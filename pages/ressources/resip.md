---
layout: page
title: Resip
fatherref: ressources
level: page
---

> Cette page présente le generateur ReSIP. 

## ReSIP

L’application ReSIP, construite au dessus de la bibliothèque sedalib, sert à construire et manipuler des structures arborescentes d’archives, d’en éditer les métadonnées, de les importer  et exporter sous la forme de SIP, sous la forme de hiérarchie disque ou encore sous forme csv pour les plans de classement.

Cette application présente de manière explicite les contenus XML, et nécessite donc une certaine connaissance du standard SEDA 2.1. Celui-ci est consultable sur le site du SIAF https://francearchives.fr/seda/. Pour comprendre l’essentiel, on visera notamment la documentation technique des:
•	manifest du SIP (message ArchiveTransfer)  qui au plus haut niveau définit  les métadonnées globales du versement 
•	DescriptiveMetadata qui contient la structure des archives et des métadonnées
•	ArchiveUnit qui contient toutes les informations de structure et de métadonnées d’une  unité d’archives
•	Management qui contient toutes les informations de gestion d’une unité d’archives
•	Content qui contient toutes les métadonnées descriptives d’une unité d’archives

L’application est constituée d’un fichier exécutable portable (qui ne nécessite pas d’installation) ReSip.exe qui permet de lancer directement par double clic l’application en mode graphique. 
Cet exécutable peut aussi être utilisé en ligne de commande (voir paragraphe Ligne de commande) ou le script ReSip.bat. Dans ce dernier cas un drag and drop d’une arborescence de fichier génère un SIP correspondant.

Sont mis à dispostion :

* **le paquet d'installation sous Windows**

Il s'agit d'un conteneur zip à décompresser en local et dont l'exécution 
nécessite la présence de java 8 64bits sur le poste ou à défaut une machine java 8 64bits dans le répertoire "jre" au niveau de l'exécutable ([jre](/ressources/resip/jre.zip)).

Il est accessible ([ici](/ressources/resip/resip.zip)).

A noter est aussi disponible le fichier .jar utilisable en ligne de commande sous Linux ([jar](/ressources/resip/resip-0.9-SNAPSHOT-shaded.jar)).

* **un manuel utilisateur**

Il décrit les fonctions de Resip ainsi que son utilisation simple et avancée
(cf "Présentation du générateur SEDA" selon la version dans la page [Documentation](/pages/documentation)).

* **le code développé**

Il est accessible dans le dépot GitHub [{{ site.github.repoext }}]({{ site.github.repoext }}). A noter que les packages java (.jar) sont sur le même point Maven que la solution logicielle.


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