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


# HW 10 Plots

For my plots, I used the Building Inventory Dataset to see what kind of data does the buildings from each Agency has in each congressional area. My plot are shown side-by-side of each other. [My Python Notebook](https://github.com/lzenku2/lzenku2.github.io/blob/main/Zenku-Lisa-HW10.ipynb).


<vegachart schema-url="{{ site.baseurl }}/assets/json/hw10.json" style="width: 100%"></vegachart>


## Discussion

Before I created the plots, I wanted to explore the data and see what kind of data the dataset offered. In my first plot, I decided to look into the US Congress representatives and what agency they are involved in. I wanted to see if there was an agency that is working with all congressional members or if a congressional member is working with all agencies. I made the x-axis with the “Agency Name” column and made the type to be nominal and the y-axis with the “Congressional Full Name” column and made the type to be nominal. Another aspect I added was making the color of each square dependent on the count of buildings of that specific congressional member and agency. Lighter blue means it has a lower count of buildings and dark blue means it has a higher count of buildings. I decided to keep the default color of blue for my plot and not change it to a different color to keep both plots standardized. The only data transformation was the aggregation when creating the plots.

My second plot is the result of the interaction with my first plot. From the section that is highlighted in my first plot, the second plot showed how much square footage the buildings have and the count of buildings in each square footage interval. For example, the first square footage interval is 0 to 100,000 and the intervals continued on by 100,000 sq. ft. I made the x-axis with the “Square Footage” column and the type to be quantitative and the y-axis with the count of how many buildings are in each interval of square footage and used the type quantitative.