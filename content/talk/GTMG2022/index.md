---
abstract: >-
La construction d'opérations de modélisation géométriques est une tâche souvent longue et fastidieuse.
Même si l'implémentation d'une opération peut s'avérer difficile, il est en revanche relativement simple de l'intuiter à partir d'un objet de départ et de l'objet cible, si ces deux derniers sont donnés.

On propose donc une méthode d'inférence d'opérations à partir d'un exemple représentatif.

On se place dans le domaine de la modélisation géométrique à base topologique pour séparer la reconstruction topologique de l'opération et sa partie géométrique.

On réalise l'inférence d'opérations dans Jerboa, une plateforme de conception de modeleurs qui exploite les cartes généralisées comme structure topologique et les règles de transformations de graphes comme modèle pour les opérations.
Les informations géométriques sont ajoutées sur la structure topologique à l'aide de fonction de plongement qui associe une valeur géométrique à chaque cellule. Ainsi, on associe une position 3D à chaque sommet topologique, etc. 

On infère la partie topologique de l'opération à l'aide d'un algorithme de parcours de graphe avec recherche de symétries. 

On propose d'inférer les calculs géométriques liés à la position des sommets. 

Plus précisément, on suppose que les nouvelles positions géométriques sont obtenues par combinaison affine de points correspondant à des barycentres topologiques. Ainsi, on obtient une méthode qui permet de masquer les éléments techniques de la conception d'opérations de modélisation géométrique et d'inférer des règles Jerboa qui implémentent ces opérations.
slides: ""
url_pdf: ""
summary: Journées du GTMG 2022
event_url: https://gtmg2022.sciencesconf.org/
authors:
  - admin
  - Hakim Belhaouri
  - Agnès Arnould
  - Pascale Le Gall
url_video: ""
date: 2022-03-17T15:00:00.000Z
featured: false
url_slides: GTMG2022.pdf
title: "Déduction topologique et géométrique pour l'inférence d'opérations de modélisation"
location: Dijon
links: []
event: Journées du GTMG 2022
publishDate: 2017-01-01T00:00:00Z
tags: []
projects: []
image:
  caption: ""
  focal_point: Right
url_code: ""
all_day: false
share: false
---
French event. I won the [Accessit Price](accessitContribution.pdf).
