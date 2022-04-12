---
layout: page
title: Ressources
fatherref: ressources
level: page
---

> Cette page présente pour les versions actuelle et passées de la solution logicielle Vitam, l'ensemble des ressources mises à disposition.

* [Solution logicielle Vitam - toutes versions publiées](#touteversion)
* [Des exemples d'usage](#exemples)
* [Outils de préservation Vitam](#preservation)
* [Outils complémentaires Vitam - RESIP, sedalib, mailextractlib...](#resip)


Actuellement, 2 versions de la solution logicielle Vitam sont livrées chaque année :
- au printemps, une version majeure. Exemple la V5 en avril 2022.
- à l'automne, une version appelée release candidate (RC). Exemple la V5.RC en novembre 2021.
Les 2 versions sont homologuées.




<a name="touteversion"></a>
## Solution logicielle Vitam - toutes versions publiées

Il s'agit du logiciel Vitam proprement dit, réunissant le back-office et le front-office Vitam UI. A noter que l'IHM dite de démonstration est encore utilisée en complément de Vitam UI. Sont mis à dispostion :

* **le code développé**

Il est accessible sur GitHub dans le dépot GitHub [{{ site.github.repo }}]({{ site.github.repo }}).

* **les packages java (.jar) associés, diffusés pour Maven**

Ils sont accessibles en suivant utilisant ce [lien](https://download.programmevitam.fr/vitam_repository/5.0/mvn_repo/).

* **les paquets de déploiement**

Ils permettent d'installer de manière outillée la solution, sous forme RPM pour CentOS 7 et sous forme deb pour Debian. Ils contiennent aussi des conteneurs de documentation et de jeux de tests.

### Pour la version 5 (avril 2022)

- [Release note générale](/ressources/RefCourant/Release_notes_5.0.pdf)  
- [Change-log Vitam back-office](https://github.com/ProgrammeVitam/vitam/releases/download/5.0/changelog_vitam_5.0.pdf)  
- [Change-log Vitam UI](https://github.com/ProgrammeVitam/vitam-ui/releases/download/5.0/changelog_vitam-ui-5.0.pdf)  


#### *Vitam back-office*
* Publication [GitHub Vitam](https://github.com/ProgrammeVitam/vitam/tree/5.0)
* URL de configuration du [repository Maven](https://download.programmevitam.fr/vitam_repository/5.0/)
* URL de configuration des dépôts de binaires CentOS/RHEL :  
	* [vitam-product](https://download.programmevitam.fr/vitam_repository/5.0/rpm/vitam-product/)  
	* [vitam-external](https://download.programmevitam.fr/vitam_repository/5.0/rpm/vitam-external/)
* URL de configuration des dépôts de binaires Debian :  
	* [vitam-external](https://download.programmevitam.fr/vitam_repository/5.0/deb/vitam-external/)  
	* [vitam-product](https://download.programmevitam.fr/vitam_repository/5.0/deb/vitam-product/)


#### *Vitam UI*
* Publication [GitHub Vitam UI](https://github.com/ProgrammeVitam/vitam-ui/releases/tag/5.0)
* URL de configuration du [repository Maven](https://download.programmevitam.fr/vitamui/5.0/)
* URL de configuration des [dépôts de binaires CentOS/RHEL](https://download.programmevitam.fr/vitamui/5.0/rpm/)


[Documentation de la version 5.0](https://www.programmevitam.fr/pages/documentation/)


Liens de téléchargement pour les partenaires :  [**version 5.0**](https://v5.env.programmevitam.fr/)   


### Pour la version 5.rc.1 (novembre 2021)

[Release note générale](/ressources/RefCourant/Release_notes_5.rc.1.pdf)  
[Change-log Vitam back-office](https://github.com/ProgrammeVitam/vitam/releases/download/5.rc.1/changelog_vitam_5.rc.1.pdf)  
[Change-log Vitam UI](https://github.com/ProgrammeVitam/vitam-ui/releases/download/5.rc.1/changelog_vitam-ui-5.rc.1.pdf)  

#### Vitam back-office
* Publication [GitHub Vitam](https://github.com/ProgrammeVitam/vitam/tree/master_5.rc.1)
* URL de configuration du [repository Maven](https://download.programmevitam.fr/vitam_repository/5.rc.1/)
* URL de configuration des dépôts de binaires CentOS/RHEL :  
	* [vitam-product](https://download.programmevitam.fr/vitam_repository/5.rc.1/rpm/vitam-product/)  
	* [vitam-external](https://download.programmevitam.fr/vitam_repository/5.rc.1/rpm/vitam-external/)
* URL de configuration des dépôts de binaires Debian :  
	* [vitam-external](https://download.programmevitam.fr/vitam_repository/5.rc.1/deb/vitam-external/)  
	* [vitam-product](https://download.programmevitam.fr/vitam_repository/5.rc.1/deb/vitam-product/)


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

La VM de la version 5 peut être téléchargée en suivant ce [lien](https://download.programmevitam.fr/vitam_repository/5.0/VM/demo_vitam_5.0.ova).
L'empreinte sha256 de la VM est disponible à cette [url](https://download.programmevitam.fr/vitam_repository/5.0/VM/demo_vitam_5.0.sha256).





* **la documentation fonctionnelle et technique**

Elle est accessible, en partie  sur GitHub pour les documents en forme brute RST, intégralement dans les packages sur Bintray, mais aussi directement sous forme PDF et/ou HTML sur la page [Documentation](/pages/documentation).

* **les Release Notes**

<https://github.com/ProgrammeVitam/vitam/releases>

<a name="exemples"></a>
## Des exemples d'usage

Vous pouvez utiliser pour tester le logiciel un jeu de fichiers référentiels et paquets SIP:

* **Fichiers de test du Cahier de tests métier**
([zip](https://download.programmevitam.fr/jeux_de_tests/v5/Jeux_de_tests_fonctionnels_V5.zip)) Ces éléments vous permettent de jouer les tests du cahier de test (liste des tests manuels sur les IHM) aux formats Calc ([ods](/ressources/DocCourante/autres/fonctionnel/VITAM_cahier_de_recette_fonctionnel.ods)) \| et Excel ([xlsx](/ressources/DocCourante/autres/fonctionnel/VITAM_cahier_de_recette_fonctionnel.xlsx)) 

<a name="preservation"></a>
## Outils de préservation Vitam

Les "Griffons" de préservation numérique sont des outils mobilisables pour mettre en œuvre des actions de préservation, pour l'instant analyse/validation de formats, conversion de formats.

Sont mis à dispostion :

* **les exécutables**

* URL de configuration des dépôts de binaires CentOS/RHEL : ([rpm](http://download.programmevitam.fr/vitam_griffins/1.16.0/rpm/))
* URL de configuration des repository Debian : ([deb](http://download.programmevitam.fr/vitam_griffins/1.16.0/deb/))

* **le code développé**

Il est accessible dans le dépot GitHub [Griffons](https://github.com/ProgrammeVitam/vitam-griffins/tree/1.16.0).

<a name="resip"></a>
## Outils complémentaires Vitam - RESIP, sedalib, mailextractlib...

Il s'agit des outils, applications bureautiques et bibliothèques Java de manipulation des paquets SEDA et d'extraction de messageries, réunis sous le titre de **Sedatools** :

* pour les applications
  * ``resip``: cette application permet toutes sortes de manipulations de structures d'archives que cela soit sous forme SIP, DIP, hiérarchie sur disque ou issues de l'extraction d'un conteneur de messagerie.
  * ``mailextract``: cette application permet toutes les extractions de conteneurs de messagerie
  * ``testsipgenerator``: cette application permet de générer des paquets SIP simulés pour test
* pour les bibliothèques
  * ``sedalib``: la bibliothèque SEDA (manipulation de paquets SEDA conformes aux recommandations Vitam (cf "Spécifications des SIP" selon la version dans la page [Documentation](/pages/documentation))) mise en oeuvre dans ReSIP
  * ``sedalib-samples``: des exemples de code d'usage pour construire des SIP complexes en peu de lignes en s'appuyant sur sedalib
  * ``mailextractlib``: la bibliothèque extraction de messageries (pst, mbox, thunderbird...) fortement paramétrable et avec une sortie facilement projetable dans un paquet SEDA, mise en oeuvre dans ReSIP et mailextract

Ces outils à l'origine créés pour construire et manipuler des paquets de test ont été enrichis pour un usage en production.

Pour plus d'information :
* sur ReSIP, l'application bureautique de haut niveau réunissant toutes les fonctions, consultez la page [dédiée](/pages/ressources/resip).
* sur les autres outils, consultez le [README](https://github.com/ProgrammeVitam/sedatools/blob/master/README.md) du dépôt de code


* **le code développé**

Il contient un projet par outils et par bibliothèque, et est accessible dans le dépôt GitHub [SedaTools](https://github.com/ProgrammeVitam/sedatools). 