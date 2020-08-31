---
layout: page
title: Ressources
fatherref: ressources
level: page
---

> Cette page présente pour les versions actuelle et passées de la solution logicielle Vitam, l'ensemble des ressources mises à disposition.

Actuellement, vous pouvez tester la Release 14. Il est conseillé d’installer la Release 13, V3 de la solution logicielle Vitam, désignée comme version Long Time Support et qui a reçu une homologation de sécurité pour 2 ans. Il est aussi possible de mettre à jour la Release 9 (V2 de la solution logicielle Vitam, précédente version Long Time Support). 
Il est déconseillé d'utiliser les Releases autres qui ne seront pas des versions LTS.  


* [Solution logicielle Vitam - toutes versions publiées](#touteversion)
* [Des exemples d'usage](#exemples)
* [Outils de préservation Vitam](#preservation)
* [Outils complémentaires Vitam - RESIP, sedalib, mailextractlib...](#resip)
* [Présentation de la deuxième version de production de la solution logicielle Vitam](#journee2)


<a name="touteversion"></a>
## Solution logicielle Vitam - toutes versions publiées

Il s'agit du logiciel Vitam proprement dit, réunissant le back-office et les différentes IHM. Sont mis à dispostion :

* **le code développé**

Il est accessible sur GitHub dans le dépot GitHub [{{ site.github.repo }}]({{ site.github.repo }}).

* **les packages java (.jar) associés, diffusés pour Maven**

Ils sont accessibles en suivant utilisant ce [lien](http://download.programmevitam.fr/vitam_repository/3.6.0/mvn_repo/)

* **les paquets de déploiement**

Ils permettent d'installer de manière outillée la solution, sous forme RPM pour CentOS 7 et depuis la R3-0.15.1 sous forme deb pour Debian. Ils contiennent aussi des conteneurs de documentation et de jeux de tests.

* Publication [GitHub Vitam](https://github.com/ProgrammeVitam/vitam/tree/3.6.0)     
* Publication [GitHub Vitam-itests](https://github.com/ProgrammeVitam/vitam-itests/tree/3.6.0)    
* URL de configuration du [repository Maven](http://download.programmevitam.fr/vitam_repository/3.6.0/mvn_repo/)     
* URL de configuration des dépôts de binaires CentOS/RHEL :      
** [Vitam-product](http://download.programmevitam.fr/vitam_repository/3.6.0/rpm/vitam-product)       
** [Vitam-external](http://download.programmevitam.fr/vitam_repository/3.6.0/rpm/vitam-external)    
* URL de configuration des dépôts de binaires Debian :      
** [Vitam-product](http://download.programmevitam.fr/vitam_repository/3.6.0/deb/vitam-product)       
** [Vitam-external](http://download.programmevitam.fr/vitam_repository/3.6.0/deb/vitam-external)     

Liens de téléchargement :
[**Version 3.6.0 (Release R14)**](https://r14.env.programmevitam.fr/)

[**Version 3.0.3-1 (Release R13)**](https://r13.env.programmevitam.fr/)
  
[**Version 2.1.22 (Release R9)**](https://r9.env.programmevitam.fr/)
 



A noter, ces liens sont utilisables par les outils de gestion de paquets (yum/apt).

* **une machine virtuelle**

Elle contient une installation complète de Vitam qui permet une découverte fonctionnelle.
La solution logicielle étant prévue distribuée pour les grandes volumétries, l'ensemble des modules sont taillés au plus juste pour être dans cette seule machine virtuelle qui nécessite 4 vCPU et 8GO de mémoire pour fonctionner correctement.

La VM de la version 3.6.0 (Release 14) peut être téléchargée en suivant ce [lien](https://download.programmevitam.fr/vitam_repository/3.6.0/VM/demo_vitam_3.6.0.ova).
L'empreinte sha256 de la VM est disponible à cette [url](https://download.programmevitam.fr/vitam_repository/3.6.0/VM/demo_vitam_3.6.0.sha256).

La VM de la version 3.0.1 (Release 13) peut être téléchargée en suivant ce [lien](https://download.programmevitam.fr/vitam_repository/3.0.1/VM/demo_vitam_3.0.1.ova).
L'empreinte sha256 de la VM est disponible à cette [url](https://download.programmevitam.fr/vitam_repository/3.0.1/VM/demo_vitam_3.0.1.sha256).

La VM de la version 2.1.21 (Release 9) peut être téléchargée en suivant ce [lien](https://download.programmevitam.fr/vitam_repository/2.1.21/VM/demo_vitam_2.1.21.ova).
L'empreinte sha256 de la VM est disponible à cette [url](https://download.programmevitam.fr/vitam_repository/2.1.21/VM/demo_vitam_2.1.21.sha256).



* **la documentation fonctionnelle et technique**

Elle est accessible, en partie  sur GitHub pour les documents en forme brute RST, intégralement dans les packages sur Bintray, mais aussi directement sous forme PDF et/ou HTML sur la page [Documentation](/pages/documentation).

* **les Release Notes**

<https://github.com/ProgrammeVitam/vitam/releases>

<a name="exemples"></a>
## Des exemples d'usage

Vous pouvez utiliser pour tester le logiciel un jeu de fichiers référentiels et paquets SIP:

* **Fichiers de test du Cahier de tests métier**
([zip](http://download.programmevitam.fr/vitam_repository/3.6.0/tests/Jeux_de_tests_fonctionnels_RELEASE14.zip)) Ces éléments vous permettent de jouer les tests du cahier de test (liste des tests manuels sur les IHM) aux formats Calc ([ods](/ressources/DocCourante/autres/fonctionnel/VITAM_cahier_de_recette_fonctionnel.ods)) \| et Excel ([xlsx](/ressources/DocCourante/autres/fonctionnel/VITAM_cahier_de_recette_fonctionnel.xlsx)) 

<a name="preservation"></a>
## Outils de préservation Vitam

Les "Griffons" de préservation numérique sont des outils mobilisables pour mettre en œuvre des actions de préservation, pour l'instant analyse/validation de formats, conversion de formats.

Sont mis à dispostion :

* **les exécutables**

* URL de configuration des dépôts de binaires CentOS/RHEL : ([rpm](http://download.programmevitam.fr/vitam_griffins/1.15.0/rpm/))
* URL de configuration des repository Debian : ([deb](http://download.programmevitam.fr/vitam_griffins/1.15.0/deb/))

* **le code développé**

Il est accessible dans le dépot GitHub [Griffons](https://github.com/ProgrammeVitam/vitam-griffins/tree/1.15.0). La release note est disponible ([pdf](https://github.com/ProgrammeVitam/vitam-griffins/releases/download/1.15.0/griffins-release-notes.1.15.0.pdf)) .

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


<a name="journée2"></a>
## Présentation de la deuxième version de production de la solution logicielle Vitam

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
