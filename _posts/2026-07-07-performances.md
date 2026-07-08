---
layout: post
title: Tests de performance, point d'étape
---

![Logo du Club utilisateurs](/public/images/Vitam_versements.png)
Le Programme Vitam met en oeuvre régulièrement des campagnes de test mais sans toujours publier les résultats.
En février 2020, les tests effectués mettaient en lumière les [meilleurs résultats avec des entrées lancées en parallèle qu'une entrée très volumineuse unique](https://www.programmevitam.fr/2020/02/25/test_entree/).

Avec le [module de collecte](https://www.programmevitam.fr/vitam-doc/fr/master_9.1.x/sections/module_de_collecte.html), aussi bien utilisable par le [front-office Vitam UI par l'APP dédiée](https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_Collecte_et_preparation_des_versements.pdf) que par l'[API Collect](https://www.programmevitam.fr/ressources/DocCourante/raml/externe/collect.html), l'équipe du Programme Vitam a procédé à de nouveaux tests de performance, en particulier pour répondre à la demande des utilisateurs et ainsi connaître l'existant pour cibler les améliorations.

Ainsi, quelques résultats :

## Avec Vitam UI et l'APP Collecte et préparation des versements

### ZIP d'un jeu de données de 100K et 30,17 GB

- 2 unités archivistiques avec 2 objets volumineux : 20 GB et 8 GB
- 2,5K unités archivistiques avec métadonnées descriptives (date d’enregistrement, tag, description, etc.) et métadonnées de gestion (DUA avec sort final, délai de communicabilité)

#### Vitesse d’envoi 1 GB/s → réseau avec la fibre, sans VPN

**Résultat :** en succès en 19 minutes

#### Vitesse d’envoi: 130 Mb/s → réseau culture

**Résultat :** en succès en 2 h 40 min

#### Enseignement

- Pas de saturation RAM ni CPU observée sur les VM concernées.
- Prise en charge du ZIP dépend entièrement du réseau auquel l'ordinateur de l'utilisateur est raccordé.

### SIP de 10 Go compressé avec objets et manifest 

- SIP de 10 Go compressé et 32 Go décompressé
- contenu identique au cas précédent, avec passage du ZIP à un SIP

#### Comportement

- Etape d'upload de 50 min
- Etape de traitement de 2h (visible dans le journal des opérations pour suivre les différentes étapes du workflow)
- Etape de changement de statut d'Open à validé → génération du SIP en 15 min
- Etape du versement dans le back-office Vitam en 1h30

## Avec l'API Collecte, import back-office

### Import de SIP volumineux

#### Test SIP 10 000 objets

- Durée :  10 min
- Résultat : Succès
- CPU max : 12 %, RAM max : 25%
- Observation : Traitement fluide sans saturation CPU/RAM.

#### Test SIP 50 000 objets

- Durée :  56 min
- Résultat : Succès
- CPU max : 66.2%, RAM max : 79.5%
- Observation : Traitement normal sans saturation CPU/RAM.

#### Test SIP 100 000 objets

- Durée :  2h 9min
- Résultat : Succès
- CPU max : 63.7% , RAM max : 92.8%
- Observation : Traitement normal avec un pic de la RAM.

**De manière générale :**
- pas de time-out
- plus le SIP a d'unités d'archives, plus tu consommes de la RAM

### Import de ZIP volumineux

#### Test ZIP 10 000 objets

- Durée :  55 s
- Résultat : Succès
- CPU max : 0.706%, RAM max : 18%
- Observation : Traitement fluide sans saturation CPU/RAM.

#### Test ZIP 50 000 objets

- Durée :  5 min
- Résultat : Succès
- CPU max : 10.2%, RAM max : 37.0%
- Observation : Traitement fluide sans saturation CPU/RAM.

#### Test ZIP 100 000 objets

- Durée : 7 min
- Résultat : Succès
- CPU max : 12%, RAM max : 71.3%
- Observation : Traitement fluide sans saturation CPU/RAM.

**De manière générale :
- pas de time-out
- plus le ZIP a d'unités d'archives, plus tu consommes de la RAM