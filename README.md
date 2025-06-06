# AINTZANE-PLAA
## Sujet n°2: QGIS

**Outils informatique :**

QGIS

**Objectifs de ce projet informatique (besoin, problèmes à résoudre, attendus...)**

L'objectif de ce projet informatique est de créer une carte de l'Asie Mineure occidentale où seront situées les cité où j'ai pu trouver des mentions des termes "_kyrios_" et "_epitropos_". Ces termes se rapportent aux "tuteur" ou "représentant légal" d'un individu dans le Grèce hellénistique. 

Le problèmes: 
- Les fonds de carte ne sont pas antiques mais contemporains dons les frontières ne correspondent pas.
- Les localisations des régions n'existent techniquement pas actuellement avec des coordonnées GPS donc je devrai indivduellement.

**Etapes de conception et étapes de réalisation techniques:**

J'ai commencé par télécharger un fond de carte de la Turquie et de la Grèce. J'ai hésite à utiliser un fond de carte du monde entier en zoomant sur la zone qui m'intéressait mais le fichier était très lourd. (https://www.geoboundaries.org/globalDownloads.html)

<img width="1437" alt="Capture d’écran 2025-04-08 à 12 28 54" src="https://github.com/user-attachments/assets/3f172a5e-9861-4533-8821-3cfa623aeff5" />

J'ai ensuite exposé grâce à l'exention MMQGIS les coordonnées des cités que j'avais préalablement mise dans un tableur excel en .csv. 

MMQGIS -> Import/export -> Geometry Import from CSV File -> .shp -> Shape ID: Cité antique 

J'ai également ajouté une étiquette simple pour les noms des cités apparaissent. 

<img width="1440" alt="Capture d’écran 2025-04-08 à 12 31 35" src="https://github.com/user-attachments/assets/da9aeafb-1019-4d44-9b84-3718e4f7ba50" />

J'ai ensuite fait : projet -> nouvelle mise en page 

Puis j'ai ajouté manuellement les noms des régions, les mers et les îles manquantes. Enfin, j'ai mis l'échelle, la légende, le titre, la date et mon nom ainsi que la flèche inquant le nord. 


**Jeu de données crée dans le cadre de ce projet informatique:**

| Cité       | Longitude           | Latitute  |
| ------------- |:-------------:| -----:|
| Iasos      | 27.58632 | 37.2779 |
| Milet      | 27.27917      |   37.51278 |
| Didyme | 27.2668129     |    37.3769167 |
| Ephèse    | 27.3393194 | 37.9404455 |
| Ilion    | 26.23909     | 39.95732 |
| Méthymne | 26.2117451      |39.272841 |
| Kymè    | 26.93638888888889 | 38.7591667 |
| Priène     | 27.2959755      | 37.6613182 |
| Magnésie du Ménandre | 27.52722222222222      | 37.8527778 |
| Mylasa     | 27.72749 | 37.2557647 |
| Hyllarima    | 28.3492103 | 37.505003 |
| Cyzique | 27.793055555555558 |40.3986111 |
| Erythrées | 26.480833333333333 | 38.3827778 |
| Pergame    | 27.1844821 | 39.1306225|
| Sélymbria     | 28.2481709   |   $12 |
| Smyrne | 27.02997| 38.23166 |
| Téos | 26.7844611 | 38.1945123 |
| Euromos | 27.6750765 |37.3743507|

**Précisions sur les données du tableur:**

- Les valeurs des coordonnées géographiques sont toutes en degrés décimaux.
- Les noms des lieux viennent de mes recherches.
- Les coordonnées viennent du site: https://www.coordonnees-gps.fr

**Résultats obtenus:**

<img width="1192" alt="Capture d’écran 2025-04-08 à 13 21 12" src="https://github.com/user-attachments/assets/46a03500-de3f-48ca-975a-3debb3128fba" />


**Sources:**

https://www.coordonnees-gps.fr

https://www.geoboundaries.org/globalDownloads.html
