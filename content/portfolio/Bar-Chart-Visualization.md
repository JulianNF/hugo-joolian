---
title: "Bar Chart Visualization"
date: 2019-02-18T21:20:36+02:00
draft: false

showonlyimage: false
image: "images/portfolio/bar-chart-visualization-project_banner.jpg"
image_alt_text: "A photoshopped image of the bar chart I created for this freeCodeCamp project."
weight: 0

categories: [freeCodeCamp, learning, portfolio]
tags: [freeCodeCamp, front-end, bar chart visualization project, web dev, JavaScript, CSS, SCSS, d3.js, HTML]
---

A visualization of the United State's GDP since 1947.

<!--more-->

I built this visualization for [freeCodeCamp's](http://freeCodeCamp.org/) first **Data Visualization Projects**.

{{< codepen id="KJWZOR" >}}

This is my first ever interactive bar chart built with D3.js. I found the documentation for the library difficult to use, and judging from the questions, comments, and answers I saw elsewhere on the internet while researching for my project, it seems that many other users have struggled with the same issues.

My biggest technical hurdles on this project were:

* struggling to get the xScale to work nicely (switching from scaleLinear to scaleBand() worked in the end)
* getting the tick marks on the x-axis to display as I wanted them to
* getting tooltips to render at the cursor's location

### User Stories

The brief for the [Visualize Data with a Bar Chart](https://learn.freecodecamp.org/data-visualization/data-visualization-projects/visualize-data-with-a-bar-chart) project was as follows:

1. My chart should have a title with a corresponding id="title".
2. My chart should have a g element x-axis with a corresponding id="x-axis".
3. My chart should have a g element y-axis with a corresponding id="y-axis".
4. Both axes should contain multiple tick labels, each with the corresponding class="tick".
5. My chart should have a rect element for each data point with a corresponding class="bar" displaying the data.
6. Each bar should have the properties data-date and data-gdp containing date and GDP values.
7. The bar elements' data-date properties should match the order of the provided data.
8. The bar elements' data-gdp properties should match the order of the provided data.
9. Each bar element's height should accurately represent the data's corresponding GDP.
10. The data-date attribute and its corresponding bar element should align with the corresponding value on the x-axis.
11. The data-gdp attribute and its corresponding bar element should align with the corresponding value on the y-axis.
12. I can mouse over an area and see a tooltip with a corresponding id="tooltip" which displays more information about the area.
13. My tooltip should have a data-date property that corresponds to the data-date of the active area.
