## Marché_du_Vin

Le client, le Domaine des Croix, cherche à se lancer sur le marché américain . Il souhaite donc **définir le prix** de ses bouteilles de vin **pour être compétitif sur le marché américain**. Il a récupéré un jeu de données de 130k bouteilles de vin, avec les cépages, les pays et région de production, les millésimes (c'est-à-dire les années de production), ainsi que des notes ("points") et descriptifs d'oenologues (les spécialistes du vin), et le prix moyen en dollars de toutes ces bouteilles sur le marché américain.

**L'objectif sera de faire une présentation de l'analyse du marché, et du prix que l'on conseille de fixer pour les vins du client.** Le client n'est pas data analyst, mais souhaiterait comprendre la démarche. Il faudra donc s'attacher à expliquer comment les prix ont été fixés, sans rentrer dans un trop grand niveau technique, autrement dit : vulgariser.


## Jeux de données
- Dataset des 130k vins : https://github.com/WildCodeSchool/wilddata/raw/main/wine.zip
- Dataset de la bouteille de vin que le client aimerait proposer sur le marché américain : https://raw.githubusercontent.com/WildCodeSchool/wilddata/main/domaine_des_croix.csv


## Livrables attendus
Le client souhaite une présentation qui contiendra a minima ces éléments :
- Rappel du contexte et de la problématique
- Analyse exploratoire des données
- Méthodologie, outils et langages utilisés
- Présentation de la partie technique et du code créé, si code il y a, pour cette analyse
- le tableau de bord contient des graphiques
- le tableau de bord contient au moins une visualisation de données interactive
- le tableau de bord contient au moins une carte représentant des informations géographiques
- le tableau de bord contient au moins un tableau croisé
- l'ensemble des graphiques et visuels doivent être lisible par tous (prise en compte des personne en situation de handicap visuel)
- Réponse à la question métier : proposition de prix ou de fourchette de prix au client pour être correctement positionné face à la concurrence sur le marché américain

## Analyse du marché
Le Domaine des Croix souhaiterait une analyse descriptive du marché du vin. Il faut donc réaliser un ensemble de dataviz. On peut intégrer dans le tableau de bord:
- la répartition du nombre de vins par pays
- les pays qui ont les meilleures notes
- les moyennes de notes par cépage
- la répartition par décile
- etc...

## Analyse comparative

L'objectif ici sera de comparer chacun des vins du client par rapport à ses concurrents sur le marché. Par exemple, comparer les tarifs pratiqués pour les vins français, puis de plus en plus précisément, les vins de Bourgogne puisque notre client est en Bourgogne, puis les Pinot Noir bourguignons de la même année.

## Proposition de valeur

Avec le tableau de bord que nous lui avons fourni, le client a une idée précise de ses concurrents. Faire une proposition de prix en fonction de sa volonté de positionnement (par exemple : "si vous souhaitez vous positionner sur le haut de gamme, les 25% les plus chers de vos concurrents sont à ce tarif, nous vous conseillons donc de vous aligner sur ce prix").

## Qualité esthétique du tableau de bord

Essayer de garder un oeil critique et visuel sur le tableau de bord. La forme compte autant que le fond pour le client qui n'est pas data analyst, penser donc à "vendre" notre analyse. Par exemple, avec des couleurs s'inspirant du milieu vinicole, des dataviz originales, etc...
