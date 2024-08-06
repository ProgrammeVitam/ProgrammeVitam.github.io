---
layout: page
title: Autres ressources
fatherref: ressources
level: page
---

> Cette rubrique présente l'ensemble des ressources connexes mises à disposition.

* [Outils de préservation Vitam](#preservation)
* [Outils complémentaires Vitam - RESIP, sedalib, mailextractlib...](#resip)

<a name="preservation"></a>
## Outils de préservation Vitam

Les "Griffons" de préservation numérique sont des outils mobilisables pour mettre en œuvre des actions de préservation, pour l'instant analyse/validation de formats, conversion de formats.

Sont mis à dispostion :

* **les exécutables**

* URL de configuration des dépôts de binaires CentOS/RHEL : ([rpm](http://download.programmevitam.fr/vitam_griffins/1.16.0/rpm/))
* URL de configuration des repository Debian : ([deb](http://download.programmevitam.fr/vitam_griffins/1.16.0/deb/))

* **le code développé**

Il est accessible dans le dépot GitHub [Griffons](https://github.com/ProgrammeVitam/vitam-griffins/tree/1.16.0).

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