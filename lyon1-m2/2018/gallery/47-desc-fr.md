# seaLevelProjet.github.io

![](47-teaser.png)

# Table des matières
1. [Données](#Données)
2. [Objectifs](#Objectifs)
3. [Réalisation](#Réalisation)
4. [Améliorations](#Améliorations)
5. [Sources](#Sources)

![](47-thumbnail.gif)

# Prédiction de la hausse du niveau de la mer

# Données
Notre visualisation a pour but de montrer l'évolution du niveau de la mer.
Nous avons récupéré des données du niveau de la mer de 1880 à 2015 en considérant que le niveau de la mer vaut 0 en 1880.
Nous avseaLevel.pngons aussi des données de température de 1880 à 2015.

De plus, en se basant sur ces données, nous avons fait des prédictions (sur R) du niveau de la mer et de la température jusqu'en 2400. Nous avons réalisé trois prédictions : une optimiste, une pessimiste et une intermédiaire. Pour cela nous avons utilisé un modèle exponentiel en faisant varié le paramètre avec 3 valeurs différentes.

Les jeux de données ont été récupérés à cette adresse : https://datahub.io/core/sea-level-rise#resource-sea-level-rise_zip



# Objectifs
Notre objectif est de montrer la corrélation entre l'augmentation de la température et l'augmentation du niveau de la mer mais aussi de montrer les conséquences possibles de ces augmentations.

# Réalisation
La visualisation comporte deux graphiques :

- Un "triangle" (en haut à gauche) : Ce triangle représente une côte qui se fait peu à peu submerger par l'eau. Ce graphique permet de voir la montée des eaux au cours du temps à l'aide du slider temporel placé au dessus de la visualisation.
Le long de la pente sont placés plusieurs grandes villes dans le but d'observer les villes qui seront submergées si le phénomène continue sur cette lancée. En passant sur une ville on peut obtenir des informations supplémentaires comme l'altitude, la population, ...

- Un streamgraph : Ce streamgraph permet de visualiser à la fois l'évolution de l'augmentation de la température moyenne sur la surface du globe au cours du temps mais aussi l'évolution du niveau de la mer sur Terre grâce à l'épaisseur du streamgraph. On voit une corrélation entre niveau de la mer et température puisque au cours des années le niveau de la mer et la température augmente en même temps.

# Améliorations

Suite à la présentation, nous avons modifié des éléments de la visualisation. Nous avons réalisé deux versions :

- Version 2 : Version qui ne comporte pas les prédictions de température jusqu'en 2400. Il nous a été demandé d'ajouté les prédictions de températures jusqu'en 2400 sur le streamgraph, nous pensons qu'en ajoutant cela la visualisation n'est plus esthétique. C'est la version que nous préférons.

- Version 3 : Version qui comporte les prédictions de température sur le streamgraph.

Un élément à été ajouté à la visualisation :

- Une jauge verticale : Sur les versions 2 et 3 (qui font suite à la présentation), nous avons placé une jauge verticale à gauche des graphiques pour permettre d'observer la montée des eaux de manière linéaire. Cela permet de bien voir l'explosion du phénomène qui n'était pas visible avec l'échelle logarithmique utilisée pour le graphique. Nous avons fait le choix de laisser l'échelle logarithmique qui permet de voir les petites variations du niveau de la mer qui ne sont pas visibles avec l'échelle linéaire.

Nous avons aussi modifié l'affichage des villes le long de la pente.

# Sources
Pour réaliser ce projet, nous nous sommes inspirés des exemples de Mike Bostock ainsi que de cette visualisation : https://bl.ocks.org/lsbardel/d686414f38742cb60c3bf3f21b79b9df (pour faire les vagues).
