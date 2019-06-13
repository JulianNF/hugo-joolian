---
title: "Treemap Visualization"
date: 2019-03-01T14:06:14+02:00
draft: false

showonlyimage: false
image: "images/portfolio/treemap-visualization-project_banner.jpg"
image_alt_text: "A photoshoped image of this project's treemap visualization."
weight: 0

categories: [freeCodeCamp, learning, portfolio]
tags: [freeCodeCamp, front-end, treemap visualization project, web dev, JavaScript, CSS, SCSS, d3.js, HTML]
---

A visualization of the highest-grossing movies using D3.js to generate an SVG graphic.

<!--more-->

I built this little website for [freeCodeCamp's](http://freeCodeCamp.org/) third **Responsive Web Design Projects**.

{{< codepen id="eXNyEX" >}}

I had the pleasure of banging this visualization out over the course of two days (12 hours), and chose to not use any tooltip or legend librairies in order to challenge myself to learn more.

### User Stories

The brief for the [Visualize Data with a Treemap Diagram](https://learn.freecodecamp.org/data-visualization/data-visualization-projects/visualize-data-with-a-treemap-diagram) project was as follows:

1. My tree map should have a title with a corresponding id="title".
2. My tree map should have a description with a corresponding id="description".
3. My tree map should have rect elements with a corresponding class="tile" that represent the data.
4. There should be at least 2 different fill colors used for the tiles.
5. Each tile should have the properties data-name, data-category, and data-value containing their corresponding name, category, and value.
6. The area of each tile should correspond to the data-value amount: tiles with a larger data-value should have a bigger area.
7. My tree map should have a legend with corresponding id="legend".
8. My legend should have rect elements with a corresponding class="legend-item".
9. The rect elements in the legend should use at least 2 different fill colors.
10. I can mouse over an area and see a tooltip with a corresponding id="tooltip" which displays more information about the area.
11. My tooltip should have a data-value property that corresponds to the data-value of the active area.
