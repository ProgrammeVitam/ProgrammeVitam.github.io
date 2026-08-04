---
layout: page
title: VaS - Utilisateurs du service
fatherref: VaS
---

<div id="map" style="height: 800px; width: 100%;"></div>

<link rel="stylesheet" href="https://unpkg.com/leaflet@1.9.4/dist/leaflet.css"/>

<script src="https://unpkg.com/leaflet@1.9.4/dist/leaflet.js"></script>

<script>
const map = L.map('map');

L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', {
    attribution: '&copy; OpenStreetMap'
}).addTo(map);

const sites = [

    // ÎLE-DE-FRANCE

    {
        nom: "Ministère de la Culture",
        adresse: "3 rue de Valois, 75001 Paris",
        lat: 48.8646,
        lon: 2.3371
    },
    {
        nom: "Ministère des Affaires Sociales",
        adresse: "14 avenue Duquesne, Paris",
        lat: 48.8567,
        lon: 2.3076
    },
    {
        nom: "Ministère de la Transition écologique",
        adresse: "246 boulevard Saint-Germain, Paris",
        lat: 48.8545,
        lon: 2.3215
    },
    {
        nom: "Ministère de l'Agriculture et de la Souveraineté alimentaire",
        adresse: "78 rue de Varenne, Paris",
        lat: 48.8540,
        lon: 2.3182
    },
    {
        nom: "Ministère de la Justice",
        adresse: "13 place Vendôme, Paris",
        lat: 48.8670,
        lon: 2.3290
    },
    {
        nom: "Ministère de l'Éducation nationale",
        adresse: "110 rue de Grenelle, Paris",
        lat: 48.8560,
        lon: 2.3194
    },
    {
        nom: "Musée du quai Branly",
        adresse: "37 quai Branly, Paris",
        lat: 48.8606,
        lon: 2.2976
    },
    {
        nom: "Société des Grands Projets",
        adresse: "2 Mail de la Petite Espagne, Saint-Denis",
        lat: 48.9180,
        lon: 2.3620
    },
    {
        nom: "Médiathèque du patrimoine et de la photographie",
        adresse: "11 rue du Séminaire de Conflans, Charenton-le-Pont",
        lat: 48.8218,
        lon: 2.4128
    },
    {
        nom: "Communauté d'Agglomération Paris-Vallée de la Marne",
        adresse: "5 cours de l'Arche Guédon, Torcy",
        lat: 48.8503,
        lon: 2.6503
    },
    {
        nom: "Commission nationale des comptes de campagne",
        adresse: "31-35 rue de la Fédération, Paris",
        lat: 48.8500,
        lon: 2.2920
    },
    {
        nom: "Direction Générale de la Gendarmerie Nationale",
        adresse: "4 rue Claude-Bernard, Issy-les-Moulineaux",
        lat: 48.8230,
        lon: 2.2740
    },
    {
        nom: "INHA",
        adresse: "2 rue de Vivienne, Paris",
        lat: 48.8671,
        lon: 2.3394
    },
    {
        nom: "ANSM",
        adresse: "143 boulevard Anatole France, Saint-Denis",
        lat: 48.9360,
        lon: 2.3570
    },
    {
        nom: "ECPAD",
        adresse: "2 à 8 route du Fort, Ivry-sur-Seine",
        lat: 48.8147,
        lon: 2.3868
    },
    {
        nom: "École nationale des ponts et chaussées",
        adresse: "6-8 avenue Blaise Pascal, Marne-la-Vallée",
        lat: 48.8417,
        lon: 2.5874
    },
    {
        nom: "Château de Fontainebleau",
        adresse: "Place Charles-de-Gaulle, Fontainebleau",
        lat: 48.4021,
        lon: 2.7005
    },
    {
        nom: "Ministère des Finances",
        adresse: "139 rue de Bercy, Paris",
        lat: 48.8405,
        lon: 2.3770
    },
    {
        nom: "Archives de Paris",
        adresse: "18 boulevard Sérurier, Paris",
        lat: 48.8762,
        lon: 2.4085
    },

    // FRANCE

    {
        nom: "Conseil départemental du Gard",
        adresse: "2 rue Guillemette, Nîmes",
        lat: 43.8367,
        lon: 4.3601
    },
    {
        nom: "Conseil départemental de l'Hérault",
        adresse: "Mas d'Alco, Montpellier",
        lat: 43.6119,
        lon: 3.8336
    },
    {
        nom: "Conseil départemental du Tarn-et-Garonne",
        adresse: "100 boulevard Hubert Gouze, Montauban",
        lat: 44.0170,
        lon: 1.3540
    },
    {
        nom: "Conseil départemental de la Gironde",
        adresse: "1 Esplanade Charles-de-Gaulle, Bordeaux",
        lat: 44.8378,
        lon: -0.5792
    },
    {
        nom: "Conseil départemental des Bouches-du-Rhône",
        adresse: "52 avenue de Saint-Just, Marseille",
        lat: 43.3117,
        lon: 5.4035
    },
    {
        nom: "Université de Bordeaux",
        adresse: "351 cours de la Libération, Talence",
        lat: 44.8065,
        lon: -0.6058
    },
    {
        nom: "CCI Pays de la Loire",
        adresse: "1 rue Françoise Sagan, Saint-Herblain",
        lat: 47.2158,
        lon: -1.6386
    },
    {
        nom: "Toulouse Métropole",
        adresse: "6 rue René Leduc, Toulouse",
        lat: 43.6045,
        lon: 1.4440
    },
    {
        nom: "Métropole Aix-Marseille-Provence",
        adresse: "58 boulevard Charles-Livon, Marseille",
        lat: 43.2906,
        lon: 5.3605
    },
    {
        nom: "Université de Lille",
        adresse: "42 rue Paul Duez, Lille",
        lat: 50.6297,
        lon: 3.0686
    }

];

const markers = [];

sites.forEach(site => {
    const marker = L.marker([site.lat, site.lon])
        .addTo(map)
        .bindPopup(`
            <b>${site.nom}</b><br>
            ${site.adresse}
        `);

    markers.push(marker);
});

const group = L.featureGroup(markers);
map.fitBounds(group.getBounds(), {
    padding: [40, 40]
});
</script>
