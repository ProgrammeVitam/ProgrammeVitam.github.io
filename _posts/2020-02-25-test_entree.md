---
layout: post
title: Retour sur un test de versement dans Vitam
---
> A la demande d'un service d'archives départementales, l'équipe du programme Vitam a effectué un test de versement dans la solution logicielle Vitam de paquets d'archives (ou SIP) qui lui avaient été fournis.

![Logos](/public/images/entrees_test_202002.png)

Ce test a porté essentiellement sur un paquet d’archives contenant 160 000 archives et faisant 5 Go. La principale difficulté a été de transformer ce paquet fourni et initialement décrit en SEDA 1.0 en paquet conforme au formalisme du SEDA 2.1, qui est la version supportée par la solution logicielle Vitam. Ces tests ont démontré la capacité de Vitam à traiter correctement et rapidement les archives même pour une volumétrie importante.Ce test a porté sur un paquet d’archives de 160 000 archives et 5 Go. 

Pour rappel, Vitam ne supporte pas officiellement le versement de paquet d’archives (SIP) de plus de 100 000 archives, sans que cela ne soit une limite technique absolue : pour preuve le SIP a bien été traité avec ses 160 000 archives. 
Ce SIP a été traité en 3h13 minutes, soit une vitesse moyenne de 50 000 archives par heures.

Devant ce résultat, un test complémentaire a été effectué, en découpant le paquet d’archives fourni (SIP) en 16 SIP de 10 000 archives chacun (reprenant donc les mêmes 160 000 archives en tout). Ces 16 SIP, pour un total de 160 000 archives, ont été injectés simultanément dans la solution logicielle Vitam. Ils ont tous été traités en moins de 18 minutes, soit 10 fois plus rapidement qu'en faisant un SIP unique (à une vitesse moyenne globale de 500 000 archives par heure).

Les résultats de ces tests sur les données fournies par ce service d'archives départementales sont en tout point conformes aux prévisions de l'équipe du programme Vitam, issues des résultats obtenus lors des précédents tests effectués avec des données fictives.