---
title: "Drum Machine"
date: 2019-01-25T19:45:13+02:00
draft: false

showonlyimage: false
image: "images/portfolio/drum-machine-project_banner.jpg"
image_alt_text: "A photoshopped image of the drumpad that I designed and coded for this project."
weight: 0

categories: [freeCodeCamp, learning, portfolio]
tags: [freeCodeCamp, front-end, drumpad project, web dev, CSS, SCSS, HTML, JavaScript, React]
---

A drum pad that works with mouse clicks and keyboard presses.

<!--more-->

I built this web app for [freeCodeCamp's](http://freeCodeCamp.org/) third **Front End Libraries Projects**.

{{< codepen id="PVYJvg" >}}

This was a pretty straightforward and fun project to work on. Finding free samples was a bit tedious, but the biggest headscratcher for this project was figuring out how to handle keyboard presses.

All told, it took me 22 hours to design, code, research, style, and review this project before submitting it. It was fun to put one of these together.

In the next iteration (or update), I'd like to figure out how to play concurrent sounds over each other (either same sample or different samples), or have samples terminate any other currently playing sounds (including the same sample). Either of these changes would bring the functionality of this project more in line with the expected real-world behaviour of a drum pad.

### User Stories

The brief for the [Build a Drum Machine](https://learn.freecodecamp.org/front-end-libraries/front-end-libraries-projects/build-a-drum-machine) project was as follows:

1. I should be able to see an outer container with a corresponding id="drum-machine" that contains all other elements.
2. Within #drum-machine I can see an element with a corresponding id="display".
3. Within #drum-machine I can see 9 clickable drum pad elements, each with a class name of drum-pad, a unique id that describes the audio clip the drum pad will be set up to trigger, and an inner text that corresponds to one of the following keys on the keyboard: Q, W, E, A, S, D, Z, X, C. The drum pads MUST be in this order.
4. Within each .drum-pad, there should be an HTML5 audio element which has a src attribute pointing to an audio clip, a class name of clip, and an id corresponding to the inner text of its parent .drum-pad (e.g. id="Q", id="W", id="E" etc.).
5. When I click on a .drum-pad element, the audio clip contained in its child audio element should be triggered.
6. When I press the trigger key associated with each .drum-pad, the audio clip contained in its child audio element should be triggered (e.g. pressing the Q key should trigger the drum pad which contains the string "Q", pressing the W key should trigger the drum pad which contains the string "W", etc.).
7. When a .drum-pad is triggered, a string describing the associated audio clip is displayed as the inner text of the #display element (each string must be unique).