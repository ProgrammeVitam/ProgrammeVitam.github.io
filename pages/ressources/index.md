---
layout: page
title: Ressources
fatherref: ressources
level: page
---

> Cette page présente pour les versions actuelle et passées de la solution logicielle Vitam, l'ensemble des ressources mises à disposition.

Trois versions de productions sont livrées à ce jour. Vous pouvez installer la Release 9 (V2 de la solution logicielle Vitam) et installer ou mettre à jour la Release 7 grâce à la version corrigée, désignée comme la version Long Time Support de la V1 de la solution logicielle. Il est déconseillé d'utiliser les Releases 6 et 8 qui ne seront pas des versions LTS.


## Solution logicielle Vitam - toutes versions publiées

Il s'agit du logiciel Vitam proprement dit, réunissant le back-office et les différentes IHM. Sont mis à dispostion :

* **le code développé**

Il est accessible sur GitHub dans le dépot GitHub [{{ site.github.repo }}]({{ site.github.repo }}).

* **les packages java (.jar) associés, diffusés pour Maven**

Ils sont accessibles en suivant utilisant ce [lien](http://download.programmevitam.fr/vitam_repository/2.1.6/mvn_repo/)

* **les paquets de déploiement**

Ils permettent d'installer de manière outillée la solution, sous forme RPM pour CentOS 7 et depuis la R3-0.15.1 sous forme deb pour Debian. Ils contiennent aussi des conteneurs de documentation et de jeux de tests.


Liens de téléchargement :

**Version 2.11.3 (Release R11)**
  - pour les packages logiciels développés et/ou packagés par Vitam ([rpm](http://download.programmevitam.fr/vitam_repository/2.11.3/rpm/vitam-product/)/[deb](http://download.programmevitam.fr/vitam_repository/2.11.3/deb/vitam-product/)),
  - pour les copies de packages officiels tiers permettant de faciliter une installation hors ligne ([rpm]( http://download.programmevitam.fr/vitam_repository/2.11.3/rpm/vitam-external/)/[deb](http://download.programmevitam.fr/vitam_repository/2.11.3/deb/vitam-external/)).
  

**Version 2.1.13 (Release R9.13)**
  - pour les packages logiciels développés et/ou packagés par Vitam ([rpm](http://download.programmevitam.fr/vitam_repository/2.1.13/rpm/vitam-product/)/[deb](http://download.programmevitam.fr/vitam_repository/2.1.13/deb/vitam-product/)),
  - pour les copies de packages officiels tiers permettant de faciliter une installation hors ligne ([rpm]( http://download.programmevitam.fr/vitam_repository/2.1.13/rpm/vitam-external/)/[deb](http://download.programmevitam.fr/vitam_repository/2.1.13/deb/vitam-external/)).




A noter, ces liens sont utilisables par les outils de gestion de paquets (yum/apt).

* **une machine virtuelle**

Elle contient une installation complète de Vitam qui permet une découverte fonctionnelle.
La solution logicielle étant prévue distribuée pour les grandes volumétries, l'ensemble des modules sont taillés au plus juste pour être dans cette seule machine virtuelle qui nécessite 4 vCPU et 8GO de mémoire pour fonctionner correctement.

La VM de la version 2.11.3 (Release 11) peut être téléchargée en suivant ce [lien](http://download.programmevitam.fr/vitam_repository/2.11.3/VM/demo_vitam_2.11.3.ova).
L'empreinte sha256 de la VM est disponible à cette [url](http://download.programmevitam.fr/vitam_repository/2.11.3/VM/demo_vitam_2.11.3.sha256).

La VM de la version 2.1.13 (Release 9) peut être téléchargée en suivant ce [lien](http://download.programmevitam.fr/vitam_repository/2.1.13/VM/demo_vitam_2.1.13.ova).
L'empreinte sha256 de la VM est disponible à cette [url](http://download.programmevitam.fr/vitam_repository/2.1.13/VM/demo_vitam_2.1.13.sha256).



* **la documentation fonctionnelle et technique**

Elle est accessible, en partie  sur GitHub pour les documents en forme brute RST, intégralement dans les packages sur Bintray, mais aussi directement sous forme PDF et/ou HTML sur la page [Documentation](/pages/documentation).

* **les Release Notes**

<https://github.com/ProgrammeVitam/vitam/releases>


## Des exemples d'usage

Vous pouvez utiliser pour tester le logiciel deux jeux de fichiers référentiels et paquets SIP:

* **Fichiers d'exemples du kit de prise en main**
([zip](http://download.programmevitam.fr/vitam_repository/2.6.1/tests/Jeu_de_tests_Guide_de_prise_en_main_R10.zip)) Ces éléments vous permettent d'effectuer les premiers paramétrages et une première entrée d'archives dans la solution logicielle Vitam en lien avec le guide de prise en main ([pdf](/ressources/DocCourante/autres/fonctionnel/VITAM_Guide_de_prise_en_main.pdf))

* **Fichiers de test du Cahier de tests métier**
([zip](http://download.programmevitam.fr/vitam_repository/2.6.0/tests/Jeux_de_tests_fonctionnels_RELEASE10.zip)) Ces éléments vous permettent de jouer les tests du cahier de test (liste des tests manuels sur les IHM) aux formats Calc ([ods](/ressources/DocCourante/autres/fonctionnel/VITAM_cahier_de_recette_fonctionnel.ods)) \| et Excel ([xlsx](/ressources/DocCourante/autres/fonctionnel/VITAM_cahier_de_recette_fonctionnel.xlsx)) 


## Outils de préservation Vitam

Les "Griffons" de préservation numérique sont des outils mobilisables pour mettre en œuvre des actions de préservation, pour l'instant analyse/validation de formats, conversion de formats.

Sont mis à dispostion :

* **les exécutables**

* URL de configuration des dépôts de binaires CentOS/RHEL : ([rpm](http://download.programmevitam.fr/vitam_griffins/1.11.0/rpm/))
* URL de configuration des repository Debian : ([deb](http://download.programmevitam.fr/vitam_griffins/1.11.0/deb/))

* **le code développé**

Il est accessible dans le dépot GitHub [Griffons](https://github.com/ProgrammeVitam/vitam-griffins/tree/1.11.0). Le 


## Outils complémentaires Vitam - RESIP, sedalib, mailextractlib...

Il s'agit des outils, applications bureautiques et bibliothèques Java de manipulation des paquets SEDA et d'extraction de messageries, réunis sous le titre de **Sedatools** :

* pour les applications
  * ``resip``: l'application de création et manipulation des SIP. Cette application permet toutes sortes de manipulations de structures d'archives que cela soit sous forme SIP, DIP ou hiérarchie sur disque.
  * ``mailextract``: l'application permettant toutes les extractions de messagerie
  * ``testsipgenerator``: l'application permettant de générer des paquets SIP simulés pour test
* pour les bibliothèques
  * ``sedalib``: la bibliothèque SEDA (manipulation de paquets SEDA conformes aux recommandations Vitam (cf "Spécifications des SIP" selon la version dans la page [Documentation](/pages/documentation))) mise en oeuvre dans ReSIP
  * ``sedalib-samples``: des exemples de code d'usage pour construire des SIP complexes en peu de lignes en s'appuyant sur sedalib
  * ``mailextractlib``: la bibliothèque extraction de messageries (pst, mbox, thunderbird...) fortement paramétrable et avec une sortie facilement projetable dans un paquet SEDA

Ces outils à l'origine créés pour construire et manipuler des paquets de test ont été enrichis pour un usage en production.

Pour plus d'information :
* sur ReSIP, l'application bureautique de haut niveau réunissant toutes les fonctions, consultez la page [dédiée](/pages/ressources/resip).
* sur les autres outils, consultez le [README](/https://github.com/ProgrammeVitam/sedatools/blob/master/README.md) du dépot de code


* **le code développé**

Il contient un projet par outils et par bibliothèque, et est accessible dans le dépot GitHub [SedaTools](https://github.com/ProgrammeVitam/sedatools). 



## Présentation de la Deuxième version de production de la solution logicielle Vitam

Le 18 mars 2019 une journée de présentation de la V2 de la solution logicielle Vitam a permis à un large public de découvrir les nouvelles fonctionnalités livrées et l'état d'avancement des projets utilisateurs. L'événement a réuni 280 participants aux Archives nationales sur le site de Pierrefitte-sur-Seine. La journée était séquencée en 3 temps.


**La présentation des nouvelles fonctionnalités**

Cette première partie a permis de faire un point sur les fonctionnalités de la V2, et de les démontrer. Les éléments présentés concernaient :
* la recherche par facette, 
* le contrôle de l'indexation et des métadonnées,
* la mise à jour et la modification en masse d'une métadonnée descriptive (titre),
* le rattachement,
* les éliminations,
* la préservation.

La présentation est consultable en suivant ce lien : ([pdf](/ressources/DocCourante/autres/fonctionnel/20190318_1_présentation_1ere_partie_VITAM_préservation_VDiffusion.pdf)).

Les vidéos des différentes fonctionnalités de la V2, diffusées lors de cette session, sont accessibles sur la page [Démonstration](/pages/demonstration).


**Les actualités des projets d'implémentation**

Une deuxième partie a fait un point d'actualités et un état d'avancement des projets d'utilisation de la solution logicielle Vitam : 
* Adamant (Ministère de la Culture/Archives nationales), 
* Archipel (Ministère des Armées), 
* Saphir (Ministère de l'Europe et des Affaires étrangères), 
* Siamae (Ministère de la Transition Ecologique et Solidaire)
	* La présentation de ces projets est consultable en suivant ce lien : ([pdf](/ressources/DocCourante/autres/fonctionnel/20190318_2_présentation_V2_2e_partie_VDiffusion.pdf))
* et Vitam/in (CEA)
	* La présentation de ce projet est consultable en suivant ce lien : ([pdf](/ressources/DocCourante/autres/fonctionnel/20190318_3_présentation_V2_2e_partie_VITAMIN_VDiffusion.pdf))


**Les outils de préparation des versements**

Une troisème partie était consacrée aux outils de préparation des versements d'archives numériques : 
* Octave (Ministère de la Culture/SIAF), 
* Archifiltre (Ministères sociaux), 
* SedaTools (Vitam)
	* La présentation de ces projets est consultable en suivant ce lien :  ([pdf](/ressources/DocCourante/autres/fonctionnel/20190318_4_présentation_V2_3e_partie_préparation_versement_VDiffusion.pdf))


## Présentation de la Première version de production de la solution logicielle Vitam

Une présentation de la Première version de production de la solution logicielle Vitam a eu lieu aux Archives nationales le 11 avril 2018, réunissant environ 250 personnes. Le support de présentation est consultable ici : ([pdf](/ressources/Doc1.0.0/autres/fonctionnel/20180411_présentation_vitam_V5.0_publication.pdf))


<br>
<hr/>

## Anciennes ressources

### API alpha

* Package de présentation ([zip](/ressources/API-Alpha/Vitam-API-Alpha-07-2016.zip)) comprenant
	* un fichier README.txt (version [HTML](/ressources/API-Alpha/Readme)),
	* le fichier de licence Vitam LICENCE.txt (version [HTML](/ressources/API-Alpha/LICENCE)),
	* un ensemble exécutable avec une JVM 8 (autour d'un serveur jetty) qui expose :
		* la documentation html des API Vitam (pages statiques reprises ci-dessus)
		* l'outil RAML Console permettant de manière dynamique de visualiser la documentation RAML et de faire des tests ([https://github.com/mulesoft/api-console](https://github.com/mulesoft/api-console))
		* les Javadoc de quelques modules Vitam (query-builder, ingest.client, access.client, logbook.client)
		* les points d'entrée REST des API externes de Access (units et objects), de Logbook (operation et lifecycle) et d'Ingest en mode "bouchonné" c'est à dire que les réponses renvoyées par le serveur sont correctes vis à vis de la documentation de l'API, mais il s'agit de "fausses" données puisqu'il n'y a pas d'implémentation du back-office Vitam derrière.
	* des exemples de code Java pour l'utilisation des clients Access, Logbook et Ingest
	* des exemples de requêtes CURL vers les APIs Access et Logbook
