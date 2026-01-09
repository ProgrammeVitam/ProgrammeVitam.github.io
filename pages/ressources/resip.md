---
layout: page
title: ReSIP
fatherref: ressources
---

> Cette page présente le générateur ReSIP (version 2.9.0 - hiver 2025-2026).

![ReSIP_logo](/public/images/ReSIP.jpg)

## ReSIP

L’application ReSIP, basée sur la bibliothèque sedalib, permet de construire et manipuler des structures arborescentes d’archives, d’en éditer les métadonnées, de les importer  et exporter sous la forme de SIP, sous la forme de hiérarchie disque ou encore sous forme csv pour les plans de classement.

L’application est constituée d’un fichier exécutable portable (qui ne nécessite pas d’installation) ReSip.exe qui permet de lancer directement par double clic l’application en mode graphique. 

Cet exécutable peut aussi être utilisé en ligne de commande (voir paragraphe Ligne de commande) ou via le script ReSip.bat. Dans ce dernier cas un drag and drop d’une arborescence de fichier génère un SIP correspondant. Enfin un .jar est fourni pour permettre l'usage sur d'autres systèmes que Windows.

ReSIP présente de manière explicite les contenus XML, et nécessite donc une certaine connaissance du standard SEDA 2.1, 2.2 ainsi que 2.3. Celui-ci est consultable sur le site du [SIAF](https://francearchives.fr/seda/).

Pour comprendre l’essentiel, on visera notamment la documentation technique des:
*	**manifest du SIP (message ArchiveTransfer)**  qui au plus haut niveau définit  les métadonnées globales du versement 
*	**DescriptiveMetadata** qui contient la structure des archives et des métadonnées
*	**ArchiveUnit** qui contient toutes les informations de structure et de métadonnées d’une  unité d’archives
*	**Management** qui contient toutes les informations de gestion d’une unité d’archives
*	**Content** qui contient toutes les métadonnées descriptives d’une unité d’archives

Sont mis à dispostion :


* **le paquet d'installation sous Windows**  
    Il s'agit d'un conteneur zip à décompresser en local et dont l'exécution nécessite la présence de java 8 à 11 (non testé au delà) sur le poste ou à défaut une machine java 8 à 11 dans le répertoire "jre" au niveau de l'exécutable. 

    Il est accessible **[ici](https://download.programmevitam.fr/resip/2.9.0/resip-2.9.0-standalone.zip)**.

    >A noter: le fichier .jar utilisable sous Linux est disponible [ici](https://download.programmevitam.fr/resip/2.9.0/sedatools-package-2.9.0.tar.gz).

* **un manuel utilisateur**  
    La documentation **ReSIP** décrit les fonctions de l'outil ReSIP ainsi que son utilisation simple et avancée et peut être consultée en suivant ce [lien](https://www.programmevitam.fr/vitam-doc/fr/master_9.0.x/sections/resip.html).
    Une [FAQ est également en construction et disponible ici](https://www.programmevitam.fr/vitam-doc/fr/master_9.0.x/sections/resip_faq.html).

* **un jeu de tests**  
    Il contient des hiérarchies disque, SIP, DIP, csv... et toute une série de fichiers d'exemples importables et manipulable avec ReSIP.

    Il est accessible [ici](https://www.programmevitam.fr/ressources/Doc3.14.2/autres/fonctionnel/Tests%20ReSIP.zip).

* **le code développé**  
    Il est accessible dans le dépot GitHub avec la bibliothèque sedalib [SedaTools](https://github.com/ProgrammeVitam/sedatools).

## ReSIP version 2.9.0 (hiver 2025-2026)

### Ajout de fonctionnalités 

#### Montée de version du SEDA 2.3 

- Import et export d’un manifest en SEDA 2.3 
- Ajout des métadonnées relatives à la version 2.3 du SEDA : bloc PersistentIdentifier (Identifiant pérenne) et bloc SigningInformation (Information sur la signature) 
- Contrôle de conformité en SEDA 2.3 
- Amélioration de la prise en compte des informations de date (millisecondes et fuseaux horaires). 

#### Montée de version de DROID 

#### Améliorations dans les fonctionnalités d’extraction des mails 

- Amélioration des performances 
- Prise en charge des mails signés 
- Analyse MIME pour les formats de boîte à lettre 
- Internationalisation de l’interface utilisateur 

 Consulter la [release note de ReSIP version 2.9.0](/ressources/RefCourant/Release notes_RESIP_2_9_0.pdf)

Evolution techniques 

Montée de version COTS et des librairies : Passage en Java 17, Montée de version de DROID, Utilisation d’Apache Tika. 

## ReSIP version 2.8.0 (été 2024)

Mise à disposition d’un paquet ReSIP embarquant une JDK Java 11.


## ReSIP version 2.7.0 (automne 2023)

### Ajout de fonctionnalités
* Import :  
    - Import possible de SIP formalisé en SEDA 2.1 et en SEDA 2.2  
    - Import d’un DIP full dans ReSIP  
* Traitement :  
    - Compaction d’arborescences configurable (mode expérimental)  
* Export :  
    - Export de SIP avec version du SEDA paramétrable dans les préférences (choix possibles : SEDA 2.1 et SEDA 2.2)  
    - Intégration des colonnes ID et ParentID dans l’export CSV  
    - Possibilité de faire de l’import/export de fichier CSV en vue de faire des modifications en masse depuis le fichier CSV  
    - Prise en compte des caractères spéciaux et non-substitution des apostrophes par des tirets du bas dans la colonne File d’un export CSV

### Correction
- Dans les chaînes multi-lignes, lorsqu'elles existent, 2 espaces étaient supprimés à partir du début de la deuxième ligne, en début de ligne et en fin de ligne.

### Traitements
- Dézippage des containers de type ZIP depuis une messagerie importée dans ReSIP (identification par le PUID et non plus par le TypeMime)
- Conversion de mails inclus dans une arborescence bureautique

### Sécurité
- Montée de version de DROID : version 6.5.2. (Correction de la faille de sécurité log4j)
- Montée de version de la JDK : version 11