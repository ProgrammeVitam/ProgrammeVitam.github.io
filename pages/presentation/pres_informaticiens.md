---
layout: page
title: Focus informaticien
fatherref: presentation
---
>Le rôle des informaticiens des ministères et des collectivités susceptibles 
d’utiliser Vitam est fondamental. Si l'on veut éviter "l'alzheimer" numérique, 
il leur faut, dès maintenant, penser et réaliser l'intégration de
de la fonction archivage dans leur SI.

Alors que les teraoctets s’amoncellent dans les centres de productions, la 
question de l’archivage numérique de ce qui a de la valeur pour les usagers et 
pour les autorités administratives devient de plus en plus urgente à traiter.

## Penser le moyen et le long terme

Il ne s’agit plus simplement de conserver des fichiers, mais bien de s’assurer que 
l’information pertinente pourra être retrouvée et utilisée des années, voire des
 décennies après. Il faut, non seulement, sélectionner l’information mais aussi la
 conserver de manière accessible dans le temps, malgré les migrations de baies, 
 de supports et de formats.

Face à la croissance exponentielle du numérique, il faut, grâce à un saut 
technologique, se mettre en capacité de traiter les milliards d’objets de toutes
 natures qui devront être conservés. Le passage aux technologies du Big data, 
 associées à une approche sémantique sur une base cloud, est nécessaire pour 
 relever le défi que représentent les 3 V : Volumétrie des données, Variabilité 
 des métadonnées et Vélocité d’accès.

## Une solution ouverte

La solution logicielle développée par le programme Vitam permettra la prise en 
charge, la conservation, la pérennisation et la consultation sécurisées de très 
gros volumes d’archives numériques. Elle assurera la gestion complète du cycle 
de vie des archives et donc la garantie de leur valeur probante. Elle pourra 
être utilisée pour tout type d'archive, y compris pour des documents classifiés 
de défense.

