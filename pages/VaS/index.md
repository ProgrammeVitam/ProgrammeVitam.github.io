---
layout: page
title: Vitam accessible en service (VaS)
fatherref: VaS
level: page
---

![Logos](/public/images/Logo_dev_provisoire.PNG)
> Cette page vous présente Vitam accessible en service.

* [L'offre VaS](#offre)
* [Les fonctionnalités de VaS](#fonctionnalites)
* [Historique du projet](#historique)
* [Comment préparer son usage du service ?](#utiliser)
* [Quels sont les tarifs ?](#tarif)
* [Gouvernance](#gouvernance)
* [Les utilisateurs actuels](#utilisateurs)
* [Documents de présentation](#documents)

[Télécharger le document de présentation](/ressources/RefCourant/VaS_flyer_202102_bd.pdf)

![Logos](/public/images/vas-schema-v2_51812355.png)


# L'offre VaS <a name="offre"></a>

## Notre mission
 
Organiser, de manière sécurisée, pérenne et souveraine la conservation et la communication des données, issues d’applications, de la bureautique, de messageries, tout en respectant la législation et les besoins archivistiques.

## Vos enjeux

- conserver vos données et y accéder
- respecter la réglementation et répondre aux exigences juridiques
- optimiser les stockages et gagner de la place sur les serveurs
- réduire vos difficultés organisationnelles et gagner du temps
- mutualiser les coûts

![alt text](/public/images/VaS_details.PNG)

## Pourquoi recourir à VaS ?

- Pour archiver en toute sécurité ses données sur une offre de l'Etat
- Pour accéder à tout moment à ses documents
- Pour bénéficier d'une interface pensée par et pour les archivistes
- Pour disposer de l'hébergement, de la maintenance, de l'exploitation de la plateforme sans gérer l'installation et la maintenance
- Pour profiter d'un accompagnement fonctionnel et technique riche de l'expérience Vitam
- Pour faciliter l'archivage numérique définitif aux Archives nationales

## Les + de l'offre VaS

- Implication et soutien de l'Etat
- Cloud souverain de l'Etat
- Compétitivité financière
- Interface homme-machine simple d'utilisation et conçu en UX Design
- Enrichissement des fonctionnalités en continu 
- Ecosystème Vitam et son club utilisateurs

# Les fonctionnalités de VaS <a name="fonctionnalites"></a>

![alt text](/public/images/vas_schema.png)

## Fonctionnalités métier

- Déposer sur la plateforme un dossier d'archives numériques
- Verser des données numériques directement issues d'une application tierce
- Contrôler à l'entrée la conformité de son versement
- Créer une arborescence et y intégrer ses versements
- Modifier  les métadonnées
- Stocker et indexer les archives et leurs métadonnées
- Calculer les échéances des règles de gestion
- Gérer les stocks et éliminer les archives dont la DUA est échue
- Créer des profils d'utilisateurs et gérer leurs droits d'accès et de modification dans l'application
- Rechercher dans les arborescences et les archives conservées, les consulter et les télécharger en fonction de ses droits
- Tracer toutes les actions qui ont lieu dans le système, et générer des certificats (valeur probante, intégrité)
- Auditer le système et les fonds existants

## Caractéristiques techniques

- Données stockées sur des serveurs de l’Etat (Cercle 1 du Cloud de l’Etat)
- Infrastructure mutualisée
- Equipe d’exploitation dédiée (taux de disponibilité garanti à ce stade à 98% en heures ouvrées, en amélioration continue)
- Redondance sur deux sites (garantie de non-perte de données)
- Élasticité (offre qui s'adapte à la demande)
- Centralisation de l'exploitation et de la maintenance de la plateforme
- Centralisation des mises à jour logicielles et de sécurité

# Historique du projet VaS <a name="historique"></a>

Courant 2019, le ministère de la Culture et les ministères de la Transition écologique et solidaire, et de la Cohésion des territoires et des Relations avec les collectivités territoriales ont signé une convention de service pour le projet "Vitam as a Service". 

Devenu depuis <i>Vitam accessible en service</i> (VaS), ce projet soutenu également par la DINum et le Siaf visait dans sa première phase à produire un produit minimum viable (MVP) offrant des fonctionnalités de versement et de gestion des archives pour les archivistes. 

À l'origine de cette initiative se trouve le besoin des ministères d'avoir une solution dédiée pour la gestion de leur archivage intermédiaire, besoin exprimé également par plusieurs opérateurs – partenaires du Programme Vitam. 

S'appuyant sur la réutilisation de la solution logicielle Vitam, le projet offre une **infrastructure interministérielle mutualisée avec un front-office générique, appelé Vitam UI**.

## En s'appuyant sur une initiative de partenaires…

Les travaux de réflexion ont été entamés en s'appuyant sur l'initiative **Vitam UI (pour Interface utilisateurs)** et en y participant.   
Cette dernière est portée depuis 2019 par deux partenaires du Programme Vitam, le CEA et le CINES, rejoints par Locarchives - Xelians, qui a déployé une offre d'archivage à partir de la solution logicielle Vitam. 
Ensemble, ils ont listé les fonctionnalités nécessaires pour la gestion des archives en front-office, les ont priorisées et ont commencé les développements.   
Les contributions à Vitam UI seront reversées au Programme, en Open Source (licence Cecill-C1), permettant de renforcer encore l’axe directionnel fort du Programme depuis l’origine, soit la diffusion et la réutilisation la plus large possible.

## ...pour proposer rapidement un Produit minimum viable (MVP)…

La phase 1 du projet VaS, extension du Programme Vitam, a débuté en même temps que sa phase maintenance et amélioration continue.   
Une comitologie propre a été mise en place, issue du fonctionnement du Programme Vitam, avec un comité de direction, un comité de pilotage et une cellule d’urgence, créée pour agir en cas de problème majeur lorsque les mises en production seront effectives. 

![alt text](/public/images/202401_gouvernance_VaS.jpg)

La première phase a abouti à un MVP fin 2020 contenant les fonctionnalités socles de versements, mais aussi de gestion et d’accès aux archives par les archivistes. 


![alt text](/public/images/Vas_architecture_globale.jpg)

## … avant d’aboutir à une offre de service plus large !

Une phase 2 démarre ensuite.   
Aux porteurs initiaux du projet s’ajoutent de nouveaux ministères, dont certains, comme les Ministères sociaux, ont embarqué dès la phase 1 dans les réflexions et les échanges permettant l’acculturation de tous au projet, au Programme Vitam, aux méthodes, etc.   
Cette deuxième étape a été l’occasion de pousser les fonctionnalités développées en phase 1, mais aussi d’ajouter des fonctionnalités qui ont pu être jugées non prioritaires au début, tout en gardant en objectif le versement dans VaS mais également le reversement dans la plate-forme des Archives nationales. 

À termes, d’autres ministères, en plus des porteurs en phases 1 et 2, pourront utiliser ce service ainsi que les organisations publiques. 
Le modèle économique repose sur la répartition des coûts entre tous les utilisateurs.


# Comment préparer son usage du service ?<a name="utiliser"></a>

* Contacter son service d'archives et/ou le service responsable du contrôle scientifique et technique sur ses archives

* [Contacter l'équipe VaS](mailto:contact@programmevitam.fr)

* Préparer les référentiels (services agents, règles de gestion, arbres et plans, etc.) et former les utilisateurs

* Lister les données et flux prioritaires et estimer :

	* Reprise de données :

		* poids global + nombre de documents à archiver présents sur les serveurs

		* poids global + nombre de documents à archiver

	* Prévision des entrées :

		* poids global + nombre de documents estimé pour les archives versées manuellement dans le système sur les deux prochaines années

		* poids global + nombre de documents estimé en flux pour le versement

* Vérifier son accès au RIE et si besoin évaluer le débit nécessaire selon les données et flux priorisés

* Préparer les versements

* Evaluer vos moyens de coopération : personnes ressources, temps disponibles pour participer au projet VaS, partage possible d'expériences, de livrables, etc.

![alt text](/public/images/VaS_coopérants.JPG)

# Quels sont les tarifs ? <a name="tarif"></a>

Le budget est réparti entre tous les utilisateurs selon l'usage.  
En fin d'année, une estimation de l'usage sur l'année à venir permet de chiffrer la participation de chaque utilisateur.  
Une régularisation selon l'usage réellement constaté sera faite en fin d'année.

Quelques chiffres malgré tout :
- budget global du service pour 2022 et 2023 : 1 430 000€
- prix de l'usage de base : 10 000€ l'année pour 20 000 à 22 000 archives et moins d'1 To
- exemple 1 : 73 000 archives et 6 133 Go pour 30 000€ l'année
- exemple 2 : 248 000 archives et 1,88 To pour 99 000€ l'année
- exemple 3 : 1 million d'archives pour 317 000€ et le coût selon les To versés

Le plus simple ? [Nous contacter](mailto:contact@programmevitam.fr) pour un dialogue sur le modèle économique, vos besoins et une prévision financière sur plusieurs années !

# La gouvernance de VaS <a name="gouvernance"></a>

La gouvernance est mutualisée, associant les ministères porteurs initiaux et ceux qui ont rejoint le projet et les utilisateurs (collectivités publiques ou opérateurs de l'Etat) représentés  par 2 organisations élues en assemblée des utilisateurs.

![alt text](/public/images/VaS_gouvernance.jpg)

# Les utilisateurs actuels <a name="utilisateurs"></a>

![alt text](/public/images/VaS_utilisateurs.jpg)

# Documents de présentation <a name="documents"></a>

- Téléchargez le [flyer de présentation](/ressources/RefCourant/VaS_flyer_202102_bd.pdf)
- Téléchargez les [informations souscripteurs](/ressources/RefCourant/vas-souscripteur_3.pdf)
- Téléchargez les [pré-requis](/ressources/RefCourant/vas-prerequis.pdf)

<!DOCTYPE html>
<html>
<head>
    
    <meta http-equiv="content-type" content="text/html; charset=UTF-8" />
    <script src="https://cdn.jsdelivr.net/npm/leaflet@1.9.3/dist/leaflet.js"></script>
    <script src="https://code.jquery.com/jquery-3.7.1.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/js/bootstrap.bundle.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.js"></script>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/leaflet@1.9.3/dist/leaflet.css"/>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/css/bootstrap.min.css"/>
    <link rel="stylesheet" href="https://netdna.bootstrapcdn.com/bootstrap/3.0.0/css/bootstrap-glyphicons.css"/>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.2.0/css/all.min.css"/>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.css"/>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/python-visualization/folium/folium/templates/leaflet.awesome.rotate.min.css"/>
    
            <meta name="viewport" content="width=device-width,
                initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
            <style>
                #map_a25760613726081d23ced48c931c4987 {
                    position: relative;
                    width: 100.0%;
                    height: 100.0%;
                    left: 0.0%;
                    top: 0.0%;
                }
                .leaflet-container { font-size: 1rem; }
            </style>

            <style>html, body {
                width: 100%;
                height: 100%;
                margin: 0;
                padding: 0;
            }
            </style>

            <style>#map {
                position:absolute;
                top:0;
                bottom:0;
                right:0;
                left:0;
                }
            </style>

            <script>
                L_NO_TOUCH = false;
                L_DISABLE_3D = false;
            </script>

        
</head>
<body>
    
    
            <div class="folium-map" id="map_a25760613726081d23ced48c931c4987" ></div>
        
</body>
<script>
    
    
            var map_a25760613726081d23ced48c931c4987 = L.map(
                "map_a25760613726081d23ced48c931c4987",
                {
                    center: [48.86, 2.35],
                    crs: L.CRS.EPSG3857,
                    ...{
  "zoom": 10,
  "zoomControl": true,
  "preferCanvas": false,
}

                }
            );

            

        
    
            var tile_layer_eb7abf08725f0bbfc1ab58993919092b = L.tileLayer(
                "https://tile.openstreetmap.org/{z}/{x}/{y}.png",
                {
  "minZoom": 0,
  "maxZoom": 19,
  "maxNativeZoom": 19,
  "noWrap": false,
  "attribution": "\u0026copy; \u003ca href=\"https://www.openstreetmap.org/copyright\"\u003eOpenStreetMap\u003c/a\u003e contributors",
  "subdomains": "abc",
  "detectRetina": false,
  "tms": false,
  "opacity": 1,
}

            );
        
    
            tile_layer_eb7abf08725f0bbfc1ab58993919092b.addTo(map_a25760613726081d23ced48c931c4987);
        
    
            var marker_df7f443729c9dffdaa520e6956c022c6 = L.marker(
                [48.8647, 2.3363],
                {
}
            ).addTo(map_a25760613726081d23ced48c931c4987);
        
    
        var popup_1eb4b36cce4ee07ec6256f8c75af41c1 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_e1ba5cb37525e649a12ff8a3c2b6da3e = $(`<div id="html_e1ba5cb37525e649a12ff8a3c2b6da3e" style="width: 100.0%; height: 100.0%;">Ministère de la Culture</div>`)[0];
                popup_1eb4b36cce4ee07ec6256f8c75af41c1.setContent(html_e1ba5cb37525e649a12ff8a3c2b6da3e);
            
        

        marker_df7f443729c9dffdaa520e6956c022c6.bindPopup(popup_1eb4b36cce4ee07ec6256f8c75af41c1)
        ;

        
    
    
            var marker_563f0069703aa81c9d6027f3f2fff9c0 = L.marker(
                [48.851, 2.312],
                {
}
            ).addTo(map_a25760613726081d23ced48c931c4987);
        
    
        var popup_9776b8bcbaf8838268ee9b051cf5ab10 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_dc30f78eef70fb27349619803ec3e313 = $(`<div id="html_dc30f78eef70fb27349619803ec3e313" style="width: 100.0%; height: 100.0%;">Ministère des Affaires Sociales</div>`)[0];
                popup_9776b8bcbaf8838268ee9b051cf5ab10.setContent(html_dc30f78eef70fb27349619803ec3e313);
            
        

        marker_563f0069703aa81c9d6027f3f2fff9c0.bindPopup(popup_9776b8bcbaf8838268ee9b051cf5ab10)
        ;

        
    
    
            var marker_9e7f4800d7b6366b39aa8b9bf77a7594 = L.marker(
                [48.8546, 2.321],
                {
}
            ).addTo(map_a25760613726081d23ced48c931c4987);
        
    
        var popup_aae17e003f5dbc9ac489193a4adf2059 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_c7fd7c1f8cd7a62eec43bf490f041dd1 = $(`<div id="html_c7fd7c1f8cd7a62eec43bf490f041dd1" style="width: 100.0%; height: 100.0%;">Ministère de la Transition écologique</div>`)[0];
                popup_aae17e003f5dbc9ac489193a4adf2059.setContent(html_c7fd7c1f8cd7a62eec43bf490f041dd1);
            
        

        marker_9e7f4800d7b6366b39aa8b9bf77a7594.bindPopup(popup_aae17e003f5dbc9ac489193a4adf2059)
        ;

        
    
    
            var marker_98d914b9fce9345a86babb6c1e6b6b13 = L.marker(
                [48.853, 2.316],
                {
}
            ).addTo(map_a25760613726081d23ced48c931c4987);
        
    
        var popup_2ac03c83b5894893cbf1ddfd3dade19e = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_ac2e06877e2aad8b7edec90fd97905c8 = $(`<div id="html_ac2e06877e2aad8b7edec90fd97905c8" style="width: 100.0%; height: 100.0%;">Ministère de l'Agriculture</div>`)[0];
                popup_2ac03c83b5894893cbf1ddfd3dade19e.setContent(html_ac2e06877e2aad8b7edec90fd97905c8);
            
        

        marker_98d914b9fce9345a86babb6c1e6b6b13.bindPopup(popup_2ac03c83b5894893cbf1ddfd3dade19e)
        ;

        
    
    
            var marker_4b7ed3f983569188c3c20127a691d7a8 = L.marker(
                [48.8675, 2.329],
                {
}
            ).addTo(map_a25760613726081d23ced48c931c4987);
        
    
        var popup_db5aa890d8ddf7222b888e9ba84fa3ac = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_ee867c94c6ee6df036a045f9ea9b67fb = $(`<div id="html_ee867c94c6ee6df036a045f9ea9b67fb" style="width: 100.0%; height: 100.0%;">Ministère de la Justice</div>`)[0];
                popup_db5aa890d8ddf7222b888e9ba84fa3ac.setContent(html_ee867c94c6ee6df036a045f9ea9b67fb);
            
        

        marker_4b7ed3f983569188c3c20127a691d7a8.bindPopup(popup_db5aa890d8ddf7222b888e9ba84fa3ac)
        ;

        
    
    
            var marker_ef9b0fac00f3d2d248ba50cc12da9232 = L.marker(
                [48.8558, 2.3205],
                {
}
            ).addTo(map_a25760613726081d23ced48c931c4987);
        
    
        var popup_e52f76584d8cfeb1281c8119ed289579 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_f13c8c40665a1df277a6958b1d7d8370 = $(`<div id="html_f13c8c40665a1df277a6958b1d7d8370" style="width: 100.0%; height: 100.0%;">Ministère de l'Education nationale</div>`)[0];
                popup_e52f76584d8cfeb1281c8119ed289579.setContent(html_f13c8c40665a1df277a6958b1d7d8370);
            
        

        marker_ef9b0fac00f3d2d248ba50cc12da9232.bindPopup(popup_e52f76584d8cfeb1281c8119ed289579)
        ;

        
    
    
            var marker_0247ea9f3e9343b26c77e8122bff2bfb = L.marker(
                [48.8606, 2.2976],
                {
}
            ).addTo(map_a25760613726081d23ced48c931c4987);
        
    
        var popup_868a4532c39db614da58ee17a748e304 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_f9f94afcdc47e6d339f0d58f4437bacd = $(`<div id="html_f9f94afcdc47e6d339f0d58f4437bacd" style="width: 100.0%; height: 100.0%;">Musée du quai Branly</div>`)[0];
                popup_868a4532c39db614da58ee17a748e304.setContent(html_f9f94afcdc47e6d339f0d58f4437bacd);
            
        

        marker_0247ea9f3e9343b26c77e8122bff2bfb.bindPopup(popup_868a4532c39db614da58ee17a748e304)
        ;

        
    
    
            var marker_4280f4cb5f452ea7f2183a672680dca5 = L.marker(
                [48.918, 2.362],
                {
}
            ).addTo(map_a25760613726081d23ced48c931c4987);
        
    
        var popup_498068da66ccd47d9a0d21099bfe22ac = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_1b58d261408184731b0f74959839c2ee = $(`<div id="html_1b58d261408184731b0f74959839c2ee" style="width: 100.0%; height: 100.0%;">Société des Grands Projets</div>`)[0];
                popup_498068da66ccd47d9a0d21099bfe22ac.setContent(html_1b58d261408184731b0f74959839c2ee);
            
        

        marker_4280f4cb5f452ea7f2183a672680dca5.bindPopup(popup_498068da66ccd47d9a0d21099bfe22ac)
        ;

        
    
    
            var marker_f279bd16d8ae958e401c3f7075bc1f99 = L.marker(
                [48.821, 2.414],
                {
}
            ).addTo(map_a25760613726081d23ced48c931c4987);
        
    
        var popup_cac1f2d00ceaadd4251e24fbd39953c7 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_cc851c23eae523553f29818298b9ac6a = $(`<div id="html_cc851c23eae523553f29818298b9ac6a" style="width: 100.0%; height: 100.0%;">Médiathèque du patrimoine et de la photographie</div>`)[0];
                popup_cac1f2d00ceaadd4251e24fbd39953c7.setContent(html_cc851c23eae523553f29818298b9ac6a);
            
        

        marker_f279bd16d8ae958e401c3f7075bc1f99.bindPopup(popup_cac1f2d00ceaadd4251e24fbd39953c7)
        ;

        
    
    
            var marker_43eca033d841712a633d80321e5f9a1c = L.marker(
                [48.85, 2.65],
                {
}
            ).addTo(map_a25760613726081d23ced48c931c4987);
        
    
        var popup_854977b2cf0d2d3b58dcef51cf20705d = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_a62c828bac103850d55a783bcaa7936a = $(`<div id="html_a62c828bac103850d55a783bcaa7936a" style="width: 100.0%; height: 100.0%;">CA Paris-Vallée de la Marne</div>`)[0];
                popup_854977b2cf0d2d3b58dcef51cf20705d.setContent(html_a62c828bac103850d55a783bcaa7936a);
            
        

        marker_43eca033d841712a633d80321e5f9a1c.bindPopup(popup_854977b2cf0d2d3b58dcef51cf20705d)
        ;

        
    
    
            var marker_dea7f99e4e1720b1b649ef9585ec8c3a = L.marker(
                [48.8502, 2.292],
                {
}
            ).addTo(map_a25760613726081d23ced48c931c4987);
        
    
        var popup_9b6ced67083dbac4879e580ac3064bb1 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_be674eb0859ecbd050d01a44eae3616e = $(`<div id="html_be674eb0859ecbd050d01a44eae3616e" style="width: 100.0%; height: 100.0%;">CNCCFP</div>`)[0];
                popup_9b6ced67083dbac4879e580ac3064bb1.setContent(html_be674eb0859ecbd050d01a44eae3616e);
            
        

        marker_dea7f99e4e1720b1b649ef9585ec8c3a.bindPopup(popup_9b6ced67083dbac4879e580ac3064bb1)
        ;

        
    
    
            var marker_bb13de3175e0774d4a2d88b290b25851 = L.marker(
                [48.823, 2.274],
                {
}
            ).addTo(map_a25760613726081d23ced48c931c4987);
        
    
        var popup_181a1e41f7f0e68e6b31d60ad223e7b5 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_fc52cfa758c9cb9d66003fddccf5b58e = $(`<div id="html_fc52cfa758c9cb9d66003fddccf5b58e" style="width: 100.0%; height: 100.0%;">DGGN</div>`)[0];
                popup_181a1e41f7f0e68e6b31d60ad223e7b5.setContent(html_fc52cfa758c9cb9d66003fddccf5b58e);
            
        

        marker_bb13de3175e0774d4a2d88b290b25851.bindPopup(popup_181a1e41f7f0e68e6b31d60ad223e7b5)
        ;

        
    
    
            var marker_f8ee78c9e8bd63dd239e4cfcdf72d5bb = L.marker(
                [48.8665, 2.3398],
                {
}
            ).addTo(map_a25760613726081d23ced48c931c4987);
        
    
        var popup_4add8dc87b3e290ba7b9273435f6fce6 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_8320f9a11fca4a16ad44af2c395abd51 = $(`<div id="html_8320f9a11fca4a16ad44af2c395abd51" style="width: 100.0%; height: 100.0%;">INHA</div>`)[0];
                popup_4add8dc87b3e290ba7b9273435f6fce6.setContent(html_8320f9a11fca4a16ad44af2c395abd51);
            
        

        marker_f8ee78c9e8bd63dd239e4cfcdf72d5bb.bindPopup(popup_4add8dc87b3e290ba7b9273435f6fce6)
        ;

        
    
    
            var marker_b8e4cabc62521e87249f9ed47f0fec52 = L.marker(
                [48.936, 2.357],
                {
}
            ).addTo(map_a25760613726081d23ced48c931c4987);
        
    
        var popup_31466f79bdd9b7b7959dd42e37c945f5 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_1f77fe0310a4271be02c612bd453c41a = $(`<div id="html_1f77fe0310a4271be02c612bd453c41a" style="width: 100.0%; height: 100.0%;">ANSM</div>`)[0];
                popup_31466f79bdd9b7b7959dd42e37c945f5.setContent(html_1f77fe0310a4271be02c612bd453c41a);
            
        

        marker_b8e4cabc62521e87249f9ed47f0fec52.bindPopup(popup_31466f79bdd9b7b7959dd42e37c945f5)
        ;

        
    
    
            var marker_6828e24923286a4078c34d2b69acd986 = L.marker(
                [48.815, 2.386],
                {
}
            ).addTo(map_a25760613726081d23ced48c931c4987);
        
    
        var popup_3d17b26087bfb20e446907af04b433ab = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_6d6fc2e7b6e1c9236fcd9de2dae09e83 = $(`<div id="html_6d6fc2e7b6e1c9236fcd9de2dae09e83" style="width: 100.0%; height: 100.0%;">ECPAD</div>`)[0];
                popup_3d17b26087bfb20e446907af04b433ab.setContent(html_6d6fc2e7b6e1c9236fcd9de2dae09e83);
            
        

        marker_6828e24923286a4078c34d2b69acd986.bindPopup(popup_3d17b26087bfb20e446907af04b433ab)
        ;

        
    
    
            var marker_7d7c816269a4234bdd1c6ad30c7fe92e = L.marker(
                [48.841, 2.587],
                {
}
            ).addTo(map_a25760613726081d23ced48c931c4987);
        
    
        var popup_403dcb34ddc58e89c62efe5c9f29e800 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_65e4df8c1294b4de9a91b5c8c8c0fe5e = $(`<div id="html_65e4df8c1294b4de9a91b5c8c8c0fe5e" style="width: 100.0%; height: 100.0%;">ENPC</div>`)[0];
                popup_403dcb34ddc58e89c62efe5c9f29e800.setContent(html_65e4df8c1294b4de9a91b5c8c8c0fe5e);
            
        

        marker_7d7c816269a4234bdd1c6ad30c7fe92e.bindPopup(popup_403dcb34ddc58e89c62efe5c9f29e800)
        ;

        
    
    
            var marker_246cdc205d560f5585b55749f99237de = L.marker(
                [48.402, 2.701],
                {
}
            ).addTo(map_a25760613726081d23ced48c931c4987);
        
    
        var popup_321392c89a7ead225de8bb48daf377c1 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_332a87eba7536f103e09356784a9d889 = $(`<div id="html_332a87eba7536f103e09356784a9d889" style="width: 100.0%; height: 100.0%;">Château de Fontainebleau</div>`)[0];
                popup_321392c89a7ead225de8bb48daf377c1.setContent(html_332a87eba7536f103e09356784a9d889);
            
        

        marker_246cdc205d560f5585b55749f99237de.bindPopup(popup_321392c89a7ead225de8bb48daf377c1)
        ;

        
    
    
            var marker_d8625e11f28cb97e39820e43d76f9529 = L.marker(
                [48.8402, 2.377],
                {
}
            ).addTo(map_a25760613726081d23ced48c931c4987);
        
    
        var popup_ae1f80f67e3de068791c3d4f9e4168e7 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_7cdf346fd0c0309f3c89d846deb60268 = $(`<div id="html_7cdf346fd0c0309f3c89d846deb60268" style="width: 100.0%; height: 100.0%;">Ministère des Finances</div>`)[0];
                popup_ae1f80f67e3de068791c3d4f9e4168e7.setContent(html_7cdf346fd0c0309f3c89d846deb60268);
            
        

        marker_d8625e11f28cb97e39820e43d76f9529.bindPopup(popup_ae1f80f67e3de068791c3d4f9e4168e7)
        ;

        
    
</script>
</html>