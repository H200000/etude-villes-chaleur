# Les villes de France où l'on a le plus besoin de la climatisation

Classement de **275 villes de France métropolitaine** (Corse comprise) selon le nombre moyen de jours par an où la température maximale atteint **30 °C ou plus**, d'après les normales Météo-France 1991-2020.

- Étude complète, carte et méthode : **https://clim-posee.fr/etude/villes-les-plus-chaudes/**
- Publiée le 10 novembre 2026 par [Clim Posée](https://clim-posee.fr/)

## Fichiers

| Fichier | Contenu |
|---|---|
| [`donnees/villes-les-plus-chaudes-2026.csv`](donnees/villes-les-plus-chaudes-2026.csv) | Une ligne par ville, séparateur `;`, décimales à virgule, UTF-8 avec BOM (s'ouvre tel quel dans Excel) |
| [`donnees/villes-les-plus-chaudes-2026.json`](donnees/villes-les-plus-chaudes-2026.json) | Mêmes données avec les métadonnées (sources, périmètre, conditions de reprise) |
| [`cartes/`](cartes/) | Une carte SVG par région |

Colonnes : rang national et régional, ville, code INSEE, département, région, population municipale, jours par an à 30 °C ou plus, température maximale moyenne de juillet, station Météo-France de référence, distance et altitude de la station, recherches Google mensuelles « climatisation + ville ».

## Les 15 villes les plus chaudes

| Rang | Ville | Département | Jours à 30 °C ou plus par an | Max. moyen en juillet | Station de référence |
|---|---|---|---|---|---|
| 1 | Alès | Gard (30) | 71,2 | 32,5 °C | Saint-Christol-les-Ales (3,7 km) |
| 2 | Draguignan | Var (83) | 70,9 | 32,4 °C | Le Luc (18 km) |
| 3 | Carpentras | Vaucluse (84) | 67 | 32,3 °C | Carpentras (2,3 km) |
| 4 | Aubagne | Bouches-du-Rhône (13) | 60,8 | 31,3 °C | Aubagne (3,5 km) |
| 5 | Nîmes | Gard (30) | 59 | 31,5 °C | Nîmes-Courbessac (5,8 km) |
| 6 | Aix-en-Provence | Bouches-du-Rhône (13) | 55,2 | 31 °C | Aix-en-Provence (3 km) |
| 7 | Orange | Vaucluse (84) | 54,6 | 31,1 °C | Orange (5 km) |
| 8 | Avignon | Vaucluse (84) | 52,7 | 30,8 °C | Pujaut (8,6 km) |
| 9 | Béziers | Hérault (34) | 52,6 | 30,9 °C | Béziers-Courtade (6,6 km) |
| 10 | Marignane | Bouches-du-Rhône (13) | 50,6 | 30,7 °C | Marignane (1,8 km) |
| 10 | Martigues | Bouches-du-Rhône (13) | 50,6 | 30,7 °C | Marignane (14,7 km) |
| 10 | Vitrolles | Bouches-du-Rhône (13) | 50,6 | 30,7 °C | Marignane (4,6 km) |
| 13 | Salon-de-Provence | Bouches-du-Rhône (13) | 50,1 | 30,7 °C | Salon-de-Provence (5,8 km) |
| 14 | Istres | Bouches-du-Rhône (13) | 48,7 | 30,7 °C | Istres (3 km) |
| 15 | Montélimar | Drôme (26) | 42,8 | 29,8 °C | Montélimar (3,1 km) |

## Les 5 villes les plus fraîches

| Rang | Ville | Département | Jours à 30 °C ou plus par an |
|---|---|---|---|
| 271 | Boulogne-sur-Mer | Pas-de-Calais (62) | 1,7 |
| 271 | Dunkerque | Nord (59) | 1,7 |
| 273 | Saint-Brieuc | Côtes-d'Armor (22) | 1,2 |
| 274 | Brest | Finistère (29) | 0,8 |
| 275 | Cherbourg-en-Cotentin | Manche (50) | 0,6 |

## Méthode

1. **Périmètre** : 275 villes de France métropolitaine (Corse comprise) parmi les 300 communes les plus peuplées de France.
2. **Indicateur** : Nombre moyen de jours par an où la température maximale atteint 30 °C ou plus, normales 1991-2020, à la station Météo-France de référence la plus proche de la ville.
3. **Rattachement** : chaque ville est rattachée à la station Météo-France disposant de normales 1991-2020 la plus proche ; la distance et l'altitude de la station sont publiées pour chaque ligne. Les villes trop éloignées d'une station représentative ont été écartées.
4. **Demande** : volumes mensuels moyens de la requête « climatisation + ville » (Google Ads Keyword Planner, octobre 2025 à septembre 2026), arrondis par paliers par Google ; rapportés à 10 000 habitants.

## Sources

- Météo-France, fiches climatologiques, normales 1991-2020 (Licence Ouverte 2.0)
- geo.api.gouv.fr, découpage administratif et population municipale (Etalab, INSEE)
- Google Ads Keyword Planner, moyenne mensuelle de la requête « climatisation + ville », octobre 2025 à septembre 2026, volumes arrondis par paliers

## Licence et reprise

Les données tirées de Météo-France et de l'INSEE sont publiées sous [Licence Ouverte 2.0](https://www.etalab.gouv.fr/licence-ouverte-open-licence/) (Etalab). Les volumes de recherche Google ne sont pas des données ouvertes : seuls des volumes arrondis par ville sont publiés.
Reprise libre avec mention de la source « étude Clim Posée » et lien vers https://clim-posee.fr/etude/villes-les-plus-chaudes/
