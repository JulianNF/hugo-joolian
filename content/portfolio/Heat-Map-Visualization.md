---
title: "Heat Map Visualization"
date: 2019-02-23T13:35:00+02:00
draft: false

showonlyimage: false
image: "images/portfolio/heat-map-visualization-project_banner.jpg"
image_alt_text: "A photoshopped screenshot of the visualization for this project, showing mean global land-mass temperatures per month since 1753."
weight: 0

categories: [freeCodeCamp, learning, portfolio]
tags: [freeCodeCamp, front-end, heat map visualization project, web dev, JavaScript, CSS, SCSS, d3.js, d3.tip, d3-legend, HTML]
---

An interactive visualization of global land-surface temperatures since 1753.

<!--more-->

I built this visualization for [freeCodeCamp's](http://freeCodeCamp.org/) third **Data Visualization Projects**.

{{< codepen id="WPBvPY" >}}

I chose to diversify my approach for this project and used the d3.tip tooltip library and the d3-legent library as well. I'm happy that I played around with these, but I still pine for a good way to easily implement tooltips and legends in D3 without resorting to external librairies.

### User Stories

The brief for the [Visualize Data with a Heat Map](https://learn.freecodecamp.org/data-visualization/data-visualization-projects/visualize-data-with-a-heat-map) project was as follows:

1. My heat map should have a title with a corresponding id="title".
2. My heat map should have a description with a corresponding id="description".
3. My heat map should have an x-axis with a corresponding id="x-axis".
4. My heat map should have a y-axis with a corresponding id="y-axis".
5. My heat map should have rect elements with a class="cell" that represent the data.
6. There should be at least 4 different fill colors used for the cells.
7. Each cell will have the properties data-month, data-year, data-temp containing their corresponding month, year, and temperature values.
8. The data-month, data-year of each cell should be within the range of the data.
9. My heat map should have cells that align with the corresponding month on the y-axis.
10. My heat map should have cells that align with the corresponding year on the x-axis.
11. My heat map should have multiple tick labels on the y-axis with the full month name.
12. My heat map should have multiple tick labels on the x-axis with the years between 1754 and 2015.
13. My heat map should have a legend with a corresponding id="legend".
14. My legend should contain rect elements.
15. The rect elements in the legend should use at least 4 different fill colors.
16. I can mouse over an area and see a tooltip with a corresponding id="tooltip" which displays more information about the area.
16. My tooltip should have a data-year property that corresponds to the data-year of the active area.
