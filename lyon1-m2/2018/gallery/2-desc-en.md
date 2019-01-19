[Rain, wind, snow: how has climate changed in mainland France from 2010 to 2018?](https://wasaviz.github.io/)

We designed an application composed by three connected visualisations :

  - A **map of France**, showing one indicator by weather station of our dataset. Those indicators contain 4 variables, each in a different color scale and a different size : temperature, wind, rain and snow. Their intensity increaases with the value of the variable. The min and max scale values can be seen in the bottom right hand corner. The values correspond to time point given by the gobal slider of the application.
  - A **projection in a plane formed by two variables**. It aims to reveal correlations between two features, at a given time point. Those variables can be changed, and the axis will be rescaled as needed. The temporal evolution of the stations can be shown by launching a movie from the current time point. 
  - A **line chart** that can be accessed from the two previous visualisations. It shows one of the 4 variables in time. The variable can be chosen by hovering over the corresponding part of an indicator of the map, or in the projection graph. A vertical line shows the position of the current slider.

The different visualisations are linked to each other, such as when a station is hovered over in a graph, it is also enlarged in the other one. 
