---
layout: page
title: version 2
---

> Ces vidéos ont été diffusées lors de la journée de présentation de la V2 de la solution logicielle Vitam. Des compléments d'information sont disponibles dans le support de présentation de la première partie présentant les fonctionnalités de la V2, faisant une large place à la préservation numérique : ([pdf](/ressources/DocCourante/autres/fonctionnel/20190318_1_présentation_1ere_partie_VITAM_préservation_VDiffusion.pdf))

### Démonstration 1 : Scénario Recherche par facette

Cette fonctionnalité permet d'affiner les résultats d'une recherche au moyen de facettes par :
* Services producteurs,
* Type d’unités archivistiques comportant des objets ou non
* Niveau de description….

<iframe width="560" height="315" src="https://www.youtube.com/embed/b209S-qwN3E" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


Etape | Description | Timing
----- | ----------- | ------
1.   | Dans l’onglet « Recherche globale ». | 
2.   | Saisir le terme « Archives nationales » puis taper sur la touche « Entrée » ou « Rechercher » pour lancer la recherche. 	 | 00:10
3.   | La recherche fournit 3800 résultats. | 
4.   | Cliquer sur le bouton + présent à droite du titre « Affiner la recherche ». | 
5.   | Sélectionner les critères voulus, par exemple, « Niveau de description » et « Producteurs » puis taper sur « Rechercher ». 	 | 00:20
6.   | On peut ensuite sélectionner une facette, Producteur, par exemple, « FRAN_000001 » et accéder aux détail de ses archives : les newsletters.  | 00:25
7.   | On peut ensuite sélectionner une facette, niveau de description, par exemple, « Serie ». Ceci permet d’accéder aux niveaux d'arborescence, ici un arbre de positionnement.  | 00:32 
8.   | Saisir le terme « bulletin » puis taper sur la touche « Entrée » ou « Rechercher » pour lancer la recherche.	 | 00:49
9.   | Sélectionner les critères voulus, par exemple, unité archivistique avec Objets ou sans Objet. Ceci permet d’accéder aux niveaux de classement.	 | 01:05 



### Démonstration 2 : Contrôle de l’indexation et des méta-données

Cette vidéo présente les modalités de contrôle de modification des métadonnées et d'indexation.


L’ontologie est une liste, par défaut, des termes indexés dans la solution logicielle Vitam (métadonnées du Seda ou ajoutées par Vitam). Il est possible d’y ajouter une
entrée d’indexation :
* EX : indexation de données géographiques : coordonnées GPS,
* EX : indexation de dossiers individuels : Age.


Des profils d’unité archivistiques (AUP), modèles de description d’archives, ont été ajoutés pour permettre de :
* Contrôler, plus finement qu’avec un profil Seda, les métadonnées accompagnant des versements.
* Définir les informations obligatoires et facultatives pour décrire un type de dossier :
	* EX 1 AUP Acte de naissance, ou un AUP dossier d’agent.
* Contrôler les mises à jour de métadonnées dans Vitam :
	* EX : obligation de renseigner le champ âge par un nombre entier (LONG);
	* EX : obligation de renseigner le champ coordonnées GPS par GEO_POINT.
	
	
<iframe width="560" height="315" src="https://www.youtube.com/embed/SyOJMd3LEvc" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


Etape | Description | Timing
----- | ----------- | ------
1. | 	Consulter dans le tenant.  | 0:10.		
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
13. | 	Copier/coller le schéma de contrôle JSON (AUP) du dossier (il est possible de valider la qualité du json).	 | 03:48	
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


### Démonstration 3 : Mise à jour en masse – Modifier une métadonnée descriptive (titre)

Cette fonctionnalité permet de corriger une coquille, remplacer une description, apporter une précision… dans un champ de métadonnées.


<iframe width="560" height="315" src="https://www.youtube.com/embed/2dF17UY9pJo" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Etape | Description | Timing
----- | ----------- | ------
1.	 | Dans le menu Recherche / Recherche d'archives, dans l'onglet Recherche Globale saisir « Fractures » dans le champ « Intitulé ou description ». 	 | 00:10’	
2.	 | Mettre cette unité archivistique ainsi que l'ensemble de son entrée dans le panier, en cliquant dans la colonne « Ajout au panier » sur le symbole représentant un carton d'archives. 3 possibilités sont offertes, ajouter l'unité archivistique seule, l’entrée, ou l'unité archivistique et sa descendance.  | 
3.	 | Accéder au panier, il comporte 25 résultats.	  | 00:28’	
4.	 | Dans le panier, dans le champ « Sélectionner une action » choisir « Mise à jour de masse ».	 | 00:38’	
5.	 | Cliquer sur « Mise à jour des métadonnées descriptives » pour déplier ce bloc.	 | 00:44’	
6.	 | Cliquer sur le bouton « Ajouter/Modifier une métadonnée descriptive ».	 | 
7.	 | On montre aussi les autres possibilités.		 | 
8.	 | Dans le champ « Intitulé » saisir « Title », dans le champ « Valeur du champ » saisir « Factures ».  	 | 01:00	
9.	 | Sélectionner l’ensemble du panier.	 | 		
10.	 | Cliquer sur le bouton « Lancer la mise à jour de masse sur tout le panier ».	 | 01:34	
11.	 | Se rendre dans le journal des opérations. 	 | 01:55	
12.	 | Détail du Journal des Opérations : 25 éléments ont été modififiés.	 | 02:05	
13.	 | Rechercher « Fracture », il y a 0 résultat.	 | 02:25	
14.	 | Rechercher « Facture », il y a 25 résultats.	 | 02:45	