Cette solution, essentiellement développée en Java, est diffusée en logiciel libre (code sous licence 
[CeCILL V2.1](http://www.cecill.info/licences/Licence_CeCILL_V2-fr.html), 
compatible GNU GPL, et documentation sous 
[CC-BY-SA 3.0 FR](https://creativecommons.org/licenses/by-sa/3.0/fr/)) 
pour faciliter sa réutilisation, 
son évolution, son adaptation à des contextes particuliers si nécessaire, sa 
maintenance et donc globalement sa pérennité.

L’obligation de mettre en œuvre une solution d’archivage numérique dans les 
contextes très différents des trois ministères porteurs, tant en termes de 
pratiques archivistiques, qu’en termes de production informatique, a orienté 
notre choix vers la réalisation d’un back-office. L’objectif est de prendre en 
compte dans la solution logicielle Vitam, le maximum de fonctions mutualisables 
et technologiquement complexes, d’autant plus quand elles s’appliquent à de 
très grands nombres d’objets, et de laisser chaque entité porter ses propres 
spécificités de processus. Cette vision permet ainsi la réutilisation plus 
large, tout en assurant la réalisation d’un outil générique intégrable selon les 
besoins d’acteurs variés dans leur système d’information.

## Une logique de back-office

Positionnée comme une brique d’infrastructure, elle prendra en charge toutes les 
opérations nécessaires pour assurer la pérennisation des documents numériques 
versés et pour garantir le maintien de leur valeur probante.

Pour permettre un usage mutualisé entre plusieurs organisations, elle sera 
multi-tenante avec un cloisonnement systématique de toutes les archives et 
des informations du système par organisation utilisatrice.

Elle permettra la prise en charge de tous les documents numériques (bureautique,
 audio, vidéo, image, plan, bases de données, etc.) que l’administration 
 souhaite conserver à des fins d’archivage courant[^1], intermédiaire[^2] ou 
 définitif[^3]. 

Elle assurera, pour de très gros volumes de documents numériques, des 
fonctionnalités :

* de gestion des métadonnées et d'indexation,
* de gestion des infrastructures de stockage,
* de transformation des fichiers,
* de recherche et de consultation,
* et de gestion sécurisée de l’ensemble du cycle vie des archives.

Elle offrira des interfaces applicatives (API) permettant principalement :

* le versement de documents,
* la recherche sur les méta-données et les journaux,
* l’accès aux documents,

Pour des usages plus spécifiques, il y aura aussi des interfaces de gestion et 
d’administration.

Enfin, toujours dans un esprit de facilité de réutilisation, la solution 
logicielle Vitam est aussi neutre technologiquement que possible :

* elle n'impose pas d'infrastructures particulières, comme des baies de 
stockages adaptées ou des matériels spécifiques,
* elle s'installe sur un environnement serveur x86 physique, virtualisé ou en 
Cloud au choix de ceux qui l'implémentent, avec plus ou moins d'automatisation 
selon le degré de virtualisation,
* elle est développée pour s'exécuter sur un environnement Linux et distribuée 
pour un déploiement CentOS (à venir en V1 aussi Debian),
* elle amène une solution de stockage déployable sur toute infrastructure 
serveurs en lien avec une capacité de stockage disque ou, quand ils existent, peut
 utiliser des moyens existants de stockage Objet (Swift)

## L'architecture... en bref
 
Une plate-forme d’archivage utilisant la solution logicielle Vitam comprend : 

* des applications de front office, permettant à des utilisateurs d’accéder aux 
objets archivés à des fins de recherche, consultation, gestion du cycle de vie 
ou préservation :
	* le frontal archivistique (IHM Système d'Information Archivistique) ;
	* des applications tierces, notamment les applications métier des services producteurs ;
* le back-office appuyé sur des offres de stockage, dont certaines sont potentiellement tierces, qui assurent la conservation binaire des objets archivés ;
* des applications tierces versant et consultant des objets dans la plate-forme.

![Architecture Générale Vitam](/public/images/ArchitectureGenerale.jpg)

L’ensemble fourni par Vitam comprend le code, sous licence libre, nécessaire pour mettre en œuvre :

* le coeur Vitam - 
Il est le back-office proprement dit. Il n’a que des API (de type REST/JSON), y compris pour son administration. Il se doit d’être intégrable complètement, et que toute fonction puisse être mobilisée via les API par un frontal non Vitam.
* les IHM d’administration, « standard » et de démonstration
* des offres de stockage

Il est possible d’utiliser des offres externes de stockage objet, ou d’en mettre en œuvre avec le logiciel Vitam.

## En collaboration avec les porteurs et partenaires

Pour que cette solution soit utile au plus grand nombre, sa conception et 
ses tests seront faits en collaboration avec tous les partenaires du Programme, 
et certains points clés seront ouverts à discussions au-delà, comme les API alpha
 publiées en juillet 2016.
 
Le calage régulier est facilité par le mode de développement en Agile, en Scrum 
de Scrum, avec, selon les moments, de 2 à 4 équipes. Le rythme est de 3 semaines 
pour les sprints, de 3 à 4 mois soit 5 sprints par version intermédiaire 
et annuel pour les versions majeures. Les ministères porteurs et partenaires peuvent se 
caler sur les livrables des sprints pour accompagner leur propre développement 
quand il est Agile.
 
Ces livraisons régulières permettent aussi les tests des ministères porteurs et partenaires, 
ce qui contribue à la qualité des livrables... 

<hr/>

[^1]: Avant la clôture d’une affaire ou d’un dossier, par exemple, le dossier RH d’un agent travaillant toujours dans le service.

[^2]: Avant l’expiration de la durée d’utilité administrative (DUA), les données peuvent faire l’objet d’un contrôle, recours contentieux ou de la demande du public à des fins administratives.

[^3]: A l’issue de la DUA, les données n’ont plus d’utilité administrative mais sont conservées pour des raisons historiques, statistiques mais aussi juridiques. Les données ayant un effet de droit sans limite dans le temps, par exemple l’état-civil, sont aussi archivées à titre définitif. A ce stade, elles doivent pouvoir être communiquées au public, en conformité avec les délais légaux de communicabilité.