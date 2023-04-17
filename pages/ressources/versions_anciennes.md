---
layout: page
title: Anciennes versions
fatherref: ressources
---

> Cette page présente pour les versions actuelle et passées de la solution logicielle Vitam, l'ensemble des ressources mises à disposition.

Actuellement, 2 versions de la solution logicielle Vitam sont livrées chaque année :
- au printemps, une version majeure. Exemple la V5 en avril 2022.
- à l'automne, une version appelée release candidate (RC). Exemple la V5.RC en novembre 2021.
Les 2 versions sont homologuées.


* [Solution logicielle Vitam - toutes versions publiées](#touteversion)
* [Des exemples d'usage](#exemples)
* [Présentation de la deuxième version de production de la solution logicielle Vitam](#journee2)
* [Présentation de la Première version de production de la solution logicielle Vitam](#journee1)

<a name="touteversion"></a>
## Solution logicielle Vitam - toutes versions publiées

Il s'agit du logiciel Vitam proprement dit, réunissant le back-office et le front-office Vitam UI. A noter que l'IHM dite de démonstration est encore utilisée en complément de Vitam UI. Sont mis à dispostion :

* **le code développé**

Il est accessible sur GitHub dans le dépot GitHub [{{ site.github.repo }}]({{ site.github.repo }}).

* **les packages java (.jar) associés, diffusés pour Maven**

Ils sont accessibles en suivant utilisant ce [lien](https://download.programmevitam.fr/vitam_repository/5.0/mvn_repo/)

* **les paquets de déploiement**

Ils permettent d'installer de manière outillée la solution, sous forme RPM pour CentOS 7 et sous forme deb pour Debian. Ils contiennent aussi des conteneurs de documentation et de jeux de tests.


### Pour la 4.0.7 de la R16 (mise à jour en mars 2023)

Releases note [back](/ressources/RefCourant/VitamBO_release-notes.4.0.4.pdf) et [front](/ressources/RefCourant/VitamUI_release-notes.4.0.4.pdf)

#### Vitam back-office
* Publication [GitHub Vitam](https://github.com/ProgrammeVitam/vitam/tree/4.0.7)  

* URL de configuration du [repository Maven](http://download.programmevitam.fr/vitam_repository/4.0.7/mvn_repo/)  
* URL de configuration des dépôts de binaires CentOS/RHEL :  
	* [Vitam-product](http://download.programmevitam.fr/vitam_repository/4.0.7/rpm/vitam-product)  
	* [Vitam-external](http://download.programmevitam.fr/vitam_repository/4.0.7/rpm/vitam-external)  
* URL de configuration des dépôts de binaires Debian :  
	- [Vitam-product](http://download.programmevitam.fr/vitam_repository/4.0.7/deb/vitam-product)  
	- [Vitam-external](http://download.programmevitam.fr/vitam_repository/4.0.7/deb/vitam-external)  
   

#### Vitam UI
* Publication [GitHub Vitam UI](https://github.com/ProgrammeVitam/vitam-ui/tree/4.0.5)  
* URL de configuration du [repository Maven](https://download.programmevitam.fr/vitamui/4.0.5/mvn_repo/)  
* URL de configuration des [dépôts de binaires CentOS/RHEL](https://download.programmevitam.fr/vitamui/4.0.5/rpm/)  



### Pour la 3.0.16 de la R13 (mise à jour en juillet 2021)
* [Publication GitHub Vitam](https://github.com/ProgrammeVitam/vitam/tree/3.0.16)  
* URL de configuration du [repository Maven](https://download.programmevitam.fr/vitam_repository/3.0.16/mvn_repo/)  
* URL de configuration des dépôts de binaires CentOS/RHEL :  
	- [Vitam-product](https://download.programmevitam.fr/vitam_repository/3.0.16/rpm/vitam-product/)  
	- [Vitam-external](https://download.programmevitam.fr/vitam_repository/3.0.16/rpm/vitam-external/)  
* URL de configuration des dépôts de binaires Debian :  
	- [Vitam-product](https://download.programmevitam.fr/vitam_repository/3.0.16/deb/vitam-product/)  
	- [Vitam-external](https://download.programmevitam.fr/vitam_repository/3.0.16/deb/vitam-external/)  
* [Release notes](https://github.com/ProgrammeVitam/vitam/releases/download/3.0.16/release-notes.3.0.16.pdf)  

[Documentation de la version 3.0.16](https://www.programmevitam.fr/pages/documentation/liste_doc_ancienne/#R13_16)





* **la documentation fonctionnelle et technique**

Elle est accessible, en partie  sur GitHub pour les documents en forme brute RST, intégralement dans les packages sur Bintray, mais aussi directement sous forme PDF et/ou HTML sur la page [Documentation](/pages/documentation).

* **les Release Notes**

<https://github.com/ProgrammeVitam/vitam/releases>

<a name="exemples"></a>
## Des exemples d'usage

Vous pouvez utiliser pour tester le logiciel un jeu de fichiers référentiels et paquets SIP:

* **Fichiers de test du Cahier de tests métier**
([zip](https://download.programmevitam.fr/vitam_repository/4.0.0/tests/Jeux_de_tests_fonctionnels_R16.zip)) Ces éléments vous permettent de jouer les tests du cahier de test (liste des tests manuels sur les IHM) aux formats Calc ([ods](/ressources/DocCourante/autres/fonctionnel/VITAM_cahier_de_recette_fonctionnel.ods)) \| et Excel ([xlsx](/ressources/DocCourante/autres/fonctionnel/VITAM_cahier_de_recette_fonctionnel.xlsx)) 



<a name="journée2"></a>
## Présentation de la deuxième version de production de la solution logicielle Vitam

Le 18 mars 2019 une journée de présentation de la V2 de la solution logicielle Vitam a permis à un large public de découvrir les nouvelles fonctionnalités livrées et l'état d'avancement des projets utilisateurs. L'événement a réuni 280 participants aux Archives nationales sur le site de Pierrefitte-sur-Seine. La journée était séquencée en 3 temps.


**La présentation des nouvelles fonctionnalités**

Cette première partie a permis de faire un point sur les fonctionnalités de la V2, et de les démontrer. Les éléments présentés concernaient :
* la recherche par facette, 
* le contrôle de l'indexation et des métadonnées,
* la mise à jour et la modification en masse d'une métadonnée descriptive (titre),
* le rattachement,
* les éliminations,
* la préservation.

La présentation est consultable en suivant ce lien : ([pdf](/ressources/Doc2.1.1/autres/fonctionnel/20190318_1_présentation_1ere_partie_VITAM_préservation_VDiffusion.pdf)).

Les vidéos des différentes fonctionnalités de la V2, diffusées lors de cette session, sont accessibles sur la page [Démonstration](/pages/demonstration).


**Les actualités des projets d'implémentation**

Une deuxième partie a fait un point d'actualités et un état d'avancement des projets d'utilisation de la solution logicielle Vitam : 
* Adamant (Ministère de la Culture/Archives nationales), 
* Archipel (Ministère des Armées), 
* Saphir (Ministère de l'Europe et des Affaires étrangères), 
* Siamae (Ministère de la Transition Ecologique et Solidaire)
	* La présentation de ces projets est consultable en suivant ce lien : ([pdf](/ressources/Doc2.1.1/autres/fonctionnel/20190318_2_présentation_V2_2e_partie_VDiffusion.pdf))
* et Vitam/in (CEA)
	* La présentation de ce projet est consultable en suivant ce lien : ([pdf](/ressources/Doc2.1.1/autres/fonctionnel/20190318_3_présentation_V2_2e_partie_VITAMIN_VDiffusion.pdf))


**Les outils de préparation des versements**

Une troisème partie était consacrée aux outils de préparation des versements d'archives numériques : 
* Octave (Ministère de la Culture/SIAF), 
* Archifiltre (Ministères sociaux), 
* SedaTools (Vitam)
	* La présentation de ces projets est consultable en suivant ce lien :  ([pdf](/ressources/Doc2.1.1/autres/fonctionnel/20190318_4_présentation_V2_3e_partie_préparation_versement_VDiffusion.pdf))

<a name="journée1"></a>
## Présentation de la Première version de production de la solution logicielle Vitam

Une présentation de la Première version de production de la solution logicielle Vitam a eu lieu aux Archives nationales le 11 avril 2018, réunissant environ 250 personnes. Le support de présentation est consultable ici : ([pdf](/ressources/Doc1.0.0/autres/fonctionnel/20180411_présentation_vitam_V5.0_publication.pdf))