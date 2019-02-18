---
layout: page
title: Ressources
fatherref: ressources
level: page
---

> Cette page présente pour les versions actuelle et passées de la solution logicielle Vitam, l'ensemble des ressources mises à disposition.

Trois versions de productions sont livrées à ce jour. Vous pouvez installer la Release 9 (V2 de la solution logicielle Vitam) et installer ou mettre à jour la Release 7 grâce à la version corrigée, désignée comme la version Long Time Support de la V1 de la solution logicielle. Il est déconseillé d'utiliser les Releases 6 et 8 qui ne seront pas des versions LTS.


## Solution logicielle Vitam - toutes versions publiées

Il s'agit du logiciel Vitam proprement dit, réunissant le back-office et les différentes IHM. Sont mis à dispostion :

* **le code développé**

Il est accessible sur GitHub dans le dépot GitHub [{{ site.github.repo }}]({{ site.github.repo }}).

* **les packages java (.jar) associés, diffusés pour Maven**

Ils sont accessibles en suivant utilisant ce [lien] (http://download.programmevitam.fr/vitam_repository/2.1.1/mvn_repo/)

* **les paquets de déploiement**

Ils permettent d'installer de manière outillée la solution, sous forme RPM pour CentOS 7 et depuis la R3-0.15.1 sous forme deb pour Debian. Ils contiennent aussi des conteneurs de documentation et de jeux de tests.


Liens de téléchargement :

**Version 2.1.1 (Release R9.1)**
  - pour les packages logiciels développés et/ou packagés par Vitam ([rpm](http://download.programmevitam.fr/vitam_repository/2.1.1/rpm/vitam-product/)/[deb](http://download.programmevitam.fr/vitam_repository/2.1.1/deb/vitam-product/)),
  - pour les copies de packages officiels tiers permettant de faciliter une installation hors ligne ([rpm]( http://download.programmevitam.fr/vitam_repository/2.1.1/rpm/vitam-external/)/[deb](http://download.programmevitam.fr/vitam_repository/2.1.1/deb/vitam-external/)).


**Version 1.10.3 (Release 8.3)**
  - pour les packages logiciels développés et/ou packagés par Vitam ([rpm](http://download.programmevitam.fr/vitam_repository/1.10.3/rpm/vitam-product/)/[deb](http://download.programmevitam.fr/vitam_repository/1.10.3/deb/vitam-product/)),
  - pour les copies de packages officiels tiers permettant de faciliter une installation hors ligne ([rpm]( http://download.programmevitam.fr/vitam_repository/1.10.3/rpm/vitam-external/)/[deb](http://download.programmevitam.fr/vitam_repository/1.10.3/deb/vitam-external/)).

**Version 1.4.9 (Release 7.9)**
  - pour les packages logiciels développés et/ou packagés par Vitam ([rpm](http://download.programmevitam.fr/vitam_repository/1.4.9/rpm/vitam-product/)/[deb](http://download.programmevitam.fr/vitam_repository/1.4.9/deb/vitam-product/)),
  - pour les copies de packages officiels tiers permettant de faciliter une installation hors ligne ([rpm](http://download.programmevitam.fr/vitam_repository/1.4.9/rpm/vitam-external/)/[deb](http://download.programmevitam.fr/vitam_repository/1.4.9/deb/vitam-product/)).


**Version 1.0.13 (Release 6.13)**
  - pour les packages logiciels développés et/ou packagés par Vitam ([rpm](http://download.programmevitam.fr/vitam_repository/1.0.13/rpm/vitam-product/)/[deb](http://download.programmevitam.fr/vitam_repository/1.0.13/deb/vitam-product/)),
  - pour les copies de packages officiels tiers permettant de faciliter une installation hors ligne ([rpm](http://download.programmevitam.fr/vitam_repository/1.0.13/rpm/vitam-external/)/[deb](http://download.programmevitam.fr/vitam_repository/1.0.13/rpm/vitam-external/)).


A noter, ces liens sont utilisables par les outils de gestion de paquets (yum/apt).

* **une machine virtuelle**

Elle contient une installation complète de Vitam qui permet une découverte fonctionnelle.
La solution logicielle étant prévue distribuée pour les grandes volumétries, l'ensemble des modules sont taillés au plus juste pour être dans cette seule machine virtuelle qui nécessite 4 vCPU et 8GO de mémoire pour fonctionner correctement.

La VM de la version 2.1.1 (Release 9) peut être téléchargée en suivant ce [lien](http://download.programmevitam.fr/vitam_repository/2.1.1/VM/demo_vitam_2.1.1.ova).
L'empreinte sha256 de la VM est disponible à cette url: (http://download.programmevitam.fr/vitam_repository/2.1.1/VM/demo_vitam_2.1.1.sha256).

La VM de la version 1.10.3. (Release 8) peut être téléchargée en suivant ce [lien](http://download.programmevitam.fr/vitam_repository/1.10.3/VM/demo_vitam_1.10.3.ova).
L'empreinte sha256 de la VM est disponible à cette url: (http://download.programmevitam.fr/vitam_repository/1.10.3/VM/demo_vitam_1.10.3.sha256).

La VM de la version 1.4.5. (Release 7) peut être téléchargée en suivant ce [lien](http://download.programmevitam.fr/vitam_repository/1.4.9/VM/demo_vitam_1.4.9.ova).
L'empreinte sha256 de la VM est disponible à cette url: (http://download.programmevitam.fr/vitam_repository/1.4.9/VM/demo_vitam_1.4.9.sha256).

La VM de la version 1.0.13. (Release 6 corrigée) peut être téléchargée en suivant ce [lien](http://download.programmevitam.fr/vitam_repository/1.0.13/VM/demo_vitam_1.0.13.ova).
L'empreinte sha256 de la VM est disponible à cette url: (http://download.programmevitam.fr/vitam_repository/1.0.13/VM/demo_vitam_1.0.13.ova.sha256).


* **la documentation fonctionnelle et technique**

Elle est accessible, en partie  sur GitHub pour les documents en forme brute RST, intégralement dans les packages sur Bintray, mais aussi directement sous forme PDF et/ou HTML sur la page [Documentation](/pages/documentation).

* **les Release Notes**

<https://github.com/ProgrammeVitam/vitam/releases>


## Des exemples d'usage

Vous pouvez utiliser pour tester le logiciel deux jeux de fichiers référentiels et paquets SIP:

* **Fichiers d'exemples du kit de prise en main**
([zip](http://download.programmevitam.fr/vitam_repository/2.1.1/tests/Jeu_de_tests_Guide_de_prise_en_main_R9.zip)) Ces éléments vous permettent d'effectuer les premiers paramétrages et une première entrée d'archives dans la solution logicielle Vitam en lien avec le guide de prise en main ([pdf](/ressources/DocCourante/autres/fonctionnel/VITAM_Guide_de_prise_en_main.pdf))

* **Fichiers de test du Cahier de tests métier**
([zip](http://download.programmevitam.fr/vitam_repository/2.1.1/tests/Jeux_de_tests_fonctionnels_RELEASE9_SEDA2.1.zip)) Ces éléments vous permettent de jouer les tests du cahier de test ([pdf](/ressources/DocCourante/autres/fonctionnel/VITAM_Cahier_de_tests_metiers.pdf))


## Outils de préservation Vitam

Les "Griffons" de préservation numérique sont des outils mobilisables pour mettre en œuvre des actions de préservation, pour l'instant analyse/validation de formats, conversion de formats.

Sont mis à dispostion :

* **les exécutables**

* URL de configuration des dépôts de binaires CentOS/RHEL : ([rpm](http://download.programmevitam.fr/griffins/1.0.0/rpm/))
* URL de configuration des repository Debian : ([deb](http://download.programmevitam.fr/griffins/1.0.0/deb/))

* **le code développé**

Il est accessible dans le dépot GitHub [Griffons](https://github.com/ProgrammeVitam/vitam-griffins/tree/1.0.0)


## Outils complémentaires Vitam - toutes versions publiées

Il s'agit des outils utilisés pour faciliter le test ou le développement.

Pour le moment, il s'agit des **Sedatools**,
Bibliothèque Java et outils IHM (interface hommes/machines) de manipulation des paquets SEDA, proposés pour tests
Ils permettent de générer automatiquement à partir d’une simple arborescence de fichiers un SIP (paquet d’information à archiver) conforme aux recommandations Vitam (cf "Spécifications des SIP" selon la version dans la page [Documentation](/pages/documentation)).

Cette publication vise à recueillir les déclarations d’intérêt des utilisateurs suite à leurs tests afin d'évaluer l'intérêt d'intégrer cet outil à la solution logicielle Vitam. Les retours sont possibles à l'adresse contact@programmevitam.fr

Pour plus d'information, consultez la page [ReSIP](/pages/ressources/resip).

Sont mis à dispostion :

* **les exécutables**

Ils sont accessibles dans la page [ReSIP](/pages/ressources/resip).

Il s'agit d'un conteneur zip à décompresser en local et dont l'exécution nécessite la présence de java 8 sur le poste ou à défaut une machine java 8 dans le répertoire "jre" au niveau de l'exécutable.

* **La documentation associée**

Elle est accessible dans la page [Documentation](/pages/documentation).

La documentation **ReSIP** décrit les fonctions de l'outil ReSIP et peut être consultée en suivant ce [lien] (http://ressources/DocCourante/autres/fonctionnel/VITAM_manuel_ReSIP.pdf)

La documentation **Spécification des SIP** - recommandations sur la construction des paquets
à archiver peut être consultée en suivant ce [lien] ([pdf](/ressources/DocCourante/autres/fonctionnel/VITAM_Structuration_des_SIP.pdf))

* **le code développé**

Il est accessible dans le dépot GitHub [SedaTools](https://github.com/ProgrammeVitam/sedatools/tree/1.0.0)


## Présentation de la Première version de production de la solution logicielle Vitam

Une présentation de la Première version de production de la solution logicielle Vitam a eu lieu aux Archives nationales le 11 avril 2018, réunissant environ 250 personnes. Le support de présentation est consultable ici : ([pdf](/ressources/Doc1.0.0/autres/fonctionnel/20180411_présentation_vitam_V5.0_publication.pdf))


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
