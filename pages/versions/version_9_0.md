---
layout: page
title: version 9.0 (12/2025)
fatherref: versions
---
* [Mise à disposition du code](#github)
* [Package Java](#java)
* [Paquets de déploiement](#déploiement)
* [Machine virtuelle](#vm)
* [Documentation](#doc)
* [Release note](#rn)


Il s'agit du logiciel Vitam proprement dit, réunissant le back-office et le front-office Vitam UI. 
La présentation des fonctionnalités est [disponible sur cet article](https://www.programmevitam.fr/2025/12/23/version9_0/).

Sont mis à dispostion :

<a name="github"></a>
### Le code développé

Il est accessible sur GitHub dans le dépot GitHub [{{ site.github.repo }}]({{ site.github.repo }}).

<a name="java"></a>
### Les packages java (.jar) associés, diffusés pour Maven

Ils sont accessibles en suivant utilisant ce [lien](https://download.programmevitam.fr/vitam_repository/9.0.0/mvn_repo/).

<a name="déploiement"></a>
### Les paquets de déploiement

Ils permettent d'installer de manière outillée la solution, sous forme RPM pour Alma Linux et sous forme deb pour Debian. Ils contiennent aussi des conteneurs de documentation et de jeux de tests.  
    - Pour [Vitam](https://github.com/ProgrammeVitam/deployment/tree/9.0.0/vitam)  
    - Pour [Vitam UI](https://github.com/ProgrammeVitam/deployment/tree/9.0.0/vitam-ui)

#### *Vitam back-office*

- Publication [GitHub Vitam](https://github.com/ProgrammeVitam/vitam/tree/9.0.0)
- URL de configuration du [repository Maven](https://download.programmevitam.fr/vitam_repository/9.0.0/mvn_repo/) 
- URL de configuration des dépôts de binaires CentOS/RHEL :  
    - [vitam-product](https://download.programmevitam.fr/vitam_repository/9.0.0/rpm/vitam-product/)  
    - [vitam-external](https://download.programmevitam.fr/vitam_repository/9.0.0/rpm/vitam-external/)  
- URL de configuration des dépôts de binaires Debian :  
    - [vitam-product](https://download.programmevitam.fr/vitam_repository/9.0.0/deb/vitam-product/)  
    - [vitam-external](https://download.programmevitam.fr/vitam_repository/9.0.0/deb/vitam-external/)


#### *Vitam UI*

- Publication [GitHub Vitam UI](https://github.com/ProgrammeVitam/vitam-ui/tree/9.0.0)
- URL de configuration du [repository Maven](https://download.programmevitam.fr/vitamui_repository/9.0.0/mvn_repo/)
- URL de configuration des [dépôts de binaires CentOS/RHEL](https://download.programmevitam.fr/vitamui_repository/9.0.0/rpm/)
- URL de configuration des [dépôts de binaires Debian](https://download.programmevitam.fr/vitamui_repository/9.0.0/deb/)

Liens de téléchargement pour les partenaires :  [**version 9.0.**](https://releases.programmevitam.fr/9.0.0/index.html)

<a name="doc"></a>  
### La documentation fonctionnelle et technique

Elle est accessible, en partie sur GitHub pour les documents en forme brute RST, mais aussi directement sous forme PDF et/ou HTML sur la page [Documentation](/pages/documentation).

<a name="rn"></a>  
### La release note

- la [release note de la version 9.0.0](/ressources/RefCourant/Release notes9.0_v1.0.pdf)
- le [change-log du back-office](/ressources/RefCourant/vitam-changelog.9.0.0.pdf)
- le [change-log du front-office](/ressources/RefCourant/vitamui-changelog.9.0.0.pdf)