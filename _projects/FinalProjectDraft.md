---
name:  IS 445 Final Project
tools: [Python, HTML, vega-lite]
image: assets/pngs/chiflag.png
description: 2022 Crime in The Windy City
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---


# 2022 Crime in The Windy City: Understanding the Data 
## By Lisa Zenku

## [Python Notebook](https://github.com/lzenku2/lzenku2.github.io/blob/main/Zenku-Lisa-FinalProjectPart3.1.ipynb) [GitHub Repository](https://github.com/lzenku2/lzenku2.github.io)

# Plot 1: Dashboard of Arrests in Each Primary Type Crime and the Grouped Districts

<vegachart schema-url="{{ site.baseurl }}/assets/json/final_1_plot.json" style="width: 100%"></vegachart>

[Source](https://data.cityofchicago.org/Public-Safety/City-of-Chicago-Crime-Data/v9q9-3dm2)

The graph above shows the different Primary Type crimes that have or have not ended in an arrest and the wards they are located in. The graph on the left shows the different kinds of crimes compared to whether or not there was an arrest. Also, the color of each square shows the count of occurrences of each crime. The denser and darker the blue is, the more common that crime has occurred and the lighter the blue is, the less common that crime has occured. The graph on the right shows the number of total crimes highlighted on the left graph and what wards they were in. The color of the right plot is based on the Primary Type and allows the user to visually see the concentration of the crimes. To be able to interact with this graph, you can go to the left graph and highlight the type of crime(s) you want to look into further. The right graph will automatically update the data to be based on what you highlighted from the left graph. Another way to interact with the right plot is by hovering over a section of one of the bars to see the exact ward and primary type crime it is a part of. For example, you can notice that motor vehicle theft and narcotics are a bit more colored in than the other squares around them. We can see that it has a bit darker blue for the True square in narcotics compared to the False square, which means most narcotic charges end in arrest. If you select those 4 squares with the highlight tool, the plot to the right changes and shows that it is most common for these crimes to occur in the 24, 27, and 28 wards. 

Grouped Wards Listed Below:

1-5 wards: 

1 Rogers Park, 2 West Ridge, 3 Uptown, 4 Lincoln Square, 5 North Center

6-10 wards:

6 Lakeview, 7 Lincoln Park, 8 Near North Side, 9 Edison Park, 10 Norwood Park

11-15 wards:

11 Jefferson Park, 12 Forest Glen, 13 North Park, 14 Albany Park, 15 Portage Park

16-20 wards:

16 Irving Park, 17 Dunning, 18 Montclare, 19 Belmont Cragin, 20 Hermosa

21-25 wards:

21 Avondale, 22 Logan Square, 23 Humboldt Park, 24 West Town, 25 Austin

26-30 wards:

26 Garfield Park, 27 North Lawndale, 28 South Lawndale, 29 Lower West Side, 30 Near West Side

31-35 wards:

31 McKinley Park, 32 Bridgeport, 33 Brighton Park, 34 Gage Park, 35 West Elsdon

36-40 wards:

36 Archer Heights, 37 Clearing, 38 West Lawn, 39 Chicago Lawn, 40 West Englewood

41-45 wards:

41 Ashburn, 42 Auburn Gresham, 43 Beverly, 44 Washington Heights, 45 Mount Greenwood

46-50 wards:

46 Morgan Park, 47 Chatham, 48 South Shore, 49 Roseland, 50 Pullman

# Plot 2: The Top 10 Primary Type Crimes Per Month

<vegachart schema-url="{{ site.baseurl }}/assets/json/final_2.json" style="width: 100%"></vegachart>

[Source](https://data.cityofchicago.org/Public-Safety/City-of-Chicago-Crime-Data/v9q9-3dm2)

The graph above shows the number of the top 10 most common primary type crimes per month in the year 2022. Each bar is divided into 11 different colors that represent the top 10 primary types and another color for the rest of the primary types. To be able to use this graph interactively, you can hover over the colored section of a bar on the graph that you want to learn more about and it will tell you the Primary Type, the count of recorded incidents, and the percentage of those crimes that end in arrest. For example, if you were to hover over the dark blue section in October, then you would see that the type of crime is assault, the amount of occurrences of assault is 1,835, and a percentage of 8.61% of those crimes led to an arrest. 

# CONTEXTUAL VISUALIZATIONS: Crimes Per Square Mile in Champaign, IL and Chicago, IL

![Champaign_and_Chicago_Viz](/assets/pngs/ComboPic.png)
[Champaign Source](https://www.neighborhoodscout.com/il/champaign/crime) and [Chicago Source](https://www.neighborhoodscout.com/il/chicago/crime)

The 2 graphs above show the crimes per square mile in Champaign, Illinois, and Chicago, Illinois from Neighborhood Scout. These graphs also show Illinois's crimes per square mile and the National median number. Illinois has the same amount of crime per square mile as the National median but Champaign and Chicago are both above them. Comparing these cities to the National median, Champaign has about 3.5 more crimes per square mile and Chicago has about 14.5 more crimes per square mile. Comparing Chicago and Champaign together, Chicago has about 4.25 more crimes per square mile. It is important to note that according to the [United States Census Bureau](https://www.census.gov/quickfacts/fact/table/champaigncityillinois,chicagocityillinois/PST045222
), Champaign has a population of 89,114 in July 2021 while Chicago has about 2.7 million which can explain the density of crimes. These graphs give a great comparison of crimes in different cities since both are in Illinois and contain colleges. As a current resident of Champaign, it was interesting to compare how these cities differ in crime density. 

[Chicago Flag Cover Image Source](https://en.wikipedia.org/wiki/Flag_of_Chicago)
