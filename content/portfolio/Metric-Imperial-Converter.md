---
title: "Metric-Imperial Converter"
date: 2019-04-10T11:26:14+02:00
draft: false

showonlyimage: false
image: "images/portfolio/metric-imperial-converter-microservice-project_banner.jpg"
image_alt_text: "A screenshot of my take on the metric-imperial converter project for freeCodeCamp."
weight: 0

categories: [freeCodeCamp, learning, portfolio]
tags: [freeCodeCamp, web dev, HTML, CSS, JavaScript, Node.js, Express.js, MongoDB, body-parser, helmet.js, chai.js, chai-http, Mocha, math.js]
---

A small web app that converts between metric and imperial unit measures (Km/mi, Kg/lbs, L/gal).

<!--more-->

I built this little website for [freeCodeCamp's](http://freeCodeCamp.org/) first **Information Security and Quality Assurance Projects**.

{{< glitch project="cliff-gray" >}}

The sample web app for this project was corrupted, but no problem, the files were still available on GitHub. After some time spent trying to make heads or tails of the boilerplate code, I got to work and banged the converter out. All in all, everything took me 17 hours to do and I felt even more energized and focused working on this project than usual.

### User Stories

The brief for the [Metric-Imperial Converter](https://learn.freecodecamp.org/information-security-and-quality-assurance/information-security-and-quality-assurance-projects/metric-imperial-converter) project was as follows:

1. I will help prevent the client from trying to guess(sniff) the MIME type.
2. I will prevent cross-site scripting (XSS) attacks.
3. I can GET /api/convert with a single parameter containing an accepted number and unit and have it converted.
4. Hint: Split the input by looking for the index of the first character.
5. I can convert 'gal' to 'L' and vice versa. (1 gal to 3.78541 L)
6. I can convert 'lbs' to 'kg' and vice versa. (1 lbs to 0.453592 kg)
7. I can convert 'mi' to 'km' and vice versa. (1 mi to 1.60934 km)
8. If my unit of measurement is invalid, returned will be 'invalid unit'.
9. If my number is invalid, returned with will 'invalid number'.
10. If both are invalid, return will be 'invalid number and unit'.
11. I can use fractions, decimals or both in my parameter(ie. 5, 1/2, 2.5/6), but if nothing is provided it will default to 1.
12. My return will consist of the initNum, initUnit, returnNum, returnUnit, and string spelling out units in format `{initNum} {initial_Units}converts to {returnNum} {return_Units}` with the result rounded to 5 decimals.
13. All 16 unit tests are complete and passing.
14. All 5 functional tests are complete and passing.
