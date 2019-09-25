---
layout: page
title: Resip
---

> Cette page présente le générateur ReSIP (version courante 1.10.0-SNAPSHOT compilée le 01/09/2019).

## ReSIP

L’application ReSIP, construite au dessus de la bibliothèque sedalib, permet de construire et manipuler des structures arborescentes d’archives, d’en éditer les métadonnées, de les importer  et exporter sous la forme de SIP, sous la forme de hiérarchie disque ou encore sous forme csv pour les plans de classement.

L’application est constituée d’un fichier exécutable portable (qui ne nécessite pas d’installation) ReSip.exe qui permet de lancer directement par double clic l’application en mode graphique. 

Cet exécutable peut aussi être utilisé en ligne de commande (voir paragraphe Ligne de commande) ou via le script ReSip.bat. Dans ce dernier cas un drag and drop d’une arborescence de fichier génère un SIP correspondant. Enfin un .jar est fourni pour permettre l'usage sur d'autres systèmes que Windows.

ReSIP présente de manière explicite les contenus XML, et nécessite donc une certaine connaissance du standard SEDA 2.1. Celui-ci est consultable sur le site du [SIAF](https://francearchives.fr/seda/).

Pour comprendre l’essentiel, on visera notamment la documentation technique des:
*	**manifest du SIP (message ArchiveTransfer)**  qui au plus haut niveau définit  les métadonnées globales du versement 
*	**DescriptiveMetadata** qui contient la structure des archives et des métadonnées
*	**ArchiveUnit** qui contient toutes les informations de structure et de métadonnées d’une  unité d’archives
*	**Management** qui contient toutes les informations de gestion d’une unité d’archives
*	**Content** qui contient toutes les métadonnées descriptives d’une unité d’archives

Sont mis à dispostion :


* **le paquet d'installation sous Windows**

Il s'agit d'un conteneur zip à décompresser en local et dont l'exécution 
nécessite la présence de java 8 sur le poste ou à défaut une machine java 8 dans le répertoire "jre" au niveau de l'exécutable. 

Il est accessible [ici](http://download.programmevitam.fr/resip/1.10-SNAPSHOT/Resip.zip) avec si nécessaire la [jre 64bits](http://download.programmevitam.fr/resip/1.1-SNAPSHOT/jre%2064bits.zip) ou la [jre 32bits](http://download.programmevitam.fr/resip/1.1-SNAPSHOT/jre%2032bits.zip) à ajouter dans le répertoire Resip

A noter est aussi disponible le fichier .jar utilisable sous Linux ([ici](http://download.programmevitam.fr/resip/1.10-SNAPSHOT/jar.zip)).


>**BETA**: une version beta de la V2.0 est à disposition [ici](http://download.programmevitam.fr/resip/2.0-SNAPSHOT/ResipV2.0.zip) en exécutable et [ici](http://download.programmevitam.fr/resip/2.0-SNAPSHOT/jar.zip) en jar avec notamment : 
>* une refonte ergonomique permettant une visualisation et une édition des métadonnées de manière structurée et graphique (sans XML)
>* une capacité de visualisation et de recherche dans le manifest
>* une capacité de recherche des unités d'archives sans descendance
>* compatible jdk11


* **un manuel utilisateur**

La documentation **ReSIP** décrit les fonctions de l'outil ReSIP ainsi que son utilisation simple et avancée et peut être consultée en suivant ce [lien](http://download.programmevitam.fr/resip/1.10-SNAPSHOT/20190910_Vitam_Manuel_ReSIP_V3.1.pdf)


* **un jeux de tests**

Il contient des hiérachie disque, SIP, DIP, csv... et toute une série de fichiers d'exemples importables et manipulable avec ReSIP.

Il est accessible ([ici](http://download.programmevitam.fr/resip/1.1/ResipSamples.zip)).

* **le code développé**

Il est accessible dans le dépot GitHub avec la bibliothèque sedalib [SedaTools](https://github.com/ProgrammeVitam/sedatools)