### Démonstration 4 : Rattachement

Le rattachement permet de réorganiser les arborescences pour les unités archivistiques présentes dans le système (postérieurement à leur versement) :
* Il ne peut être effectué qu’entre des unités archivistiques, des groupes d’objets techniques ou des objets sur un même tenant de la plate-forme ;
* Il permet de « reclasser » un ensemble d’archive, en le rattachant à une autre unité archivistique : par exemple, changer l’organisation des archives suite à un transfert de compétence entre service producteurs :
	* Cela correspond à créer un lien entre 2 unités archivistiques.


<iframe width="560" height="315" src="https://www.youtube.com/embed/mXH5dflQ3DM" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


Etape | Description | Timing
----- | ----------- | ------
1.	 | Ouvrir l’IHM recette et montrer les champs permettant d'effectuer les modifications.	 | 
2.	 | Bien sélectionner le Tenant 10.	 | 	
3.	 | Rechercher « Newsletter », l’unité archivistique à rattacher. Il s'agit d'une pièce. 	  | 00:15’
4.	 | Sélectionner son identifiant (ID). 	 | 00:30’	
5.	 | Coller l’identifiant (ID) de « Newsletter » dans l’IHM recette, dans le champ « Enfant ».	 | 00:42’	
6.	 | Recherche d’une unité archivitique à laquelle le rattacher : il s'agit d'un niveau d'arborescence (arbre de positionnement) « Coordination interministérielle » dont l'identifiant (ID) est aeaqaaaabihposu6aardqaljozvamqqaaaba. On voit que l'unité archivistique « Coordination interministérielle » ne comporte rien au niveau inférieur.  | 00:50’
7.	 | Coller l’identifiant (ID) de « Newsletter » dans l’IHM recette, dans le champ : parent.		 | 01:10	
8.	 | Sélectionner une action : Lancer rattachement. Attention, le contrat doit permettre les rattachements.		 | 01:20	
9.	 | Consulter le journal des opérations.		 | 01:44
10.	 | Rechercher « Coordination ». En consultant cette unité archivistique, on constate que « Newsletter » y est rattachée.	 	 | 02’14
11.	 | Consulter son Journal du cycle de vie. Le rattachement y figure.		 | 02:39	


### Démonstration 5 : Eliminations

Les élimination permettent de mettre en œuvre la gestion du cycle de vie et éliminer les unités archivistiques qui portent :
* une règle de durée d’utilité administrative (DUA) dont la date échue,
* un sort final « détruire ».

La phase d’analyse permet :
* d’étudier le caractère éliminable d’un ensemble d’unités archivistiques ;
* de définir le statut des unités archivistiques concernées :
	* KEEP / DESTROY (éliminable) / CONFLICT (non décidable),
	* d’établir la liste des services producteurs pour lesquels les unités archivistiques sont éliminables,
	* de constituer les lots à soumettre à une demande d’autorisation d’élimination.
	
La phase d’action permet d’éliminer effectivement les unités archivistiques qui peuvent l’être (à la fois en base et sur les offres de stockage).
* Les unités archivistiques, les groupes d’objets techniques, les objets techniques et les journaux du cycle de vie associés sont supprimés.
* Le registre des fonds est mis à jour.

<iframe width="560" height="315" src="https://www.youtube.com/embed/YDaePDNOZ4o" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


