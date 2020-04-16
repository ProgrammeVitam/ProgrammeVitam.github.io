---
layout: page
title: Sedalib
fatherref: ressources
---

> Cette page présente la bibliothèque sedalib (version courante 1.1 compilée 25/02/2019).

## sedalib

La bibliothèque sedalib permet de créer et de manipuler des structures du standard SEDA 2.1. Celui-ci est consultable sur le site du [SIAF](https://francearchives.fr/seda/).

Pour comprendre l’essentiel, on visera notamment la documentation technique des:
*	**manifest du SIP (message ArchiveTransfer)**  qui au plus haut niveau définit  les métadonnées globales du versement 
*	**DescriptiveMetadata** qui contient la structure des archives et des métadonnées
*	**ArchiveUnit** qui contient toutes les informations de structure et de métadonnées d’une  unité d’archives
*	**Management** qui contient toutes les informations de gestion d’une unité d’archives
*	**Content** qui contient toutes les métadonnées descriptives d’une unité d’archives

Elle permet de :
* Créer des SIP
* Ouvrir des SIP ou DIP
* Manipuler les métadonnées à bas niveau pour les ajouter, les enlever et les modifier
* Exporter sous forme SIP ou hiérarchie disque

Elle contient aussi un **constructeur de haut-niveau** (classe **SIPBuilder**) qui permet de construire des SIP avec des métadonnées riches en quelques appels.

Sont mis à dispostion :


* **le fichier jar**

Le .jar est [ici](http://download.programmevitam.fr/resip/1.1/sedalib-1.1.0.jar).


* **la documentation**

La JavaDoc est [ici](http://download.programmevitam.fr/resip/1.1/javadoc-sedalib1.1). 

Par ailleurs, dans le code vous trouverez des exemples d'utilisation, notamment de la classe SIPBuilder, dans 
[sedalib-samples](https://github.com/ProgrammeVitam/sedatools/tree/master/sedalib-samples/src/main/java/fr/gouv/vitam/tools/sedalibsamples).


* **le code développé**

Il est accessible dans le dépot GitHub, au sein du depot sedatools qui contient aussi l'application [ReSip](/pages/ressources/resip) qui utilise massivement sedalib : [SedaTools](https://github.com/ProgrammeVitam/sedatools/tree/master/sedalib)
