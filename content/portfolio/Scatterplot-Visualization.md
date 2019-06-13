---
title: "Scatterplot Visualization"
date: 2019-02-20T19:06:54+02:00
draft: false

showonlyimage: false
image: "images/portfolio/scatterplot-visualization-project_banner.jpg"
image_alt_text: "A photoshopped representation of this project's scatterplot visualization."
weight: 0

categories: [freeCodeCamp, learning, portfolio]
tags: [freeCodeCamp, front-end, scatterplot visualization project, web dev, JavaScript, CSS, SCSS, d3.js, HTML]
---

A graph showing doping allegations against the fastest climber's at the Alpe d'Huez in the Tour de France.

<!--more-->

I built this visualization for [freeCodeCamp's](http://freeCodeCamp.org/) second **Data Visualization Projects**.

{{< codepen id="XOOPVw" >}}

I continued to struggle with placing tooltips on this visualization project, as I have yet to find a clean and efficient way to do so without relying on external D3 tooltip or legend libraries. I'm definitely getting better at it, but there is still work to be done.

### User Stories

The brief for the [Visualize Data with a Scatterplot Graph](https://learn.freecodecamp.org/data-visualization/data-visualization-projects/visualize-data-with-a-scatterplot-graph) project was as follows:

1. I can see a title element that has a corresponding id="title".
2. I can see an x-axis that has a corresponding id="x-axis".
3. I can see a y-axis that has a corresponding id="y-axis".
4. I can see dots, that each have a class of dot, which represent the data being plotted.
5. Each dot should have the properties data-xvalue and data-yvalue containing their corresponding x and y values.
6. The data-xvalue and data-yvalue of each dot should be within the range of the actual data and in the correct data format. For data-xvalue, integers (full years) or Date objects are acceptable for test evaluation. For data-yvalue (minutes), use Date objects.
7. The data-xvalue and its corresponding dot should align with the corresponding point/value on the x-axis.
8. The data-yvalue and its corresponding dot should align with the corresponding point/value on the y-axis.
9. I can see multiple tick labels on the y-axis with %M:%S time format.
10. I can see multiple tick labels on the x-axis that show the year.
11. I can see that the range of the x-axis labels are within the range of the actual x-axis data.
12. I can see that the range of the y-axis labels are within the range of the actual y-axis data.
13. I can see a legend containing descriptive text that has id="legend".
14. I can mouse over an area and see a tooltip with a corresponding id="tooltip" which displays more information about the area.
15. My tooltip should have a data-year property that corresponds to the data-xvalue of the active area.
