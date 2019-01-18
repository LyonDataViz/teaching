## Climate events in the United States: seasonality and influence on the price of insurance.
<i>Project realized by Cheikh Toure, Rhizlaine Degni, Floriand Baud and Antoine Vendeville.</i>

https://florianbaud.github.io/# (also available on mobile)

### Dataset
The climate events dataset is available at https://catalog.data.gov/dataset/ncdc-storm-events-database (does not currently work due to administrative blocking in the US). It contains data on more than 50 million climatic events in the United States during the year 2017, of more than 50 different types: tornado, flood, drought, ... For each event, the states affected, the number of injuries, the number of deaths and the damage assessment in $.

Regarding the price of home insurance, the data is at https://quotewizard.com/news/posts/home-insurance-rate-increase-by-state.

### Objectives
Our goal is divided into two parts. First, try to correlate the damage caused by natural disasters in the United States with the price of home insurance. Second, establish a temporal visualization of event occurrences of each type to determine which seasons each type of event occurs.

### Interest
This visualization can be used by people wishing to move to the United States, so that they know in what state they are least likely to be affected by a natural disaster and / or in which they will pay the cheapest home insurance. The temporal visualization makes it possible to know which states are the most dangerous at a given moment in the year.

### Production
For the insurance part, we juxtaposed a map of the United States and a wordcloud. On the wordcloud, each state is represented with a size proportional to the price of home insurance. One can compare with the map: when selecting a type of event, the states are colored there according to the damage caused by all the cumulated events of this type. By hovering over the states, the damage and the number of deaths are displayed, and the state is highlighted in the wordcloud (and vice versa when you mouse over a state in the wordcloud). We can thus observe the correlation between the damage caused by climate events and the price of insurance.

For the temporal part, we made a HeatMap which represents the frequency of the different types of climatic events throughout the year. Each box corresponds to one month (in abscissa) and one type of event (in ordinate) and is colored according to the number of events of this type which were observed during the month. We observe the impact of the seasons on the types of events encountered.

#### Inspiration
GeoMap : https://lyondataviz.github.io/teaching/lyon1-m2/2018/tp5.html <br>
WordCloud : https://jsfiddle.net/plantface/g6faeurj/ <br>
HeatMap : https://codepen.io/ubershibs/pen/JbKVPJ
