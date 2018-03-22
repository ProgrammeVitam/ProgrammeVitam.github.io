---
layout: page
title: Ressources
fatherref: ressources
level: page
---

> Cette page présente pour les versions actuelle et passées de la solution logicielle Vitam, l'ensemble des ressources mises à disposition. 

## Solution logicielle Vitam - toutes versions publiées

Il s'agit du logiciel Vitam proprement dit, réunissant le back-office et les différentes IHM. Sont mis à dispostion :

* **le code développé**

Il est accessible sur GitHub dans le dépot GitHub [{{ site.github.repo }}]({{ site.github.repo }}).

* **les packages java (.jar) associés, diffusés pour Maven**

Ils sont accessibles sur BinTray [{{ site.bintray.repomaven }}]({{ site.bintray.repomaven }}).

* **les paquets de déploiement** 

Ils permettent d'installer de manière outillée la solution, sous forme RPM 
pour CentOS 7 et depuis la R3-0.15.1 sous forme deb pour Debian. Ils contiennent aussi des conteneurs de documentation et de jeux de tests. 

Liens de téléchargement:
  - pour les packages logiciels développés et/ou packagés par Vitam ([rpm](http://download.programmevitam/repo_vitam_1.0.0/rpm/vitam-product/)/[deb](http://download.programmevitam/repo_vitam_1.0.0/deb/vitam-product/)),
  - pour les copies de packages officiels tiers permettant de faciliter une installation hors ligne ([rpm](http://download.programmevitam/repo_vitam_1.0.0/rpm/vitam-external/)/[deb](http://download.programmevitam/repo_vitam_1.0.0/deb/vitam-external/)).

* **une machine virtuelle**

Elle contient une installation complète de Vitam qui permet une découverte fonctionnelle. 
La solution logicielle étant prévue distribuée pour les grandes volumétries, l'ensemble des modules sont taillés au plus juste pour être dans cette seule machine virtuelle qui nécessite 4 vCPU et 8GO de mémoire pour fonctionner correctement. 

Sa publication interviendra dans quelques jours.

* **la documentation fonctionnelle et technique**

Elle est accessible, en partie  sur GitHub pour les documents en forme brute RST, intégralement dans les packages sur Bintray, mais aussi directement sous forme PDF et/ou HTML sur la page [Documentation](/pages/documentation).

* **les Release Notes**

<https://github.com/ProgrammeVitam/vitam/releases>


## Des exemples d'usage

Vous pouvez utiliser pour tester le logiciel deux jeux de fichiers référentiels et paquets SIP:

* **Fichiers d'exemples du kit de prise en main** ([zip](http://download.programmevitam.fr/repo_vitam_1.0.0/tests/20180320-Jeu_de_tests_Kit_de_prise_en_main.zip)) Ces éléments vous permettent d'effectuer les premiers paramétrages et une première entrée d'archives dans la solution logicielle Vitam en lien avec le guide de prise en main ([pdf](/ressources/DocCourante/autres/fonctionnel/20180320_Vitam_Kit_de_prise_en_main_V3.0.pdf))

* **Fichiers de test du cahier de tests** ([zip](http://download.programmevitam.fr/repo_vitam_1.0.0/tests/20180320-Jeux_de_tests_fonctionnels_RELEASE6.zip)) Ces éléments vous permettent de jouer les tests du cahier de test ([pdf](/ressources/DocCourante/autres/fonctionnel/20180320_Vitam_Cahier_de_tests_metiers.pdf))


## Outils complémentaires Vitam - toutes versions publiées

Il s'agit des outils utilisés pour faciliter le test ou le développement. 

Pour le moment, il s'agit du **Générateur Seda**, un outil de développement permettant
de générer automatiquement à partir d’une simple arborescence de fichiers un SIP
(paquet d’information à archiver) conforme aux recommandations Vitam (cf "Spécifications des SIP" selon la version dans la page [Documentation](/pages/documentation)).

Sont mis à dispostion :

* **le paquet d'installation sous Linux et Windows**

Il s'agit d'un conteneur zip à décompresser en local et dont l'exécution 
nécessite seulement la présence de java 8 sur le poste.
Il est accessible sur BinTray [{{ site.bintray.repogenseda }}]({{ site.bintray.repogenseda }}).

* **une présentation du Générateur Seda**

Elle décrit les fonctions du Générateur ainsi que son utilisation simple et avancée
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