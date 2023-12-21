---
layout: page
title: version 6.2 (12/2023)
fatherref: ressources
---
* [Mise à disposition du code](#github)
* [Package Java](#java)
* [Paquets de déploiement](#déploiement)
* [Machine virtuelle](#vm)
* [Documentation](#doc)
* [Release note](#rn)


Il s'agit du logiciel Vitam proprement dit, réunissant le back-office et le front-office Vitam UI. A noter que l'IHM dite de démonstration est encore utilisée en complément de Vitam UI. Sont mis à dispostion :

<a name="github"></a>
* **le code développé**

Il est accessible sur GitHub dans le dépot GitHub [{{ site.github.repo }}]({{ site.github.repo }}).

<a name="java"></a>
* **les packages java (.jar) associés, diffusés pour Maven**

Ils sont accessibles en suivant utilisant ce [lien](https://download.programmevitam.fr/vitam_repository/6.2/mvn_repo/).

<a name="déploiement"></a>
* **les paquets de déploiement**

Ils permettent d'installer de manière outillée la solution, sous forme RPM pour CentOS 7 et sous forme deb pour Debian. Ils contiennent aussi des conteneurs de documentation et de jeux de tests.  
    - Pour [Vitam](https://github.com/ProgrammeVitam/deployment/tree/6.2/vitam)  
    - Pour [Vitam UI](https://github.com/ProgrammeVitam/deployment/tree/6.2/vitam-ui)

#### *Vitam back-office*

- Publication [GitHub Vitam](https://github.com/ProgrammeVitam/vitam/tree/6.2)
- URL de configuration du [repository Maven](hhttps://download.programmevitam.fr/vitam_repository/6.2/mvn_repo/) 
- URL de configuration des dépôts de binaires CentOS/RHEL :  
    - [vitam-product](https://download.programmevitam.fr/vitam_repository/6.2/rpm/vitam-product/)  
    - [vitam-external](https://download.programmevitam.fr/vitam_repository/6.2/rpm/vitam-external/)  
- URL de configuration des dépôts de binaires Debian :  
    - [vitam-product](https://download.programmevitam.fr/vitam_repository/6.2/deb/vitam-product/ )  
    - [vitam-external](https://download.programmevitam.fr/vitam_repository/6.2/deb/vitam-external/)


#### *Vitam UI*

- Publication [GitHub Vitam UI](https://github.com/ProgrammeVitam/vitam-ui/tree/6.2)
- URL de configuration du [repository Maven](https://download.programmevitam.fr/vitamui/6.2/mvn_repo/)
- URL de configuration des [dépôts de binaires CentOS/RHEL](https://download.programmevitam.fr/vitamui/6.2/rpm/)
- URL de configuration des [dépôts de binaires Debian](https://download.programmevitam.fr/vitamui/6.2/deb/)


Liens de téléchargement pour les partenaires :  [**version 6.2**](https://support.programmevitam.fr/releases/6.2/index.html)

<a name="rn"></a>  
* **la release note**

- la [release note de la version 6](/ressources/RefCourant/Release_notes_6.1_v1.pdf)
- le [change-log du back-office](/ressources/RefCourant/vitam-changelog.6.2.pdf)
- le [change-log du front-office](/ressources/RefCourant/vitamui-changelog.6.2.pdf)