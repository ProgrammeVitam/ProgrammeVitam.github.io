---
layout: page
title: Sedalib
fatherref: ressources
---

> Cette page présente la bibliothèque sedalib (version courante 2.5.0 compilée en mars 2021).

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

Est mis à dispostion le code développé.
Il est accessible dans le dépot GitHub, au sein du depot sedatools qui contient aussi l'application [ReSip](/pages/ressources/resip) qui utilise massivement sedalib : [SedaTools](https://github.com/ProgrammeVitam/sedatools).
