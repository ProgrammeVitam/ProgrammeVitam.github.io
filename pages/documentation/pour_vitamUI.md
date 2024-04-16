---
layout: page
title: Doc. Vitam UI
fatherref: documentation
---

> Est ici présentée la documentation de Vitam UI.

Naviguer dans la documentation par domaine :
* [Organisation et droits utilisateurs](#orga)
* [Référentiels](#referentiels)
* [Sécurité et droits applicatifs](#secu)
* [Supervision et audit](#supervision)
* [Versement et consultation](#versement)

Documentation générale
* **Vitam UI : documentation produit** ([pdf](/ressources/DocCourante/autres/fonctionnel/VitamUI_Doc_produit.pdf))
* **Vitam et Vitam UI : guide de prise en main** ([pdf](https://www.programmevitam.fr/vitam-doc/fr/master/sections/guide_prise_en_main.html))
* **Vitam UI : jeu de tests pour prise en main** ([zip](https://download.programmevitam.fr/jeux_de_tests/v6/Jeux_de_tests_Guide_de_prise_en_main_VitamUI.zip))
* **Vitam UI : présentation de la fonctionnalité d’auto-provisioning**([html](https://www.programmevitam.fr/vitam-doc/fr/master/sections/VitamUI_Autoprovisionning.html))

## Guide de lecture de la documentation Vitam UI

### Domaine : organisation et droits utilisateurs<a name="orga"> 

![Logos](/public/images/VitamUI_organisation.JPG){: style="display: block; margin-left: auto; margin-right: auto; height:30rem"} 

|Ordre d'exécution|Je souhaite...|Je suis...|APP Vitam UI|
|:----|:-----|:----|:-----|
|1.1 (obligatoire)|créercréer une nouvelle organisation utilisatrice de Vitam UI et lui associer 1 ou plusieurs coffre(s)|administrateur d'instance (si vous exposez Vitam UI en tant que service), administrateur technique VitamUI (si vous utilisez Vitam UI hébergé en propre)|[Organisation](https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_Organisation.pdf)|
|1.2 (obligatoire)|créer le compte nominatif de l'administrateur fonctionnel d'une organisation à des fins d'activation et prendre la main sur la session d'un utilisateur à des fins de support|administrateur d'instance (si vous exposez Vitam UI en tant que service), administrateur technique VitamUI (si vous utilisez Vitam UI hébergé en propre)|[Subrogation](https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_Subrogation.pdf)|
|1.2 (facultatif)|définir des droits fins sur les utilisateurs de mon organisation en créant un nouveau profil de droits|administrateur fonctionnel Vitam UI|[Profil APP Utilisateur](https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_Profil_APP_Utilisateur.pdf)|
|1.3 (obligatoire sauf si le groupe existe déjà)|définir des regroupements de droits sur les APPs Vitam UI pour mes utilisateurs en créant un nouveau groupe de profils|administrateur fonctionnel Vitam UI|[Groupe de profil](https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_Groupe_profil.pdf)|
|1.4 (obligatoire sauf si le groupe existe déjà)|créer mes utilisateurs et leur attribuer des droits|administrateur fonctionnel Vitam UI|[Utilisateur](https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_Utilisateur.pdf)|
|NA|paramétrer des profils de droits permettant d’associer un contrat d’accès à un utilisateur|administrateur fonctionnel Vitam UI|[Profil APP Paramétrages externes](https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_Profil_APP_Parametrages_externes.pdf)|
|NA|Créer de nouveaux profils de niveaux inférieurs, limiter l’attribution de profils à une portée d’utilisateurs et adapter la séparation des rôles|opérateur d'instance|[APP Hiérarchisation des profils](https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_Hierarchisation_profils.pdf)|

### Domaine : référentiels<a name="referentiels">  

![Logos](/public/images/VitamUI_referentiels.JPG){: style="display: block; margin-left: auto; margin-right: auto; height:30rem"}

|Ordre d'exécution|Je souhaite...|Je suis...|APP Vitam UI|
|:----|:-----|:----|:-----|
|2.1 (obligatoire)|déclarer un nouveau service producteur ou un nouveau service versant dans Vitam UI|administrateur fonctionnel Vitam UI|[Services agents](https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_Services_agents.pdf)|
|2.2 (obligatoire)|déclarer des nouvelles règles de gestion|administrateur fonctionnel Vitam UI|[Règles de gestion](https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_Regles_gestion.pdf)|
|2.3 (facultatif)|créer et modifier un profil d’archivage (PA) ou un profil d’unité archivistique (PUA), créer et modifier une notice d’un profil, importer et exporter un profil d’archivage|administrateur fonctionnel Vitam UI|[Profils documentaires](https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_Profils_documentaires.pdf)|
|2.4 (facultatif)|déclarer un nouveau format non présent dans le référentiel PRONOM|administrateur technique Vitam UI|[Formats de fichiers](https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_Formats_fichiers.pdf)|
|2.5 (facultatif)|déclarer un nouveau vocabulaire non présent dans l'ontologie SEDA|administrateur technique Vitam UI|[Ontologie](https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_Ontologie.pdf)|
|2.6 (facultatif)|importer un arbre de positionnement ou un plan de classement|administrateur fonctionnel Vitam UI|[Arbres et plans](https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_Arbres_plans.pdf)|
|2.7 (facultatif)|rechercher et consulter un contrat de gestion, le créer et le mettre à jour|administrateur fonctionnel Vitam UI|[Contrat de gestion](https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_Contrat_gestion.pdf)|

### Domaine : Sécurité et droits applicatifs<a name="secu">  

![Logos](/public/images/VitamUI_securite.JPG){: style="display: block; margin-left: auto; margin-right: auto; height:30rem"}  

|Ordre d'exécution|Je souhaite...|Je suis...|APP Vitam UI|
|:----|:-----|:----|:-----|
|3.1 (obligatoire sauf si le contrat existe déjà)|paramétrer des droits pour le versement d'archives dans un coffre par une nouvelle application|administrateur fonctionnel Vitam UI|[Contrat d'entrée](https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_Contrat_entree.pdf)|
|3.2 (obligatoire sauf si le contrat existe déjà)|paramétrer des droits pour la consultation ou mise à jour d'archives dans un coffre par une nouvelle application|administrateur fonctionnel Vitam UI|[Contrat d'accès](https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_Contrat_acces.pdf)|
|3.3 (obligatoire sauf si le contrat existe déjà)|définir les droits d'une nouvelle application sur les services exposés par Vitam|administrateur technique Vitam UI|[Profil de sécurité](https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_Profil_securite.pdf)|
|3.4 (obligatoire sauf si le contrat existe déjà)|authentifier une nouvelle application interconnectée avec Vitam et lui attribuer des droits|administrateur technique Vitam UI|[Contexte applicatif](https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_Contexte_applicatif.pdf)|

### Domaine : supervision et audit<a name="supervision">

![Logos](/public/images/VitamUI_supervision.JPG){: style="display: block; margin-left: auto; margin-right: auto; height:30rem"}  

|Je souhaite...|Je suis...|APP Vitam UI|
|:-----|:----|:-----|
|consulter le journal des opérations VITAM (entrées, éliminations et données de base)|administrateur technique Vitam UI ou administrateur fonctionnel Vitam UI|[Journal des opérations](https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_Journal_operations.pdf)|
|visualiser les opérations de sécurisation et accéder aux journaux du cycle de vie des objets|administrateur technique Vitam UI|[Opérations de sécurisation](https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_Operations_securisation.pdf)|
|effectuer des requêtes complexes sur les bases de données documentaires en vue de retrouver des objets|administrateur technique Vitam UI|[Requêtes DSL](https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_RequetesDSL.pdf)|
|vérifier la conformité de la conservation de mes archives|administrateur fonctionnel Vitam UI, super-archiviste|[Audit](https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_Audit.pdf)|
|produire un relevé de valeur probante sur une ou plusieurs de mes archives électroniques|administrateur fonctionnel Vitam UI, super-archiviste|[Relevé de valeur probante](https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_Releve_valeur_probante.pdf)|
|gérer des opérations et interagir sur les étapes du workflow des opérations|administrateur fonctionnel Vitam UI, super-archiviste|[Gestion des opérations](https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_Gestion_operations.pdf)|

### Domaine : versement et consultation<a name="versement">

![Logos](/public/images/VitamUI_versement.JPG){: style="display: block; margin-left: auto; margin-right: auto; height:30rem"}  

|Je souhaite...|Je suis...|APP Vitam UI|
|:-----|:----|:-----|
|créer un projet de versement, consulter et rechercher les unités archivistiques liées à un versement, ajouter des métadonnées descriptives et de gestion des unités archivistiques, consulter, valider, transférer les versements liés à un projet|archiviste|[Collecte et préparation des versements](https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_Collecte_et_preparation_des_versements.pdf)|
|déposer un lot d'archives dans le SAE et en visualiser l'entrée|archiviste|[Dépôt et suivi des versements](https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_Depot_et_suivi_versements.pdf)|
|rechercher et télécharger des unités archivistiques contenues dans le SAE|archiviste|[Recherche et consultation des archives](https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_Recherche_et_consultation.pdf)|
|consulter et rechercher dans le registre des fonds|archiviste|[Registre des fonds](https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_Registre_des_fonds.pdf)|