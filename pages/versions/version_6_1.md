---
layout: page
title: version 6.3 (07/2024)
fatherref: versions
---

> Un hotfix 6.3-1 a été publié en septembre 2024. [Voir les informations sur ce hotfix](#hotfix).

* [Mise à disposition du code](#github)
* [Package Java](#java)
* [Paquets de déploiement](#déploiement)
* [Machine virtuelle](#vm)
* [Documentation](#doc)
* [Release note](#rn)
* [Hotfix 6.3-1](#hotfix)


Il s'agit du logiciel Vitam proprement dit, réunissant le back-office et le front-office Vitam UI. A noter que l'IHM dite de démonstration est encore utilisée en complément de Vitam UI. Sont mis à dispostion :

<a name="github"></a>
## le code développé

Il est accessible sur GitHub dans le dépot GitHub [{{ site.github.repo }}]({{ site.github.repo }}).

<a name="java"></a>
## les packages java (.jar) associés, diffusés pour Maven**

Ils sont accessibles en suivant utilisant ce [lien](https://download.programmevitam.fr/vitam_repository/6.3/mvn_repo/).

<a name="déploiement"></a>
## les paquets de déploiement

Ils permettent d'installer de manière outillée la solution, sous forme RPM pour CentOS 7 et sous forme deb pour Debian. Ils contiennent aussi des conteneurs de documentation et de jeux de tests.  
    - Pour [Vitam](https://github.com/ProgrammeVitam/deployment/tree/6.3/vitam)  
    - Pour [Vitam UI](https://github.com/ProgrammeVitam/deployment/tree/6.3/vitam-ui)

### *Vitam back-office*

- Publication [GitHub Vitam](https://github.com/ProgrammeVitam/vitam/tree/6.3)
- URL de configuration du [repository Maven](hhttps://download.programmevitam.fr/vitam_repository/6.3/mvn_repo/) 
- URL de configuration des dépôts de binaires CentOS/RHEL :  
    - [vitam-product](https://download.programmevitam.fr/vitam_repository/6.3/rpm/vitam-product/)  
    - [vitam-external](https://download.programmevitam.fr/vitam_repository/6.3/rpm/vitam-external/)  
- URL de configuration des dépôts de binaires Debian :  
    - [vitam-product](https://download.programmevitam.fr/vitam_repository/6.3/deb/vitam-product/ )  
    - [vitam-external](https://download.programmevitam.fr/vitam_repository/6.3/deb/vitam-external/)

### *Vitam UI*

- Publication [GitHub Vitam UI](https://github.com/ProgrammeVitam/vitam-ui/tree/6.3)
- URL de configuration du [repository Maven](https://download.programmevitam.fr/vitamui/6.3/mvn_repo/)
- URL de configuration des [dépôts de binaires CentOS/RHEL](https://download.programmevitam.fr/vitamui/6.3/rpm/)
- URL de configuration des [dépôts de binaires Debian](https://download.programmevitam.fr/vitamui/6.3/deb/)


Liens de téléchargement pour les partenaires :  [**version 6.3**](https://releases.programmevitam.fr/6.3/index.html)

<a name="rn"></a>  
## la release note

- la [release note de la version 6](/ressources/RefCourant/Release_notes_6.1_v1.pdf)
- le [change-log du back-office](/ressources/RefCourant/vitam-changelog.6.3.pdf)
- le [change-log du front-office](/ressources/RefCourant/vitamui-changelog.6.3.pdf)

<a name="hotfix"></a>
## Hotfix 6.3-1

**Notes et procédures spécifiques V6.3-1**

.. caution:: Veuillez appliquer les procédures spécifiques à chacune des versions précédentes en fonction de la version de départ selon la suite suivante: V6.3-1.

### Procédures à exécuter AVANT la montée de version

#### Arrêt des timers et des accès externes à Vitam

.. caution:: Cette opération doit être effectuée AVANT la montée de version vers la V6.3-1.

.. caution:: Cette opération doit être effectuée avec les sources de déploiements de l'ancienne version.

Les timers et les externals de Vitam doivent être arrêtés sur **tous les sites** :

.. code-block:: bash

    ansible-playbook -i environments/<inventaire> ansible-vitam-exploitation/stop_external.yml --ask-vault-pass
    ansible-playbook -i environments/<inventaire> ansible-vitam-exploitation/stop_vitam_scheduling.yml --ask-vault-pass
    ansible-playbook -i environments/<inventaire> ansible-vitam-exploitation/stop_vitam_scheduler.yml --ask-vault-pass

..

#### Mise à jour des dépôts (YUM/APT)

.. caution:: Cette opération doit être effectuée AVANT la montée de version

Afin de pouvoir déployer la nouvelle version, vous devez mettre à jour la variable ``vitam_repositories`` sous ``environments/group_vars/all/main/repositories.yml`` afin de renseigner les dépôts à la version cible.

Pour le dépôt vitam-external, vous devez renseigner la version adaptée à votre système d'exploitation (par exemple pour la version 7.1.0):

* CentOS 7: https://download.programmevitam.fr/vitam_repository/6.3-1/rpm/vitam-external/
* Debian 11: https://download.programmevitam.fr/vitam_repository/6.3-1/deb/vitam-external/

Puis exécutez le playbook suivant **sur tous les sites** :

.. code-block:: bash

    ansible-playbook -i environments/<inventaire> ansible-vitam-extra/bootstrap.yml --ask-vault-pass

..

#### Arrêt complet de Vitam

.. caution:: Cette opération doit être effectuée AVANT la montée de version vers la V6.3

.. caution:: Cette opération doit être effectuée avec les sources de déploiements de l'ancienne version.

Vitam doit être arrêté sur **tous les sites** :

.. code-block:: bash

    ansible-playbook -i environments/<inventaire> ansible-vitam-exploitation/stop_vitam.yml --ask-vault-pass

..

### Application de la montée de version

.. caution:: L'application de la montée de version s'effectue d'abord sur les sites secondaires puis sur le site primaire.

#### Mise à jour du composant vitam-processing

Se connecter à la VM qui héberge le composant vitam-processing
.. code-block:: bash

    yum remove vitam-processing
    yum update vitam-processing

..

#### Mise à jour du composant vitam-worker

Se connecter à la VM qui héberge le composant vitam-worker
.. code-block:: bash

    yum remove vitam-worker
    yum update vitam-worker

..

#### Mise à jour du composant vitam-logbook

Se connecter à la VM qui héberge le composant vitam-logbook
.. code-block:: bash

    yum remove vitam-logbook
    yum update vitam-logbook

..

### Procédures à exécuter APRÈS la montée de version

La montée de version est maintenant terminée, vous pouvez réactiver les services externals ainsi que les jobs Vitam sur tous les sites :

.. code-block:: bash

    ansible-playbook -i environments/<inventaire> ansible-vitam-exploitation/start_vitam.yml --ask-vault-pass
    ansible-playbook -i environments/<inventaire> ansible-vitam-exploitation/start_external.yml --ask-vault-pass
    ansible-playbook -i environments/<inventaire> ansible-vitam-exploitation/start_vitam_scheduler.yml --ask-vault-pass
    ansible-playbook -i environments/<inventaire> ansible-vitam-exploitation/start_vitam_scheduling.yml --ask-vault-pass

..