---
layout: page
title: version 7.1.1 (07/2024)
fatherref: versions
---
* [Mise à disposition du code](#github)
* [Package Java](#java)
* [Paquets de déploiement](#déploiement)
* [Machine virtuelle](#vm)
* [Documentation](#doc)
* [Release note](#rn)


Il s'agit du logiciel Vitam proprement dit, réunissant le back-office et le front-office Vitam UI. 
La présentation des fonctionnalités est [disponible sur cet article](https://www.programmevitam.fr/2024/07/12/version7_1/).
Sont mis à dispostion :

<a name="github"></a>
### Le code développé

Il est accessible sur GitHub dans le dépot GitHub [{{ site.github.repo }}]({{ site.github.repo }}).

<a name="java"></a>
### Les packages java (.jar) associés, diffusés pour Maven

Ils sont accessibles en suivant utilisant ce [lien](https://download.programmevitam.fr/vitam_repository/7.1.1/mvn_repo/).

<a name="déploiement"></a>
### Les paquets de déploiement

Ils permettent d'installer de manière outillée la solution, sous forme RPM pour CentOS 7 et sous forme deb pour Debian. Ils contiennent aussi des conteneurs de documentation et de jeux de tests.  
    - Pour [Vitam](https://github.com/ProgrammeVitam/deployment/tree/7.1.1/vitam)  
    - Pour [Vitam UI](https://github.com/ProgrammeVitam/deployment/tree/7.1.1/vitam-ui)

#### *Vitam back-office*

- Publication [GitHub Vitam](https://github.com/ProgrammeVitam/vitam/tree/7.1.1)
- URL de configuration du [repository Maven](https://download.programmevitam.fr/vitam_repository/7.1.1/mvn_repo/) 
- URL de configuration des dépôts de binaires CentOS/RHEL :  
    - [vitam-product](https://download.programmevitam.fr/vitam_repository/7.1.1/rpm/vitam-product/)  
    - [vitam-external](* https://download.programmevitam.fr/vitam_repository/7.1.1/rpm/vitam-external/)  
- URL de configuration des dépôts de binaires Debian :  
    - [vitam-product](https://download.programmevitam.fr/vitam_repository/7.1.1/deb/vitam-product/)  
    - [vitam-external](https://download.programmevitam.fr/vitam_repository/7.1.1/deb/vitam-external/)


#### *Vitam UI*

- Publication [GitHub Vitam UI](https://github.com/ProgrammeVitam/vitam-ui/tree/7.1.1)
- URL de configuration du [repository Maven](https://download.programmevitam.fr/vitamui_repository/7.1.1/mvn_repo/)
- URL de configuration des [dépôts de binaires CentOS/RHEL](https://download.programmevitam.fr/vitamui_repository/7.1.1/rpm/)
- URL de configuration des [dépôts de binaires Debian](https://download.programmevitam.fr/vitamui_repository/7.1.1/deb/)

Liens de téléchargement pour les partenaires :  [**version 7.1.1**](https://support.programmevitam.fr/releases/7.1.1/index.html)

<a name="doc"></a>  
### La documentation fonctionnelle et technique

Elle est accessible, en partie  sur GitHub pour les documents en forme brute RST, mais aussi directement sous forme PDF et/ou HTML sur la page [Documentation](/pages/documentation).

<a name="rn"></a>  
### La release note

- la [release note de la version 7.1.1](/ressources/RefCourant/Release_notes_7.1.1_vdef.pdf)
- le [change-log du back-office](/ressources/RefCourant/vitam-changelog.7.1.1.pdf)
- le [change-log du front-office](/ressources/RefCourant/vitamui-changelog.7.1.1.pdf)