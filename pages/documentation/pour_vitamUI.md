---
layout: page
title: Doc. Vitam UI
fatherref: documentation
---

> Est ici présentée la documentation de Vitam UI.

* [Première approche](pour_approche_deb)
* [Vademecums ou "Vitam pour mes grands-parents"](vademecums)
* [Documentation métier](pour_archiviste)
* [Documentation des tests](pour_test)
* [Documentation technique](pour_tech)
* [Documentation développeur](pour_dev)
* [Chantier préservation : documentation](sur_chantier_preservation)

<table>
<caption><b>Guide de lecture de la documentation Vitam UI</b></caption>
	<tr>
		<th>Domaine</th>
		<th>Ordre d'exécution</th>
		<th>Je souhaite... </th>
		<th>Je suis... </th>
		<th>APP Vitam UI</th>
		<th>Documentation</th>
	</tr>
	<tr>
		<td>Organisation et droits utilisateurs</td>
		<td>1.1 (obligatoire)</td>
		<td>... créer une nouvelle organisation utilisatrice de VITAM UI et lui associer 1 ou plusieurs coffre(s)</td>
		<td>... administrateur d'instance (si vous exposez VITAM UI en tant que service), administrateur technique VitamUI (si vous utilisez VITAM UI hébergé en propre)</td>
		<td>Organisation</td>
		<td><a href="https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_organisation.pdf">Organisation</a></td>
	</tr>
	<tr>
		<td>Organisation et droits utilisateurs</td>
		<td>1.2 (obligatoire)</td>
		<td>... créer le compte nominatif de l'administrateur fonctionnel d'une organisation à des fins d'activation et prendre la main sur la session d'un utilisateur à des fins de support</td>
		<td>... administrateur d'instance (si vous exposez VITAM UI en tant que service), administrateur technique VitamUI (si vous utilisez VITAM UI hébergé en propre)</td>
		<td>Subrogation</td>
		<td><a href="https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_subrogation.pdf">Subrogation</a></td>
	</tr>
	<tr>
		<td>Organisation et droits utilisateurs</td>
		<td>1.2bis (facultatif)</td>
		<td>... définir des droits fins sur les utilisateurs de mon organisation en créant un nouveau profil de droits</td>
		<td>... administrateur fonctionnel VITAM UI</td>
		<td>Profil APP Utilisateur</td>
		<td><a href="https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_profil_app_utilisateur.pdf">Profil APP Utilisateur</a></td>
	</tr>
	<tr>
		<td>Organisation et droits utilisateurs</td>
		<td>1.3 (obligatoire sauf si le groupe existe déjà)</td>
		<td>... définir des regroupements de droits sur les APPs VITAM UI pour mes utilisateurs en créant un nouveau groupe de profils</td>
		<td>... administrateur fonctionnel VITAM UI</td>
		<td>Groupes de profils</td>
		<td><a href="https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_groupe_profil.pdf"Groupes de profils</a></td>
	</tr>
	<tr>
		<td>Organisation et droits utilisateurs</td>
		<td>1.4 (obligatoire sauf si le groupe existe déjà)</td>
		<td>... créer mes utilisateurs et leur attribuer des droits</td>
		<td>... administrateur fonctionnel VITAM UI</td>
		<td>Utilisateur</td>
		<td><a href="https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_utilisateur.pdf">Utilisateur</a></td>
	</tr>
	<tr>
		<td>Référentiels</td>
		<td>2.1 (obligatoire)</td>
		<td>... déclarer un nouveau service producteur ou un nouveau service versant dans VITAM UI</td>
		<td>... administrateur fonctionnel VITAM UI</td>
		<td>Services agents</td>
		<td><a href="https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_services_agents.pdf">Services agents</a></td>
	</tr>
	<tr>
		<td>Référentiels</td>
		<td>2.1 bis (facultatif)</td>
		<td>... déclarer un nouveau format non présent dans le référentiel PRONOM</td>
		<td>... administrateur technique VITAM UI</td>
		<td>Formats de fichiers</td>
		<td><a href="https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_formats_fichiers.pdf">Formats de fichier</a></td>
	</tr>
	<tr>
		<td>Référentiels</td>
		<td>2.1 ter (facultatif)</td>
		<td>... déclarer un nouveau vocabulaire non présent dans l'ontologie SEDA</td>
		<td>... administrateur technique VITAM UI</td>
		<td>Ontologie</td>
		<td><a href="https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_ontologie.pdf">Ontologie</a></td>
	</tr>
	<tr>
		<td>Sécurité et droits applicatifs</td>
		<td>3.1 (obligatoire sauf si le contrat existe déjà)</td>
		<td>... paramétrer des droits pour le versement d'archives dans un coffre par une nouvelle application</td>
		<td>... administrateur fonctionnel VITAM UI</td>
		<td>Contrats d'entrée</td>
		<td><a href="https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_contrats_entree.pdf">Contrats d'entrée</a></td>
	</tr>
	<tr>
		<td>Sécurité et droits applicatifs</td>
		<td>3.2 (obligatoire sauf si le contrat existe déjà)</td>
		<td>... paramétrer des droits pour la consultation ou mise à jour d'archives dans un coffre par une nouvelle application</td>
		<td>... administrateur fonctionnel VITAM UI</td>
		<td>Contrats d'accès</td>
		<td><a href="https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_contrats_acces.pdf">Contrats d'accès</a></td>
	</tr>
	<tr>
		<td>Sécurité et droits applicatifs</td>
		<td>3.3 (obligatoire sauf si le contrat existe déjà)</td>
		<td>... définir les droits d'une nouvelle application sur les services exposés par VITAM</td>
		<td>... administrateur technique VITAM UI</td>
		<td>Profils de sécurité</td>
		<td><a href="https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_profils_securite.pdf">Organisation</a></td>
	</tr>
	<tr>
		<td>Sécurité et droits applicatifs</td>
		<td>3.4 (obligatoire sauf si le contrat existe déjà)</td>
		<td>... authentifier une nouvelle application interconnectée avec VITAM et lui attribuer des droits</td>
		<td>... administrateur technique VITAM UI</td>
		<td>Contexte applicatif</td>
		<td><a href="https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_contextes_applicatifs.pdf">Contexte applicatif</a></td>
	</tr>
	<tr>
		<td>Supervision et audit</td>
		<td>NA</td>
		<td>... visualiser les opérations de sécurisation et accéder aux journaux du cycle de vie des objets</td>
		<td>... administrateur technique VITAM UI</td>
		<td>Opérations de sécurisation</td>
		<td><a href="https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_operations_securisation.pdf">Opérations de sécurisation</a></td>
	</tr>
	<tr>
		<td>Supervision et audit</td>
		<td>NA</td>
		<td>... effectuer des requêtes complexes sur les bases de données documentaires en vue de retrouver des objets</td>
		<td>... administrateur technique VITAM UI</td>
		<td>Requêtes DSL</td>
		<td><a href="https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_requetes.pdf">Requêtes DSL</a></td>
	</tr>
	<tr>
		<td>Supervision et audit</td>
		<td>NA</td>
		<td>... vérifier la conformité de la conservation de mes archives</td>
		<td>... administrateur fonctionnel VITAM UI, super-archiviste</td>
		<td>Audits</td>
		<td><a href="https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_audits.pdf">Audits</a></td>
	</tr>
	<tr>
		<td>Supervision et audit</td>
		<td>NA</td>
		<td>... produire un relevé de valeur probante sur une ou plusieurs de mes archives électroniques</td>
		<td>... administrateur fonctionnel VITAM UI, super-archiviste</td>
		<td>Relevé de valeur probante</td>
		<td><a href="https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_releve_valeur_probante.pdf">Relevé de valeur probante</a></td>
	</tr>
</table>