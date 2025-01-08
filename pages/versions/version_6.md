---
layout: page
title: version 6
fatherref: versions
---



* [Mise à disposition du code](#github)
* [La version 6.4 - décembre 2024](#64)
* [La version 6.3 - juillet 2024](#63)
* [Hotfix 6.3-1](#hotfix)


Il s'agit du logiciel Vitam proprement dit, réunissant le back-office et le front-office Vitam UI. A noter que l'IHM dite de démonstration est encore utilisée en complément de Vitam UI. Sont mis à dispostion :

<a name="github"></a>
## Le code développé

Il est accessible sur GitHub dans le dépot GitHub [{{ site.github.repo }}]({{ site.github.repo }}).

<a name="64"></a>
## La version 6.4 (décembre 2024)

Ils sont accessibles en suivant utilisant ce [lien](https://download.programmevitam.fr/vitam_repository/6.4/mvn_repo/).

### les paquets de déploiement

Ils permettent d'installer de manière outillée la solution, sous forme RPM pour CentOS 7 et sous forme deb pour Debian. Ils contiennent aussi des conteneurs de documentation et de jeux de tests.  
    - Pour [Vitam](https://github.com/ProgrammeVitam/deployment/tree/6.4/vitam)  
    - Pour [Vitam UI](https://github.com/ProgrammeVitam/deployment/tree/6.4/vitam-ui)

#### *Vitam back-office*

- Publication [GitHub Vitam](https://github.com/ProgrammeVitam/vitam/tree/6.4)
- URL de configuration du [repository Maven](hhttps://download.programmevitam.fr/vitam_repository/6.4/mvn_repo/) 
- URL de configuration des dépôts de binaires CentOS/RHEL :  
    - [vitam-product](https://download.programmevitam.fr/vitam_repository/6.4/rpm/vitam-product/)  
    - [vitam-external](https://download.programmevitam.fr/vitam_repository/6.4/rpm/vitam-external/)  
- URL de configuration des dépôts de binaires Debian :  
    - [vitam-product](https://download.programmevitam.fr/vitam_repository/6.4/deb/vitam-product/ )  
    - [vitam-external](https://download.programmevitam.fr/vitam_repository/6.4/deb/vitam-external/)

#### *Vitam UI*

- Publication [GitHub Vitam UI](https://github.com/ProgrammeVitam/vitam-ui/tree/6.4)
- URL de configuration du [repository Maven](https://download.programmevitam.fr/vitamui/6.4/mvn_repo/)
- URL de configuration des [dépôts de binaires CentOS/RHEL](https://download.programmevitam.fr/vitamui/6.4/rpm/)
- URL de configuration des [dépôts de binaires Debian](https://download.programmevitam.fr/vitamui/6.4/deb/)

Liens de téléchargement pour les partenaires :  [**version 6.4**](https://releases.programmevitam.fr/6.4/index.html)
 
### la release note

- la [release note de la version 6](/ressources/RefCourant/Release_notes_6.1_v1.pdf)
- le [change-log du back-office](/ressources/RefCourant/vitam-changelog.6.4.pdf)
- le [change-log du front-office](/ressources/RefCourant/vitamui-changelog.6.4.pdf)


<a name="63"></a>
## La version 6.3 (juillet 2024)

> Un hotfix 6.3-1 a été publié en septembre 2024. [Voir les informations sur ce hotfix](#hotfix).

### les packages java (.jar) associés, diffusés pour Maven**

Ils sont accessibles en suivant utilisant ce [lien](https://download.programmevitam.fr/vitam_repository/6.3/mvn_repo/).

### les paquets de déploiement

Ils permettent d'installer de manière outillée la solution, sous forme RPM pour CentOS 7 et sous forme deb pour Debian. Ils contiennent aussi des conteneurs de documentation et de jeux de tests.  
    - Pour [Vitam](https://github.com/ProgrammeVitam/deployment/tree/6.3/vitam)  
    - Pour [Vitam UI](https://github.com/ProgrammeVitam/deployment/tree/6.3/vitam-ui)

#### *Vitam back-office*

- Publication [GitHub Vitam](https://github.com/ProgrammeVitam/vitam/tree/6.3)
- URL de configuration du [repository Maven](hhttps://download.programmevitam.fr/vitam_repository/6.3/mvn_repo/) 
- URL de configuration des dépôts de binaires CentOS/RHEL :  
    - [vitam-product](https://download.programmevitam.fr/vitam_repository/6.3/rpm/vitam-product/)  
    - [vitam-external](https://download.programmevitam.fr/vitam_repository/6.3/rpm/vitam-external/)  
- URL de configuration des dépôts de binaires Debian :  
    - [vitam-product](https://download.programmevitam.fr/vitam_repository/6.3/deb/vitam-product/ )  
    - [vitam-external](https://download.programmevitam.fr/vitam_repository/6.3/deb/vitam-external/)

#### *Vitam UI*

- Publication [GitHub Vitam UI](https://github.com/ProgrammeVitam/vitam-ui/tree/6.3)
- URL de configuration du [repository Maven](https://download.programmevitam.fr/vitamui/6.3/mvn_repo/)
- URL de configuration des [dépôts de binaires CentOS/RHEL](https://download.programmevitam.fr/vitamui/6.3/rpm/)
- URL de configuration des [dépôts de binaires Debian](https://download.programmevitam.fr/vitamui/6.3/deb/)

Liens de téléchargement pour les partenaires :  [**version 6.3**](https://releases.programmevitam.fr/6.3/index.html)
 
### la release note

- la [release note de la version 6](/ressources/RefCourant/Release_notes_6.1_v1.pdf)
- le [change-log du back-office](/ressources/RefCourant/vitam-changelog.6.3.pdf)
- le [change-log du front-office](/ressources/RefCourant/vitamui-changelog.6.3.pdf)

<a name="hotfix"></a>
### Notes et procédures spécifiques pour le hotfix V6.3-1

#### Présentation du hotfix

Le hotfix V6.3-1 associé à la version V6.3 de Vitam a pour but de corriger le `Bug #13307: Fix concurrent LFC traceability chaining`.

#### Mise à jour du dépôt vitam-product à l'aide des packages suivants

Ajouter les 3 packages fournis dans l'archive suivante dans votre repository `6.3/vitam-product/`:

* Pour YUM (rpm): https://releases.programmevitam.fr/6.3/vitam-hotfix-6.3-1-RPM.tar.gz
* Pour APT (deb): https://releases.programmevitam.fr/6.3/vitam-hotfix-6.3-1-DEB.tar.gz

#### Procédure d'application du hotfix

##### Arrêt de Vitam

> Attention, cette opération doit être effectuée AVANT l'application du hotfix 6.3-1.

Vitam doit être arrêter sur tous les sites, en commençant par le site primaire.

```sh
ansible-playbook -i environments/<inventaire> ansible-vitam-exploitation/stop_vitam.yml --ask-vault-pass
```

##### Application du hotfix

L'application du hotfix consiste à mettre à jour les packages processing, logbook & worker sur **tous les sites**.

```sh
ansible hosts_logbook,hosts_processing,hosts_worker -i environments/<inventaire> -m shell -a "yum upgrade vitam-*" --ask-vault-pass
```

##### Redémarrage de Vitam

L'application du hotfix étant terminée, vous pouvez redémarrer Vitam en commençant par les sites secondaires puis le site primaire.

```sh
ansible-playbook -i environments/<inventaire> ansible-vitam-exploitation/start_vitam.yml --ask-vault-pass
```










.. caution:: Veuillez appliquer les procédures spécifiques à chacune des versions précédentes en fonction de la version de départ selon la suite suivante: V6.3-1.

#### Procédures à exécuter AVANT la montée de version

##### Arrêt des timers et des accès externes à Vitam

.. caution:: Cette opération doit être effectuée AVANT la montée de version vers la V6.3-1.

.. caution:: Cette opération doit être effectuée avec les sources de déploiements de l'ancienne version.

Les timers et les externals de Vitam doivent être arrêtés sur **tous les sites** :

```sh
    ansible-playbook -i environments/<inventaire> ansible-vitam-exploitation/stop_external.yml --ask-vault-pass
    ansible-playbook -i environments/<inventaire> ansible-vitam-exploitation/stop_vitam_scheduling.yml --ask-vault-pass
    ansible-playbook -i environments/<inventaire> ansible-vitam-exploitation/stop_vitam_scheduler.yml --ask-vault-pass
```

##### Mise à jour des dépôts (YUM/APT)

> [!CAUTION]
Cette opération doit être effectuée AVANT la montée de version

Afin de pouvoir déployer la nouvelle version, vous devez mettre à jour la variable ``vitam_repositories`` sous ``environments/group_vars/all/main/repositories.yml`` afin de renseigner les dépôts à la version cible.

Pour le dépôt vitam-external, vous devez renseigner la version adaptée à votre système d'exploitation (par exemple pour la version 7.1.0):

* CentOS 7: https://download.programmevitam.fr/vitam_repository/6.3-1/rpm/vitam-external/
* Debian 11: https://download.programmevitam.fr/vitam_repository/6.3-1/deb/vitam-external/

Puis exécutez le playbook suivant **sur tous les sites** :

```sh
    ansible-playbook -i environments/<inventaire> ansible-vitam-extra/bootstrap.yml --ask-vault-pass
```

##### Arrêt complet de Vitam

> [!CAUTION]
Cette opération doit être effectuée AVANT la montée de version vers la V6.3

> [!CAUTION]
Cette opération doit être effectuée avec les sources de déploiements de l'ancienne version.

Vitam doit être arrêté sur **tous les sites** :

```sh
    ansible-playbook -i environments/<inventaire> ansible-vitam-exploitation/stop_vitam.yml --ask-vault-pass
```

#### Application de la montée de version

> [!CAUTION]
L'application de la montée de version s'effectue d'abord sur les sites secondaires puis sur le site primaire.

##### Mise à jour du composant vitam-processing

Se connecter à la VM qui héberge le composant vitam-processing

```sh
    yum remove vitam-processing
    yum update vitam-processing
```

##### Mise à jour du composant vitam-worker

Se connecter à la VM qui héberge le composant vitam-worker

```sh
    yum remove vitam-worker
    yum update vitam-worker
```

##### Mise à jour du composant vitam-logbook

Se connecter à la VM qui héberge le composant vitam-logbook

```sh
yum remove vitam-logbook
yum update vitam-logbook
```

#### Procédures à exécuter APRÈS la montée de version

La montée de version est maintenant terminée, vous pouvez réactiver les services externals ainsi que les jobs Vitam sur tous les sites :

```sh
    ansible-playbook -i environments/<inventaire> ansible-vitam-exploitation/start_vitam.yml --ask-vault-pass
    ansible-playbook -i environments/<inventaire> ansible-vitam-exploitation/start_external.yml --ask-vault-pass
    ansible-playbook -i environments/<inventaire> ansible-vitam-exploitation/start_vitam_scheduler.yml --ask-vault-pass
    ansible-playbook -i environments/<inventaire> ansible-vitam-exploitation/start_vitam_scheduling.yml --ask-vault-pass
```