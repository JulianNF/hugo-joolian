---
title: "Build a Calculator"
date: 2019-02-16T12:32:45+02:00
draft: false

showonlyimage: false
image: "images/portfolio/calculator-project_banner.jpg"
image_alt_text: "A photoshopped image of the calculator that I designed and coded for this project."
weight: 0

categories: [freeCodeCamp, learning, portfolio]
tags: [freeCodeCamp, front-end, calculator project, web dev, CSS, HTML, JavaScript, jQuery, math.js]

---

A pure CSS JavaScript calculator that works.

<!--more-->

I built this app for [freeCodeCamp's](http://freeCodeCamp.org/) fourth **Front End Libraries Projects**.

{{< codepen id="OzmajL" >}}

This was a really fun project to work on. Buidling something completely from scratch and taking the time to do it right was really satisfying. Let me know if you have any feedback on the project.

### User Stories

The brief for the [Build a JavaScript Calculator](https://learn.freecodecamp.org/front-end-libraries/front-end-libraries-projects/build-a-javascript-calculator) project was as follows:

1. My calculator should contain a clickable element containing an = (equal sign) with a corresponding id="equals".
2. My calculator should contain 10 clickable elements containing one number each from 0-9, with the following corresponding IDs: id="zero", id="one", id="two", id="three", id="four", id="five", id="six", id="seven", id="eight", and id="nine".
3. My calculator should contain 4 clickable elements each containing one of the 4 primary mathematical operators with the following corresponding IDs: id="add", id="subtract", id="multiply", id="divide".
4. My calculator should contain a clickable element containing a . (decimal point) symbol with a corresponding id="decimal".
5. My calculator should contain a clickable element with an id="clear".
6. My calculator should contain an element to display values with a corresponding id="display".
7. At any time, pressing the clear button clears the input and output values, and returns the calculator to its initialized state; 0 should be shown in the element with the id of display.
8. As I input numbers, I should be able to see my input in the element with the id of display.
9. In any order, I should be able to add, subtract, multiply and divide a chain of numbers of any length, and when I hit =, the correct result should be shown in the element with the id of display.
10. When inputting numbers, my calculator should not allow a number to begin with multiple zeros.
11. When the decimal element is clicked, a . should append to the currently displayed value; two . in one number should not be accepted.
12. I should be able to perform any operation (+, -, *, /) on numbers containing decimal points.
13. If 2 or more operators are entered consecutively, the operation performed should be the last operator entered.
14. Pressing an operator immediately following = should start a new calculation that operates on the result of the previous evaluation.
15. My calculator should have several decimal places of precision when it comes to rounding (note that there is no exact standard, but you should be able to handle calculations like 2 / 7 with reasonable precision to at least 4 decimal places).
