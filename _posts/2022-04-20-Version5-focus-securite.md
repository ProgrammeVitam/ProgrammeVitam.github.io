---
layout: post
title: Version 5 de Vitam, focus sur la sécurité
---

    La version 5 de la solution logicielle Vitam a été publiée il y a quelques jours. Le Programme Vitam souhaite en profiter pour faire quelques focus.

![Logos](/public/images/v5-une.png)

Le premier focus portera sur les aspects de sécurité :

- La montée de version ES corrige définitivement la vulnérabilité liée à la faille log4shell. Il n’est plus utile d’appliquer un patch correctif.

- Un travail d'analyse et d'optimisation a été réalisé sur la mise en œuvre de l'outil de sécurité Checkmarx. L'objectif étant de rendre les plus
pertinentes possibles les recommandations de sécurité émises par l'outil, en évitant les "faux-positifs" et autres points non utilisables. Les
analyses étant plus précises, la correction des éventuelles failles est plus aisée et rapide, et la qualité de la solution logicielle s'en retrouve
renforcée.

- Le service de recherche « scroll » permettant de retourner plus de 10 000 UA doit être d’usage limité au risque d’écrouler les performances. Il
est réservé à un usage ponctuel pour simplifier la synchronisation de métadonnées vers des applications tierces et non pour un usage illimité.

 
[En image](/public/images/V5_securite_focus.PNG)  

  
  
  
[En savoir plus sur la V5](http://www.programmevitam.fr/2022/04/13/Version5/)  
[Accéder au code](http://www.programmevitam.fr/pages/ressources/)  
[Accéder à la documentation de la V5](http://www.programmevitam.fr/pages/documentation/)