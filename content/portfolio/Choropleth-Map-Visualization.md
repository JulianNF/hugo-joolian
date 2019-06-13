---
title: "Choropleth Map Visualization"
date: 2019-02-27T17:13:10+02:00
draft: false

showonlyimage: false
image: "images/portfolio/choropleth-map-visualization-project_banner.jpg"
image_alt_text: "A photoshopped representation of the results of this project's visualization, showing a blue-tinged map of the USA's counties' higher education levels."
weight: 0

categories: [freeCodeCamp, learning, portfolio]
tags: [freeCodeCamp, front-end, choropleth map visualization project, web dev, JavaScript, CSS, SCSS, d3.js, topoJSON, HTML]
---

An interactive map of higher education rates per USA county.

<!--more-->

I built this visualization for [freeCodeCamp's](http://freeCodeCamp.org/) fourth **Data Visualization Projects**.

{{< codepen id="xBKYjy" >}}

This was a great project to work on. Not only are interactive choropleth (from Greek χῶρος "area/region" and πλῆθος "multitude") maps really cool to see and use, but I learned a ton working on the smaller details for this one.

Improvements for future versions (or an update to this one) will include figuring out how to make the SVG responsive rather than fixed in size. I figure this would likely require re-rendering the SVG on viewport resize events, as well as working with some sort of height-width ratio that recalculates actual height, widths, margin, etc. values on resize events.

### User Stories

The brief for the [Visualize Data with a Choropleth Map](https://learn.freecodecamp.org/data-visualization/data-visualization-projects/visualize-data-with-a-choropleth-map) project was as follows:

1. My choropleth should have a title with a corresponding id="title".
2. My choropleth should have a description element with a corresponding id="description".
3. My choropleth should have counties with a corresponding class="county" that represent the data.
4. There should be at least 4 different fill colors used for the counties.
5. My counties should each have data-fips and data-education properties containing their corresponding fips and education values.
6. My choropleth should have a county for each provided data point.
7. The counties should have data-fips and data-education values that match the sample data.
8. My choropleth should have a legend with a corresponding id="legend".
9. There should be at least 4 different fill colors used for the legend.
10. I can mouse over an area and see a tooltip with a corresponding id="tooltip" which displays more information about the area.
11. My tooltip should have a data-education property that corresponds to the data-education of the active area.
