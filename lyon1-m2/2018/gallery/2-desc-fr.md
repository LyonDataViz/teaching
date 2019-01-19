[Rain, wind, snow: how has climate changed in mainland France from 2010 to 2018?](https://wasaviz.github.io/)

Nous avons créé une application composée de trois visualisations inter-connectées : 

  - Une **carte de la France**, montrant un indicateur par station météo de notre jeu de données. Ces inicateurs contiennent 4 vaiables, chacune ayant une échelle de couleur différente et une taille différente : température, vent, pluie et neige. Leur intensité varie avec la valeur de la variable. Les bornes min et max utilisées pour chaque indicateur peuvent être retrouvées en bas à droite. Les valeurs correspondent à la période temporelle donnée par le slider de l'application.
  - Une **projection dans le plan de deux varaibles**. Le but est de montrer les corrélations entre deux indicateurs, à un moment donné. Les variables choisies peuvent être changées, et les axes seront mis à l'échelle si besoin est. L'évolution au cours du temps des stations peut être visualisé en lançant une vidéo sur la période temporelle demandée. 
  - Un **line chart** peut être utilisé grâce aux deux visualisations précédentes. Il montre l'évolution d'une des quatre variables dans le temps. La variable peut être choisie en passant le curseur sur l'indicateur voulu sur la carte, ou sur la projection. Une ligne verticale montre la position du slider courant.

Les différentes visualisations sont inter-connectées, c'est à dire que lorsque une station est sélectionnée sur une des visualisations, elle l'est aussi sur les autres. 
