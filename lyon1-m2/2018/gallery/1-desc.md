[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-blue.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

# LifeHabitsChanger : Calculateur d'émission de CO2 <br/> LifeHabitsChanger : CO2 emission calculator
> BUSAC Pascal  
> CHAPUT Rémy  
> VERGNE Théo  
> YANG Pierre  

![Thumbnail](/thumbnail.png?)

### Description (EN)

This project has been realized in the course [Data Visualization](https://lyondataviz.github.io/teaching/lyon1-m2/2018/) of the [Master Artificial Intelligence](http://master-info.univ-lyon1.fr/IA/) at [University Claude Bernard Lyon 1](https://www.univ-lyon1.fr/).

This visualization allows us to observe the carbon footprint of our choices and lifestyle, at an individual level. We assume that global warming is a fact, and is (in part) caused by too much greenhouse gas emissions, including CO2. We therefore want to raise awareness and inform citizens, by allowing both to calculate its personal CO2 emission (according to several criteria, such as food, transport, heating, ...), but also to simulate different scenarios and to observe the impact of a modification of a habit (if I ate less beef, I would avoid the emission of X kg of CO2). A secondary objective is to simulate habits changes in order to achieve the [COP21](http://www.cop21paris.org/) objective.

We invite you to enter your own data to get an estimate of your greenhouse gas emissions. Playing with the different parameters gives an idea of the impact of the different elements.

### Présentation (FR)  

Ce projet a été réalisé dans le cadre de [l'UE Data Visualization](https://lyondataviz.github.io/teaching/lyon1-m2/2018/) du [Master 2 Intelligence Artificielle](http://master-info.univ-lyon1.fr/IA/) de [l'Université Claude Bernard Lyon 1](https://www.univ-lyon1.fr/).

Cette visualisation permet d'observer l'empreinte carbone de nos choix et habitudes de vie, d'un niveau individuel. Nous partons du principe que le réchauffement climatique est un fait, et est (en partie) causé par trop d'émission de gaz à effet de serre, notamment le CO2. Nous souhaitons donc sensibiliser et informer les citoyens, en permettant à la fois de calculer son émission de CO2 personnelle (en fonction de plusieurs critères, comme l'alimentation, le transport, le chauffage, ...), mais également de simuler différents scénarios et d'observer l'impact d'une modification d'une habitude (si je mangeais moins de boeuf, je pourrais éviter l'émission de X kg de CO2). Un objectif secondaire est de simuler des modifications d'habitude afin d'atteindre l'objectif de la [COP21](https://www.apc-paris.com/cop-21).

Nous vous invitons à renseigner les données vous concernant pour avoir une estimation de vos émissions de gaz à effet de serre. Jouer avec les différents paramètres donne une idée de l'impact des différents éléments.

### Choix des visualisations

Nous avons choisi de présenter les données sous forme de Stacked Bar Chart afin de visualiser directement la somme totale calculée.
Grace aux différentes catégories indiquées, l’utilisateur peut directement comprendre la part de chacune.   
En utilisant le questionnaire, il peut explorer les impacts des différents éléments.
Les autres colonnes du Bar Chart lui permettent de se comparer avec des profils spécifiques (français moyens, végan...).  
De plus, La représentation sous forme de droite de l’objectif de la cop 21 permet de savoir immédiatement si celui-ci est atteint en fonction des choix indiqués dans le questionnaire. 

### Limites

Certains facteurs ne sont pas pris en compte dans cette visualisation :
- On ne considère que le chauffage tout électrique
- L'empreinte carbone liée à l'achat de divers produits manufacturés n'est pas pris en compte (électronique, vêtements, produits divers)
- Chauffer à différentes température n'est pas pris en compte

Bien que nous ayons croisé les sources au mieux, la précision du modèle reste relative. Certaines valeurs changent significativement d'une source à l'autre.

### Pistes d'amélioration

On pourait gagner en précision en ce qui concerne la consommation de l'électorménager en demandant quels produits l'utilisateur possède.

Tout le monde ne connait pas la classe énergétique (A, B, .., G) de son logement et de ses appareils électrique. Il serait intéressant de proposer, par exemple, une bulle d'aide pour aider à estimer ces valeurs.

Renseigner les transports en km/an n'est pas idéal.

### Liens :

[Le projet](https://lifehabitschanger.github.io/)  
[Les données](https://github.com/LifeHabitsChanger/lifehabitschanger.github.io/blob/master/Data.csv)  
[Le detail des données alimentaires](https://github.com/LifeHabitsChanger/lifehabitschanger.github.io/blob/master/Data_alimentaire.csv)  

La majorité des sources utilisées pour mettre en place le modèle sont consultables dans le fichier Data.csv présent dans cette archive
