---
layout: page
title: Démonstrations
fatherref: demonstrations
level: page
---

> Sont ici présentées des démonstrations vidéo de l'usage de Vitam ou du développement de certaines fonctionnalités

## Liste des vidéos
* [Présentation des fonctionnalités de la V2 de la solution logicielle Vitam (Release 9)](#pres_R9)
* [Présentation des fonctionnalités de la solution logicielle Vitam et des API de la version Release 5(0.26.x)](#pres_R5)
* [Présentation générale de Vitam et de l'usage des API sur la version Release 4(0.20.x)](#pres_R4)
* [Présentation de l'usage des API sur la version Bêta](#pres_api_beta)

<hr/>

## Présentation des fonctionnalités de la V2 de la solution logicielle Vitam (Release 9)

Ces vidéos ont été diffusées lors de la journée de présentation de la V2 de la solution logicielle Vitam. Des compléments d'information sont disponibles dans le support de présentation de la première partie présentant les fonctionnalités de la V2, faisant une large place à la préservation numérique : ([pdf](/ressources/DocCourante/autres/fonctionnel/20190318_1_présentation_1ere_partie_VITAM_préservation_VDiffusion.pdf))



### Démonstration 1 : Scénario Recherche par facette
<iframe width="560" height="315" src="https://www.youtube.com/embed/b209S-qwN3E" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Etape | Description | Timing
----- | ----------- | ------
1. | 	Consulter dans le tenants  | 0:10.		
2. | 	Chercher age ou beneficiary : ils n’existent pas. 	 | 00:28’
3. | 	Montrer le json de l'ontologie mise à jour : age ou beneficiary existent bien.	 | 00:50
4. | 	Se déconnecter du tenant 10 puis se connecter dans le tenant d’administration.	 | 01:15	
5. | 	Bien avoir un Contrat permettant la « modification ».	 | 01:35	
6. | 	Importer l’ontologie.	 | 01:45	
7. | 	Reconnexion au tenant 10.	 | 02:05	
8. | 	Rechercher age ou beneficiary : ils existent bien dans ontologie et sont indexés comme « EXTERNAL ».	 | 02:15	
9. | 	Montrer le JSON des notices d'Archive Unit Profile (AUP).	 | 02:45
10. | 	Consultation aucune notice d'AUP n'a été importée.	 | 03:06	
11. | 	Import de la notice d'AUP.	 | 03:12	
12. | 	Import OK / Consultation de la notice d'AUP.	 | 03:28	
13. | 	Copier/coller le schéma de contrôle JSON (AUP) du dossier (il est possibilité de valider la qualité du json).	 | 03:48	
14. | 	Copier/coller le schéma de contrôle JSON (AUP) du document.	 | 04 :17	
15. | 	Consultation aucun profil d’archivage (profil Seda) n'a été importée. 	 | 05:20	
16. | 	Montrer le fichier JSON de notice du profil d’archivage. 	 | 05:38	
17. | 	Import de la notice notice du profil d’archivage.	 | 05:46	
18. | 	Consulter la notice du profil d'archivage importée.	 | 05:55	
19. | 	Montrer le profil d’archivage (fichier XML). 	 | 06:11	
20. | 	Rattacher (importer) le profil d’archivage à la notice. 	 | 06:54	
21. | 	Montrer le contrat d’entrée spécifique au dossier militaire. Il fait référence au profil d’archivage. 	 | 07:17	
22. | 	Montrer le bordereau de versement (manifeste XML). Il référence : le contrat d’entrée, les 2 AUP, le profil d’archivage. 	 | 07:35	
23. | 	Importer le paquet à archiver (SIP). Rappel : pour constituer le SIP, il est nécessaire de zipper ses éléments dans le dossier et non le dossier lui même).  | 08:25	
24. | 	Rechercher le terme Némo. Ses métadonnées référencent l’AUP de pièce.	 | 09:01


* Démonstration 2 : Contrôle de l’indexation et des méta-données
<iframe width="560" height="315" src="https://www.youtube.com/embed/SyOJMd3LEvc" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>



* Démonstration 3 : Mise à jour en masse – Modifier une métadonnée descriptive (titre)
<iframe width="560" height="315" src="https://www.youtube.com/embed/mXH5dflQ3DM" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>



* Démonstration 4 : Rattachement
<iframe width="560" height="315" src="https://www.youtube.com/embed/mXH5dflQ3DM" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>



* Démonstration 5 : Eliminations
<iframe width="560" height="315" src="https://www.youtube.com/embed/YDaePDNOZ4o" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>



* Démonstration 6 : Préservation - conversion de format
<iframe width="560" height="315" src="https://www.youtube.com/embed/N3SdPElTSDs" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


## Présentation des fonctionnalités de la solution logicielle Vitam et des API de la version Release 5 (0.26.x)
<a name="pres_R5"></a>

Les vidéos présentent différentes fonctionnalités proposées par la solution logicielle Vitam (version Release 5).

* Transférer un paquet à archiver (SIP) :
<iframe width="560" height="315" src="https://www.youtube.com/embed/Gb29J-GHf7k" frameborder="0" gesture="media" allow="encrypted-media" allowfullscreen></iframe>
<br>

* Rechercher une archive :
<iframe width="560" height="315" src="https://www.youtube.com/embed/az-ZPVoeoXg" frameborder="0" gesture="media" allow="encrypted-media" allowfullscreen></iframe>
<br>

* Les contrats d’entrées :
<iframe width="560" height="315" src="https://www.youtube.com/embed/paXo4DpT_2Q" frameborder="0" gesture="media" allow="encrypted-media" allowfullscreen></iframe>
<br>

* Les contrats d’accès :
<iframe width="560" height="315" src="https://www.youtube.com/embed/khkcJ2rnPiY" frameborder="0" gesture="media" allow="encrypted-media" allowfullscreen></iframe>
<br>

* Le référentiel des règles de gestions :
<iframe width="560" height="315" src="https://www.youtube.com/embed/Kub8f4lD1WE" frameborder="0" gesture="media" allow="encrypted-media" allowfullscreen></iframe>
<br>

* Les profils d’archivage :
<iframe width="560" height="315" src="https://www.youtube.com/embed/TFleNc9UgJw" frameborder="0" gesture="media" allow="encrypted-media" allowfullscreen></iframe>
<br>

* Le référentiel des services agents :
<iframe width="560" height="315" src="https://www.youtube.com/embed/0WpRKCDiHbw" frameborder="0" gesture="media" allow="encrypted-media" allowfullscreen></iframe>
<br>

* Le référentiel des formats :
<iframe width="560" height="315" src="https://www.youtube.com/embed/bTkSOjApz_U" frameborder="0" gesture="media" allow="encrypted-media" allowfullscreen></iframe>
<br>

* Réaliser des audits d’existence et d’intégrité des objets archivés :
<iframe width="560" height="315" src="https://www.youtube.com/embed/pYBnchomvdU" frameborder="0" gesture="media" allow="encrypted-media" allowfullscreen></iframe>
<br>

* Extraire des archives sous la forme d’un DIP (dissemination information package) :
<iframe width="560" height="315" src="https://www.youtube.com/embed/Pz9jgIrO37w" frameborder="0" gesture="media" allow="encrypted-media" allowfullscreen></iframe> 
<br>

* Effectuer une requête en langage DSL :
<iframe width="560" height="315" src="https://www.youtube.com/embed/AzvZtCNZi7w" frameborder="0" gesture="media" allow="encrypted-media" allowfullscreen></iframe> 
<br>

Pour reproduire ces tests, il est possible d'utiliser les éléments suivants :
* Guide de prise en main ([pdf](/ressources/Doc0.26.0/Vitam_Documentation_Kit_de_prise_en_main.pdf))
* Contrat d'accès ([json](/ressources/RefCourant/exemple_contrat_acces_tous_droits.json))
* Contrat d'entrée ([json](/ressources/RefCourant/exemple_contrat_entree.json))
* Référentiel Agents ([csv](/ressources/RefCourant/exemple_referentiel_agents.csv))
* Référentiel des règles de gestion ([csv](/ressources/RefCourant/exemple_referentiel_regles.csv))



## Présentation générale de Vitam et de l'usage des API sur la version Release 4(0.20.x)
<a name="pres_R4"></a>

<iframe width="560" height="315" src="https://www.youtube.com/embed/ePoduZzoh7c" frameborder="0" allowfullscreen></iframe>
<br>
<iframe width="560" height="315" src="https://www.youtube.com/embed/0gkDZHr3PxU" frameborder="0" allowfullscreen></iframe>
<br>
Pour reproduire ces tests vous devez utiliser les exemples de référentiels et de SIP suivants:

* Référentiel [PRONOM](https://www.nationalarchives.gov.uk/PRONOM/Default.aspx) des formats ([xml](/ressources/DemoR4/DROID_SignatureFile_V88.xml))
* Référentiel de règles ([csv](/ressources/DemoR4/jeu_donnees_OK_regles_CSV.csv))
* Référentiel des contrats ([json](/ressources/DemoR4/referential_contracts_ok.json))
* SIP de test ([zip](/ressources/DemoR4/SIP_14juillet_light.zip))

**A noter:** avant de charger le SIP d'exemples, il faut avoir importé les 3 référentiels de formats, de règles de gestion et de contrats.


## Présentation de l'usage des API sur la version Bêta
<a name="pres_api_beta"></a>

<iframe width="560" height="315" src="https://www.youtube.com/embed/iQCojgA_VIM" frameborder="0" allowfullscreen></iframe>
<br>
<iframe width="560" height="315" src="https://www.youtube.com/embed/wqCSStI8jgc" frameborder="0" allowfullscreen></iframe>
<br>
<iframe width="560" height="315" src="https://www.youtube.com/embed/waiLMN6qV1k" frameborder="0" allowfullscreen></iframe>
<br>
<iframe width="560" height="315" src="https://www.youtube.com/embed/CvOMMZQVraI" frameborder="0" allowfullscreen></iframe>
<br>
<iframe width="560" height="315" src="https://www.youtube.com/embed/OEy1AKz_nvI" frameborder="0" allowfullscreen></iframe>
<br>
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZdMPyC5ADsc" frameborder="0" allowfullscreen></iframe>
<br>
<iframe width="560" height="315" src="https://www.youtube.com/embed/AuNR95yJ3Ns" frameborder="0" allowfullscreen></iframe>

Pour reproduire ces tests vous devez utiliser la configuration Postman qui est accessible dans la ([documentation](../documentation/liste_doc_ancienne/index.html#config_postman)) de la Bêta, et les exemples de référentiels et de SIP suivants:

* Référentiel [PRONOM](https://www.nationalarchives.gov.uk/PRONOM/Default.aspx) des formats ([xml](/ressources/DemoAPI/DROID_SignatureFile_V88.xml))
* Référentiel de règles ([csv](/ressources/DemoAPI/jeu_donnees_OK_regles_CSV_regles.csv))
* SIP Conforme ([zip](/ressources/DemoAPI/SIP-Conforme-Beta.zip))
* SIP Non conforme ([zip](/ressources/DemoAPI/SIP-Non-Conforme.zip))
