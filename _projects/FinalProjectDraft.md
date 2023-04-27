---
name: Final Project
tools: [Python, HTML, vega-lite]
#image: assets/pngs/cars.png
description: This is my Final Project!
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---


# 2022 Crime in The Windy City: Understanding the Data 
## BY Lisa Zenku

## [My Python Notebook](https://github.com/lzenku2/lzenku2.github.io/blob/main/Zenku-Lisa-FinalProjectPart3.1.ipynb)

# PLOT 1

<vegachart schema-url="{{ site.baseurl }}/assets/json/final_1.json" style="width: 100%"></vegachart>

[Source](https://data.cityofchicago.org/Public-Safety/City-of-Chicago-Crime-Data/v9q9-3dm2)

The graph above shows the different Primary Type crimes that have or have not ended in an arrest and in what districts they are located. The graph on the left shows the different kinds of crimes compared to whether or not there was an arrest. Also, the color of each square shows the count of occurrences of that crime. The denser and darker the blue is, the more common that crime has occurred and ended with or without arrest. The graph on the right shows the number of total crimes highlighted on the right graph and what grouped district they were in. To be able to interact with this graph, you can go to the left graph and highlight the type of crime you want to look into further. The right graph will automatically change to show what you highlighted. For example, you can notice that motor vehicle theft and narcotics are a bit more colored in than the other squares around them. We can see that it is a bit darker blue for the True square in narcotics compared to the False square, which means most narcotic charges end in arrest. If you select those 4 squares with the highlight tool, the plot to the right changes and shows that it is more common for these crimes to occur in the 0-15 districts.

# PLOT 2

<vegachart schema-url="{{ site.baseurl }}/assets/json/final_2.json" style="width: 100%"></vegachart>

[Source](https://data.cityofchicago.org/Public-Safety/City-of-Chicago-Crime-Data/v9q9-3dm2)

The graph above shows the number of the top 10 most common primary type crimes per month in the year 2022. Each bar is divided into 11 different colors that represent the top 10 primary types and another color for the rest of the primary types. To be able to use this graph interactively, hover over the colored section of a bar on the graph that you want to learn more about and it will tell you the Primary Type, the count of recorded incidents, and the percentage of those crimes that end in arrest. For example, if you were to hover over the dark blue section in October, then you would see that the type of crime is assault, 1,835 occurrences of assault, and a percentage of 8.61% of those crimes led to an arrest. 

# CONTEXTUAL VISUALIZATIONS

![Champaign_and_Chicago_Viz](/assets/pngs/ComboPic.png)
[Champaign Source](https://www.neighborhoodscout.com/il/champaign/crime) and [Chicago Source](https://www.neighborhoodscout.com/il/chicago/crime)

The 2 graphs above show the crimes per square mile in Champaign, Illinois, and Chicago, Illinois from Neighborhood Scout. These graphs also show Illinois's crimes per square mile and the National median number. Illinois is the same as the National median but Champaign and Chicago are much above them. Comparing these cities to the National median, Champaign has about 3.5 more crimes per square mile and Chicago has about 14.5 more crimes per square mile. Comparing Chicago and Champaign together, Chicago has about 4.25 more crimes per square mile. It is important to note that according to the [United States Census Bureau](https://www.census.gov/quickfacts/fact/table/champaigncityillinois,chicagocityillinois/PST045222
), Champaign has a population of 89.114 in 2021 while Chicago has 2.7 million which can explain the density of crimes. These graphs give a great comparison of crimes in different cities since both are in Illinois and contain colleges. As a current resident of Champaign, it was interesting to compare how these cities differ in crime. 