Etape | Description | Timing
----- | ----------- | ------
1.	 | Montrer le registre des fonds de l’ASP, il comporte 4499 articles et 0 supprimés.	 | 
2.	 | Saisir « ASP », dans l’écran de recherche.  	 | 00:40’
3.	 | Montrer le détail d’un des articles de ce SIP avec ses règles de gestion.	 | 01:05	
4.	 | Télécharger l’objet : fiche de paie. 	 | 01:25	
5.	 | Montrer le Référentiel des Règles de Gestion.	 | 01:45	
6.	 | Montrer le détail de la règle « APP-0047 » pour les fiches de paie. 	 | 02:00	
7.	 | Effectuer de nouveau la recherche ASP. Mettre directement dans le panier les résultats de recherche : la racine et toute sa descendance.	 | 02:10	
8.	 | Aller dans le panier et préparer une opération d’analyse  d’élimination sur le contenu du panier, en prenant comme date le 01/01/2020. 	 | 02:30	
9.	 | Lancer l’opération l'opération d’analyse  d’élimination.	 | 		
10.	 | Aller dans le journal des opérations et ouvrir l’opération correspondant à l'analyse d’élimination des archives de l'ASP. Copier l’identifiant de l’opération concernée.	 | 02:58	
11.	 | Aller dans Gestion des archives/résultats d’élimination et coller l’identifiant de l’opération dans le champ concerné. Lancer la recherche. Les résultats présentent 2368 unités archivistiques, dont le sort final est l'élimination au 01/01/2020. 	 | 03:24	
12.	 | Montrer sur cet écran que l’on peut filtrer les résultats, ceci permet de visualiser uniquement les niveaux d'arborescence. 	 | 03:45
13.	 | Retourner dans le panier.	 | 04:20	
14.	 | Lancer une opération d’élimination (action) en mettant comme date le 01/01/2020. Constater que ce n’est pas possible car la date est dans le futur.	 | 04:30	
15.	 | Corriger la date en mettant le 01/01/2017.	 | 04:45	
16.	 | Lancer l’opération d'élimination.	 | 04:50	
17.	 | Aller dans le journal des opérations et ouvrir l’opération correspondante. 	 | 05:03	
18.	 | Déplier le détail de l’opération concernée pour constater que l’opération est en warning et que le nombre d’unités archivistiques traitées est de 592. 	 | 05:11	
19.	 | Consultation du registre des fonds de l’ASP. Mêmes chiffres que dans le Journal des opérations 592 éliminés.	 | 05:35	
20.	 | Retourner sur l'écran de recherche et saisir à nouveau « ASP ». 	 | 05:53	
21.	 | Aller sur l’unité archivistique racine et naviguer dans les niveaux inférieurs. L'unité archivistique « bulletins de salaire 2011 » n’a plus de niveaux inférieurs, les archives ont été éliminées.  	 | 06:10	




### Démonstration 6 : Préservation - conversion de format

Cette vidéo présente les fonctionnalités identifiées lors du chantier préservation et développées dans la solution logicielle Vitam :
* Analyse de « qualité » : validation
* Génération de binaires (conversion)
* Identification de format
* Extraction de métadonnées techniques ou descriptives


3 éléments essentiels sont mis en œuvre dans la solution logicielle pour assurer la préservation :
* Référentiel des formats PRONOM ;
* Référentiel des griffons, liste d’outils externes pour effectuer des traitements :
	* EX : *« Siegfried est un outil d'identification. Couplé avec le référentiel PRONOM, il permet d'identifier et/ou de réidentifier les formats de fichier. »*
* Référentiel des scénarios de préservation : liste les actions possibles avec chaque outils :
	* EX : Génération de PDF/A avec LibreOffice (documents textes) : Ce scénario, appelant le griffon LibreOffice, permet de convertir des fichiers bureautiques de type textuel (.odt, .doc) en PDF/A.

<iframe width="560" height="315" src="https://www.youtube.com/embed/N3SdPElTSDs" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


Etape | Description | Timing
----- | ----------- | ------
1.	 | Montrer le référentiel des griffons.  | 		
2.	 | Montrer le détail d'un griffon : VeraPDF. 	 | 00:20’	
3.	 | Montrer le détail d'un griffon : libreOffice.	 | 00:33’	
4.	 | Montrer le référentiel des formats, avec le détail d’une notice : le JPG.	 | 00:40’	
5.	 | Montrer le fichier JSON du référentiel des scénarios de préservation avec le détail des champs. 	 | 01:10	
6.	 | Importer le fichier JSON du référentiel des scénarios de préservation.  	 | 01:50	
7.	 | Montrer le référentiel des scénarios de préservation, avec le détail d'un scénario de conversion en PDF. 	 | 02:00	
8.	 | Chercher une unité archivistique « Texte 5 » avec un fichier TXT. On constate que cette unité archivistique ne comporte qu'un seul objet.	 | 02:32	
9.	 | Mettre l’unité archivistique dans le panier (il est également possible de mettre toute l’entrée dans le panier). 	 | 03:05	
10.	 | Aller dans le panier, l'unité archivistique « Texte 5 » y figure bien.	 | 03:18	
11.	 | Sélectionner une action et la paramétrer sur l’original numérique, 1a version (FIRST), pour générer un original numérique en utilisant le scénario de préservation « Génération de PDF/A avec LibreOffice (documents textes) ». 	 | 03:30	
12.	 | Lancer l’action de préservation. 	 | 04:00	
13.	 | Aller voir le journal des opérations pour constater que l’opération est en succès. 	 | 04:10
14.	 | Recherche de l’unité archivistique « Texte 5 ».		 | 
15.	 | Consulter le détail de l’unité archivistique « Texte 5 » initialement recherchée. Constater qu’il y a maintenant 2 objets et ouvrir le fichier pdf. 	 | 04:55	
16.	 | Consulter le registre des fonds et montrer qu’il a été mis à jour pour le fonds correspondant (service_producteur). 	 | 05:20





