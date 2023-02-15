---
layout: page
title: version 5.1 (décembre 2022)
fatherref: ressources
---
* [Mise à disposition du code](#github)
* [Package Java](#java)
* [Paquets de déploiement](#déploiement)
* [Machine virtuelle](#vm)
* [Documentation](#doc)
* [Release note](#rn)
* [Exemples d'usage](#tests)
* [Démonstration](#demo)

- Avril 2022 - communication sur la publication de la version 5 : [Offre froide, module de collecte, enrichissements et nouvelles fonctionnalités au menu de la V5 de Vitam](http://www.programmevitam.fr/2022/04/13/Version5/)

Il s'agit du logiciel Vitam proprement dit, réunissant le back-office et le front-office Vitam UI. A noter que l'IHM dite de démonstration est encore utilisée en complément de Vitam UI. Sont mis à dispostion :

<a name="github"></a>
* **le code développé**

Il est accessible sur GitHub dans le dépot GitHub [{{ site.github.repo }}]({{ site.github.repo }}).

<a name="java"></a>
* **les packages java (.jar) associés, diffusés pour Maven**

Ils sont accessibles en suivant utilisant ce [lien](https://download.programmevitam.fr/vitam_repository/5.1/mvn_repo/).

<a name="déploiement"></a>
* **les paquets de déploiement**

Ils permettent d'installer de manière outillée la solution, sous forme RPM pour CentOS 7 et sous forme deb pour Debian. Ils contiennent aussi des conteneurs de documentation et de jeux de tests.


- [Change-log Vitam back-office](https://github.com/ProgrammeVitam/vitam/releases/download/5.1/changelog_vitam.5.1.pdf)  
- [Change-log Vitam UI](https://github.com/ProgrammeVitam/vitam-ui/releases/download/5.1/changelog-vitam-UI.5.1.pdf) 

#### *Vitam back-office*

- Publication [GitHub Vitam](https://github.com/ProgrammeVitam/vitam/tree/5.1)
- URL de configuration du [repository Maven](https://download.programmevitam.fr/vitam_repository/5.1/mvn_repo/) 
- URL de configuration des dépôts de binaires CentOS/RHEL :
-* [vitam-product](https://download.programmevitam.fr/vitam_repository/5.1/rpm/vitam-product/)
-* [vitam-external](https://download.programmevitam.fr/vitam_repository/5.1/rpm/vitam-external/)
- URL de configuration des dépôts de binaires Debian :
-* [vitam-product](https://download.programmevitam.fr/vitam_repository/5.1/deb/vitam-product/)
-* [vitam-external](https://download.programmevitam.fr/vitam_repository/5.1/deb/vitam-external/)


#### *Vitam UI*

- Publication [GitHub Vitam UI](https://github.com/ProgrammeVitam/vitam-ui/tree/5.1)
- URL de configuration du [repository Maven](https://download.programmevitam.fr/vitamui/5.1/mvn_repo/)
- URL de configuration des [dépôts de binaires CentOS/RHEL](https://download.programmevitam.fr/vitamui/5.1/rpm/)
- URL de configuration des dépôts de binaires Debian:
https://download.programmevitam.fr/vitamui/5.1/deb/


[Documentation de la version 5.0](https://www.programmevitam.fr/pages/documentation/)
[Release note générale](/ressources/RefCourant/Release_notes_5.0.pdf)  

Liens de téléchargement pour les partenaires :  [**version 5.1**](https://support.programmevitam.fr/releases/5.1/index.html)

<a name="vm"></a>
* **une machine virtuelle**

Elle contient une installation complète de Vitam qui permet une découverte fonctionnelle.
La solution logicielle étant prévue distribuée pour les grandes volumétries, l'ensemble des modules sont taillés au plus juste pour être dans cette seule machine virtuelle qui nécessite 4 vCPU et 8GO de mémoire pour fonctionner correctement.

La VM de la version 5 peut être téléchargée en suivant ce [lien](https://download.programmevitam.fr/vitam_repository/5.0/VM/demo_vitam_5.0.ova).
L'empreinte sha256 de la VM est disponible à cette [url](https://download.programmevitam.fr/vitam_repository/5.0/VM/demo_vitam_5.0.sha256).

<a name="doc"></a>  
* **la documentation fonctionnelle et technique**

Elle est accessible, en partie  sur GitHub pour les documents en forme brute RST, intégralement dans les packages sur Bintray, mais aussi directement sous forme PDF et/ou HTML sur la page [Documentation](/pages/documentation).

<a name="rn"></a>  
* **les Release Notes**

<https://github.com/ProgrammeVitam/vitam/releases>

<a name="tests"></a>  
* **Fichiers de test du Cahier de tests métier**
Vous pouvez utiliser pour tester le logiciel un jeu de fichiers référentiels et paquets SIP:

([zip](https://download.programmevitam.fr/jeux_de_tests/v5/Jeux_de_tests_fonctionnels_V5.zip)) Ces éléments vous permettent de jouer les tests du cahier de test (liste des tests manuels sur les IHM) aux formats Calc ([ods](/ressources/DocCourante/autres/fonctionnel/VITAM_cahier_de_recette_fonctionnel.ods)) \| et Excel ([xlsx](/ressources/DocCourante/autres/fonctionnel/VITAM_cahier_de_recette_fonctionnel.xlsx)) 

<a name="demo"></a>
* **Démonstration de la version 5**

Jeudi 30 juin 2022 était organisée une journée de présentation de la version 5 de la solution logicielle Vitam, occasion de démontrer les nouvelles fonctionnalités mais aussi de faire le point sur les actualités du Programme Vitam et sur l'avancée d'autres projets.

![Logos](/public/images/v5-publication_58361219.png)

<iframe width="560" height="315" src="https://www.youtube.com/embed/_BPYRi0hhYo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Par Emmanuel LABORDE, directeur du Programme Vitam, Alice GRIPPON, directrice de la diffusion et des partenariats, Marion VILLE, experte fonctionnelle, Thierry DEVILLECHABROLLE, architecte technique, et Isabelle JOSSE, experte fonctionnelle sur le projet Vitam accessible en service.

<p style="text-align: center;">
<object data="/ressources/RefCourant/20220630_Vitam_v5_presentation_v1.1.pdf" type="application/pdf" width="700px" height="600px">
    <embed src="/ressources/RefCourant/20220630_Vitam_v5_presentation_v1.1.pdf" type="application/pdf">
        <p>This browser does not support PDFs. Please download the PDF to view it: <a href="/ressources/RefCourant/20220630_Vitam_v5_presentation_v1.1.pdf">Download PDF</a>.</p>
    </embed>


[Découvrir la présentation](/ressources/RefCourant/20220630_Vitam_v5_presentation_v1.1.pdf)