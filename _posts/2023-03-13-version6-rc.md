---
layout: post
title: Publication de la version 6.RC de la solution logicielle Vitam
---

![Logos](/public/images/version6rc.jpg)
> Quelques semaines avant la version LTS (long time support), voici publiée la version 6.RC (release candidate) de la solution logicielle Vitam. Ce fut une release candidate particulière à développer, préparer et vous proposer... Elle contient des nouveautés majeures, liées à des contributions et interdépendantes les unes avec les autres.

Les principales nouveautés de cette version 6.RC : 

- la prise en charge du SEDA 2.2 :
  - En entrée :
    - Importer un SIP avec un manifeste.xml exprimé en SEDA 2.1 ou en SEDA 2.2
    - Récupérer un ATR en en SEDA 2.1 ou en SEDA 2.2
    - En fonction de la version envoyée dans le manifeste.xml
    - Si erreur générée avant la lecture du manifeste.xml, l’ATR sera par défaut exprimé en SEDA 2.2
    - Réaliser des contrôles avec des profils d’archivage et des profils d’unité archivistique
  - En accès :
    - Exporter un DIP en SEDA 2.2.
    - Mettre à jour des unités archivistiques exprimées en SEDA 2.1 en leur ajoutant des
métadonnées spécifiques au SEDA 2.2 
    - Réaliser des contrôles sur les profils d’unité archivistiques
    - Transférer des archives en SEDA 2.2
  
    
    <br>


- la version gamma du module de collecte (nouvelle APP pour Vitam UI et connecteur avec API en mode lot)  

  En version 6.RC, en plus des API dédiées au mode flux, le module de collecte propose des écrans de traitement des versements bureautiques et un connecteur avec API en mode lot.

  Contenu de la gamma :
  -	Versement API Flux (lot)
  -	Versement d’arborescences bureautiques
  -	Suppression des versements envoyés dans le SAE Vitam, automatisable ou non
  -	Création et gestion d’un projet de versement
  -	Amélioration des statuts
  -	Rattachement à une unité archivistique déjà transférée dans le SAE Vitam
  -	Recherche dans le module de collecte
  -	Mise à jour des métadonnées des unités archivistiques
<br>


<br>
  


- la possibilité de créer des profils d'archivage et profils d'unité archivistique dans l'APP Profils documentaires.  
  Cette APP est issue du projet Pastis (Profil d’archivage simple pour traitement de l’information en Seda) mené par le Cines avec le soutien du Siaf.

  Fonctions :
  -	Créer un profil d’archivage
  -	Créer un profil d’unité archivistique
  -	Modifier un profil d’archivage
  -	Modifier un profil d’unité archivistique
  -	Importer et exporter un profil d’archivage en RNG
  -	Importer et exporter un profil d’unité archivistique en JSON
  
  Le profil d’archivage et le profil d’unité archivistique servent à spécifier les métadonnées du SEDA pour un contexte d’archivage donné. Ils déterminent : 
  -	La liste des métadonnées à utiliser parmi le dictionnaire de données SEDA.
  -	Les paramétrages retenus pour ces métadonnées (caardinalité, valeur(s) attendue(s) le cas échéant, etc.)
  -	Des commentaires d’utilisation



La [release note  est publiée](/ressources/RefCourant/Release_notes_6.RC_vdef.pdf), ainsi sur les changelog ([back](https://github.com/ProgrammeVitam/vitam/releases/download/6.rc.1/changelog_vitam.6.rc.1.pdf) et [front](https://github.com/ProgrammeVitam/vitam-ui/releases/download/6.rc.1/changelog_vitamui.6.rc.1.pdf)).

La [documentation en ligne](/pages/documentation/) est à jour et vous trouverez tous les éléments sur cette nouvelle version [ici](/pages/ressources/version_6_RC_1.md). 
_