---
layout: page
title: Resip
fatherref: ressources
level: page
---

> Cette page présente le générateur ReSIP. 

## ReSIP

L’application ReSIP, construite au dessus de la bibliothèque sedalib, sert à construire et manipuler des structures arborescentes d’archives, d’en éditer les métadonnées, de les importer  et exporter sous la forme de SIP, sous la forme de hiérarchie disque ou encore sous forme csv pour les plans de classement.

L’application est constituée d’un fichier exécutable portable (qui ne nécessite pas d’installation) ReSip.exe qui permet de lancer directement par double clic l’application en mode graphique. 

Cet exécutable peut aussi être utilisé en ligne de commande (voir paragraphe Ligne de commande) ou le script ReSip.bat. Dans ce dernier cas un drag and drop d’une arborescence de fichier génère un SIP correspondant.

Cette application présente de manière explicite les contenus XML, et nécessite donc une certaine connaissance du standard SEDA 2.1. Celui-ci est consultable sur le site du ([SIAF](https://francearchives.fr/seda/)).

Pour comprendre l’essentiel, on visera notamment la documentation technique des:
*	manifest du SIP (message ArchiveTransfer)  qui au plus haut niveau définit  les métadonnées globales du versement 
*	DescriptiveMetadata qui contient la structure des archives et des métadonnées
*	ArchiveUnit qui contient toutes les informations de structure et de métadonnées d’une  unité d’archives
*	Management qui contient toutes les informations de gestion d’une unité d’archives
*	Content qui contient toutes les métadonnées descriptives d’une unité d’archives

Sont mis à dispostion :

* **le paquet d'installation sous Windows**

Il s'agit d'un conteneur zip à décompresser en local et dont l'exécution 
nécessite la présence de java 8 64bits sur le poste ou à défaut une machine java 8 64bits dans le répertoire "jre" au niveau de l'exécutable ([jre](http://download.programmevitam.fr/resip/0.9-SNAPSHOT/jre.zip)).

Il est accessible ([ici](http://download.programmevitam.fr/resip/0.9-SNAPSHOT/resip.zip)).

A noter est aussi disponible le fichier .jar utilisable en ligne de commande sous Linux ([jar](http://download.programmevitam.fr/resip/0.9-SNAPSHOT/resip-0.9-SNAPSHOT-shaded.jar)).

* **un manuel utilisateur**

Il décrit les fonctions de Resip ainsi que son utilisation simple et avancée

Il est accessible ([ici](http://download.programmevitam.fr/resip/0.9-SNAPSHOT/Manuel%20Application%20ReSIP%20V0.9-SNAPSHOT-181112.pdf)).

* **un jeux de tests**

il contient des hiérachie disque, SIP, DIP, csv... et toute une série de fichiers d'exemples importables et manipulable avec ReSIP.

Il est accessible ([ici](http://download.programmevitam.fr/resip/0.9-SNAPSHOT/ResipSamples.zip)).

* **le code développé**

Il sera bientôt accessible dans le dépot GitHub avec la bibliothèque sedalib sur laquelle il s'appuie.

