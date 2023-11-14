---
layout: page
title: version 5.RC.1 (11/2021)
---
Il s'agit du logiciel Vitam proprement dit, réunissant le back-office et le front-office Vitam UI. A noter que l'IHM dite de démonstration est encore utilisée en complément de Vitam UI. Sont mis à dispostion :

* **le code développé**

Il est accessible sur GitHub dans le dépot GitHub [{{ site.github.repo }}]({{ site.github.repo }}).

* **les packages java (.jar) associés, diffusés pour Maven**

Ils sont accessibles en suivant utilisant ce [lien](https://download.programmevitam.fr/vitam_repository/5.1/mvn_repo/).

* **les paquets de déploiement**

Ils permettent d'installer de manière outillée la solution, sous forme RPM pour CentOS 7 et sous forme deb pour Debian. Ils contiennent aussi des conteneurs de documentation et de jeux de tests.




### Pour la version 5.rc.1 (novembre 2021)

[Release note générale](/ressources/RefCourant/Release_notes_5.rc.1.pdf)  
[Change-log Vitam back-office](https://github.com/ProgrammeVitam/vitam/releases/download/5.rc.1/changelog_vitam_5.rc.1.pdf)  
[Change-log Vitam UI](https://github.com/ProgrammeVitam/vitam-ui/releases/download/5.rc.1/changelog_vitam-ui-5.rc.1.pdf)  

#### Vitam back-office
* Publication [GitHub Vitam](https://github.com/ProgrammeVitam/vitam/tree/master_5.rc.1)
* URL de configuration du [repository Maven](https://download.programmevitam.fr/vitam_repository/5.rc.1/)
* URL de configuration des dépôts de binaires CentOS/RHEL :  
	** [vitam-product](https://download.programmevitam.fr/vitam_repository/5.rc.1/rpm/vitam-product/)  
	** [vitam-external](https://download.programmevitam.fr/vitam_repository/5.rc.1/rpm/vitam-external/)
* URL de configuration des dépôts de binaires Debian :  
	** [vitam-external](https://download.programmevitam.fr/vitam_repository/5.rc.1/deb/vitam-external/)  
	** [vitam-product](https://download.programmevitam.fr/vitam_repository/5.rc.1/deb/vitam-product/)


#### Vitam UI
* Publication [GitHub Vitam UI](https://github.com/ProgrammeVitam/vitam-ui/releases/tag/5.rc.1)
* URL de configuration du [repository Maven](https://download.programmevitam.fr/vitamui/5.rc.1/)
* URL de configuration des [dépôts de binaires CentOS/RHEL](https://download.programmevitam.fr/vitamui/5.rc.1/rpm/)

[Documentation de la version 5.rc.1](https://www.programmevitam.fr/pages/documentation/liste_doc_ancienne/#5RC)
  


Liens de téléchargement pour les partenaires : [**version 5rc.1**](https://v5rc.env.programmevitam.fr/)   



A noter, ces liens sont utilisables par les outils de gestion de paquets (yum/apt).

* **une machine virtuelle**

Elle contient une installation complète de Vitam qui permet une découverte fonctionnelle.
La solution logicielle étant prévue distribuée pour les grandes volumétries, l'ensemble des modules sont taillés au plus juste pour être dans cette seule machine virtuelle qui nécessite 4 vCPU et 8GO de mémoire pour fonctionner correctement.

La VM de la version 5.RC peut être téléchargée en suivant ce [lien](https://download.programmevitam.fr/vitam_repository/5.rc.1/VM/demo_vitam_5.rc.1.ova).
L'empreinte sha256 de la VM est disponible à cette [url](https://download.programmevitam.fr/vitam_repository/5.rc.1/VM/demo_vitam_5.rc.1.sha256).

* **la documentation fonctionnelle et technique**

Elle est accessible, en partie  sur GitHub pour les documents en forme brute RST, intégralement dans les packages sur Bintray, mais aussi directement sous forme PDF et/ou HTML sur la page [Documentation](/pages/documentation).

* **les Release Notes**

<https://github.com/ProgrammeVitam/vitam/releases>

## Des exemples d'usage

Vous pouvez utiliser pour tester le logiciel un jeu de fichiers référentiels et paquets SIP:

* **Fichiers de test du Cahier de tests métier**
([zip](https://download.programmevitam.fr/jeux_de_tests/v5/Jeux_de_tests_fonctionnels_V5_RC.zip)) Ces éléments vous permettent de jouer les tests du cahier de test (liste des tests manuels sur les IHM) aux formats Calc ([ods](https://www.programmevitam.fr/ressources/Doc5.RC/autres/fonctionnel/VITAM_cahier_de_recette_fonctionnel.ods)) \| et Excel ([xlsx](https://www.programmevitam.fr/ressources/Doc5.RC/autres/fonctionnel/VITAM_cahier_de_recette_fonctionnel.xlsx)) 