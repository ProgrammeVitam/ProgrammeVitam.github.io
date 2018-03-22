---
layout: page
title: FAQ
fatherref: FAQ
level: page
---

## Quelle mobilisation, quels moyens humains ?

Le programme est fondé sur :

* un budget de l'ordre de 15 millions d’euro pour le développement de la solution logicielle,
* pour les 5 ans à venir, une équipe interministérielle de 14 personnes mises 
à disposition à temps plein par leur Administration (ministères de la Défense, de 
la Culture, des Affaires étrangères et du Développement international),
* des équipes de développement et d’intégration, plus de 30 personnes, constituées 
par les prestataires titulaires des marchés publics Vitam (principalement Smile, HIT Part, Linagora, Thalès, Goood),
* un responsable PMO (Project management office) KPMG,
* une plate-forme de développements pouvant atteindre 400 machines virtuelles (VM) et plus de 100To, hébergée par le ministère de l'Agriculture.

## Quel est le calendrier du projet de développement ?

Les développements de la solution logicielle ont commencé le 13 avril 2016.
Les grands jalons du planning sont les suivants :

* Pour faciliter l’appropriation par les développeurs et l’ensemble des acteurs concernés par
l’intégration applicative de la solution logicielle Vitam, **les 
API principales** ont été publiées le **18 juillet   2016**. 
Une documentation, des fichiers de descriptions et des interfaces "bouchonnées" 
sont mises à disposition à l’adresse api.programmevitam.fr,
* Pour permettre l’appropriation par les équipes de production en avance de phase, une
**version** dite "**Bêta**" de la solution logicielle Vitam a été mise à disposition des ministères
porteurs et des partenaires du programme le **29 novembre 2016**,
* La première version utilisable en production est la **V1** publiée le **22 mars 2018**,
* Ensuite la **V2** sera publiée **fin  2018**,
* Et la **V3**, version finale de la phase projet, sera publiée **fin 2019**.

## Quelle est la stratégie en cours par rapport aux autres institutions et projets  ?

Des contacts ont été pris avec différents organismes INA, INPI, BNF, équipe Atlas… 
La principale différence entre ces projets, est que Vitam gérera tous les aspects du cycle de vie des archives pour un très grand nombre 
d’objets, là ou d’autres gèrent plutôt des objets très volumineux, mais moins nombreux. Des collaborations sont 
envisageables sur certains aspects, tels que la pérennisation par exemple.

## Comment Vitam assurera la conservation dans le temps ? Comment assurer la pérennisation ? Comment l’envisager techniquement ?

On ne vise pas une virtualisation ou une émulation, mais des conversions de formats 
rendues possibles par un référentiel des formats. Le contrat de pérennisation des données 
définira les règles de conservation. Il sera possible pour chaque document de conserver la 
version d’origine, et certaines issues de conversions. Cependant le niveau de service 
(pérennisation mais aussi accès…) devra être défini dans le contrat de versement. 
En effet, on établira une relation contractualisée entre le SAE et l’application métier.

La pérennisation sera donc assurée en 3 phases :

* identification des formats : règles et préconisation de contrôle sur la base d'un référentiel,
* règles et préconisation de conservation,
* règles et outils de conversions.

La gestion des formats ne sera accessible que pour les administrateurs des plate-formes 
d’archivage. De même qu’actuellement, seules certaines personnes sont chargées de gérer 
la conservation et la restauration des documents papier.

## Comment préparer les archives à l’entrée ?

Le "pré-versement" (préparation des archives pour les rendre aptes à l'archivage) est une question à l’étude : des travaux intellectuels et des discussions 
sont lancés sur ce thème important, des développements pourraient éventuellement être réalisés 
pour assurer ces fonctionnalités (dans ou hors de Vitam).
La question du versement des données non structurées, bureautiques, par exemple, est à l’étude. 
Les vracs constituent les ensembles les plus difficiles à gérer (y compris les documents issus de GED).
Un outil supplémentaire est nécessaire pour préparer les archives, cela est pris en compte par le 
projet AD-Essor au sein du programme (outil Octave).

## Quel sera le dimensionnement et l’architecture des plate-formes dans les ministères ?

La solution logicielle utilisera les technologies du cloud pour assurer l’élasticité. 
Les infrastructures ministérielles comporteront des dizaines de machines virtuelles répliquées sur 
3 stockages (2 systèmes rapides et un plus lent sur bandes), visant des volumes en centaines de teraoctets voire 
de pétaoctets, ou encore des centaines de millions d'objets archivés voire de milliards d'objets.
Le Programme a été lancé dans un contexte de croissance exponentielle des archives 
numériques. Par exemple, le volume collecté par les Archives nationales, depuis les années 80 jusqu’en 2011, 
est équivalent à la seule collecte de 2014.


## Quels sont les services mis à disposition afin de faciliter exploitabilité du logiciel au sein de plate-formes ?

La méthode de développement retenu différencie le développement proprement dit de l’intégration. 
L'objectif est de faciliter au maximum la réutilisation de la solution logicielle, en particulier 
au sein de l’État. Le produit final livré par l’intégrateur devra donc être bien packagé et 
bien documenté, pour être facilement réutilisable.
Des conventions de partenariats seront mises en place pour faciliter la réutilisation et 
apporter plus d’accompagnement aux institutions intéressées par une implémentation durant la phase de développement.
