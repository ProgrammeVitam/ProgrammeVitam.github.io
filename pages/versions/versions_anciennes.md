---
layout: page
title: Anciennes versions
fatherref: versions
---

> Cette page présente pour les versions actuelle et passées de la solution logicielle Vitam, l'ensemble des ressources mises à disposition.

Actuellement, 2 versions de la solution logicielle Vitam sont livrées chaque année :
- au printemps, une version majeure. Exemple la V5 en avril 2022.
- à l'automne, une version appelée release candidate (RC). Exemple la V5.RC en novembre 2021.
Les 2 versions sont homologuées.

* [Solution logicielle Vitam - toutes versions publiées](#touteversion)
* [Version 5](#version5)
* [Version 5.RC](#version5RC)
* [Version 4](#version4)
* [Version 3](#version3)

<a name="touteversion"></a>
## Solution logicielle Vitam - toutes versions publiées

Il s'agit du logiciel Vitam proprement dit, réunissant le back-office et le front-office Vitam UI. A noter que l'IHM dite de démonstration est encore utilisée en complément de Vitam UI. Sont mis à dispostion :

* **le code développé**

Il est accessible sur GitHub dans le dépot GitHub [{{ site.github.repo }}]({{ site.github.repo }}).

* **les packages java (.jar) associés, diffusés pour Maven**

Ils sont accessibles en suivant utilisant ce [lien](https://download.programmevitam.fr/vitam_repository/5.0/mvn_repo/)

* **les paquets de déploiement**

Ils permettent d'installer de manière outillée la solution, sous forme RPM pour CentOS 7 et sous forme deb pour Debian. Ils contiennent aussi des conteneurs de documentation et de jeux de tests.

<a name="version5"></a>
### Pour la version 5.3 (avril 2022)

- Avril 2022 - communication sur la publication de la version 5 : [Offre froide, module de collecte, enrichissements et nouvelles fonctionnalités au menu de la V5 de Vitam](http://www.programmevitam.fr/2022/04/13/Version5/)
- [Publication de la version 5 de Vitam](/pages/ressources/version_5_1.md)

#### Publication Vitam

- [Publication GitHub Vitam](https://github.com/ProgrammeVitam/vitam/tree/5.3)

- [URL de configuration du repository Maven](https://download.programmevitam.fr/vitam_repository/5.3/mvn_repo/)

- URL de configuration des dépôts de binaires CentOS/RHEL :
    - [Vitam-product](https://download.programmevitam.fr/vitam_repository/5.3/rpm/vitam-product/)
    - [Vitam-external](https://download.programmevitam.fr/vitam_repository/5.3/rpm/vitam-external/)

- URL de configuration des dépôts de binaires Debian :
    - [Vitam-product](https://download.programmevitam.fr/vitam_repository/5.3/deb/vitam-product/)
    - [Vitam-external](https://download.programmevitam.fr/vitam_repository/5.3/deb/vitam-external/)

- [Release notes](https://github.com/ProgrammeVitam/vitam/releases/download/5.3/)
 

#### Publication Vitam UI

- [Publication GitHub Vitam UI](https://github.com/ProgrammeVitam/vitam-ui/tree/5.3)

- [URL de configuration du repository Maven](https://download.programmevitam.fr/vitamui/5.3/mvn_repo/)

- [URL de configuration des dépôts de binaires CentOS/RHEL](https://download.programmevitam.fr/vitamui/5.3/rpm/)

<p style="text-align: center;">
<object data="/ressources/RefCourant/changelog_vitam_5.3.pdf" type="application/pdf" width="600px" height="750px">
    <embed src="/ressources/RefCourant/changelog_vitam_5.3.pdf" type="application/pdf">
        <p>This browser does not support PDFs. Please download the PDF to view it: <a href="/ressources/RefCourant/changelog_vitam_5.3.pdf">Download PDF</a>.</p>
    </embed>
</object>
</p>

<a name="version5RC"></a>
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

<a name="version4"></a>
### Pour la 4.0.7 de la R16 (mise à jour en mars 2023)

Releases note [back](/ressources/RefCourant/VitamBO_release-notes.4.0.4.pdf) et [front](/ressources/RefCourant/VitamUI_release-notes.4.0.4.pdf)

#### Vitam back-office
* Publication [GitHub Vitam](https://github.com/ProgrammeVitam/vitam/tree/4.0.7)  

* URL de configuration du [repository Maven](http://download.programmevitam.fr/vitam_repository/4.0.7/mvn_repo/)  
* URL de configuration des dépôts de binaires CentOS/RHEL :  
	* [Vitam-product](http://download.programmevitam.fr/vitam_repository/4.0.7/rpm/vitam-product)  
	* [Vitam-external](http://download.programmevitam.fr/vitam_repository/4.0.7/rpm/vitam-external)  
* URL de configuration des dépôts de binaires Debian :  
	- [Vitam-product](http://download.programmevitam.fr/vitam_repository/4.0.7/deb/vitam-product)  
	- [Vitam-external](http://download.programmevitam.fr/vitam_repository/4.0.7/deb/vitam-external)  
   

#### Vitam UI
* Publication [GitHub Vitam UI](https://github.com/ProgrammeVitam/vitam-ui/tree/4.0.5)  
* URL de configuration du [repository Maven](https://download.programmevitam.fr/vitamui/4.0.5/mvn_repo/)  
* URL de configuration des [dépôts de binaires CentOS/RHEL](https://download.programmevitam.fr/vitamui/4.0.5/rpm/)  

<a name="version3"></a>
### Pour la 3.0.16 de la R13 (mise à jour en juillet 2021)
* [Publication GitHub Vitam](https://github.com/ProgrammeVitam/vitam/tree/3.0.16)  
* URL de configuration du [repository Maven](https://download.programmevitam.fr/vitam_repository/3.0.16/mvn_repo/)  
* URL de configuration des dépôts de binaires CentOS/RHEL :  
	- [Vitam-product](https://download.programmevitam.fr/vitam_repository/3.0.16/rpm/vitam-product/)  
	- [Vitam-external](https://download.programmevitam.fr/vitam_repository/3.0.16/rpm/vitam-external/)  
* URL de configuration des dépôts de binaires Debian :  
	- [Vitam-product](https://download.programmevitam.fr/vitam_repository/3.0.16/deb/vitam-product/)  
	- [Vitam-external](https://download.programmevitam.fr/vitam_repository/3.0.16/deb/vitam-external/)  
* [Release notes](https://github.com/ProgrammeVitam/vitam/releases/download/3.0.16/release-notes.3.0.16.pdf)  

[Documentation de la version 3.0.16](https://www.programmevitam.fr/pages/documentation/liste_doc_ancienne/#R13_16)

* **la documentation fonctionnelle et technique**

Elle est accessible, en partie  sur GitHub pour les documents en forme brute RST, intégralement dans les packages sur Bintray, mais aussi directement sous forme PDF et/ou HTML sur la page [Documentation](/pages/documentation).

* **les Release Notes**

<https://github.com/ProgrammeVitam/vitam/releases>