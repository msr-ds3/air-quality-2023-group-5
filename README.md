# air-quality-2023-group-5
This project consit of investigating this [article](https://write.geeksforgeeks.org/](https://www.pnas.org/doi/10.1073/pnas.2006853117#sec-1)https://www.pnas.org/doi/10.1073/pnas.2006853117#sec-1). They mentiont "The global response to the COVID-19 pandemic has resulted 
inunprecedented reductions in economic activity. We find that,after accounting for meteorological variations, lockdown events have reduced the population-weighted concentration of nitrogen dioxide and particulate matter levels by about 60% and 31% in 34 countries, with mixed effects on ozone. Reductions in transportation sector emissions are largely responsible for the NO2 anomalies.

Outline: 
Joining the city data with the coordinates data, and treat the parameter variable as a factor.

Added a new column called condition, which is going to differentiate between the baseline(01/01 - 05/15/2017 - 19) and the 2020 COVID19 time frame ( 01/01 - 05/15/2020) for each city. Then plot the mean pm25 level for the baseline and 2020 time frame for each city.

Computing the mean deviation percentage and using their longitude and latitude to plot each city on the map. 

It doesn't really look the same but the article has a subtle confusion on how they plotted these graphs. 

Here we use the US and China compute the difference between the observed benchmark and the predicted benchmark. 
