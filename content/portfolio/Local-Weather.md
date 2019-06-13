---
title: "Local Weather"
date: 2017-05-24T16:38:13Z
draft: false

showonlyimage: false
image: "images/portfolio/local-weather-project_banner.jpg"
image_alt_text: "A photoshopped image showing the local weather app."
weight: 0

categories: [freeCodeCamp, learning, portfolio]
tags: [bootstrap, freeCodeCamp, front-end, local weather project, jQuery, web dev]
---

This web-app provides the user with local weather conditions based on their browser's geolocation data.

<!--more-->

{{< codepen id="ZKVPGZ" >}}

I designed and coded this app as part of [freeCodeCamp's](http://freeCodeCamp.org/) **Intermediate Front End Development Projects**. All in all, it took me a bit less than 9 hours to design and code.

It uses `navigator.geolocation` to find the device's latitude and longitude and then uses these coordinates to `GET` weather data from [openweathermap.org’s API](https://openweathermap.org/api) with jQuery.

**Edit**: Since completing this project, it has been moved to the **Coding Interview Take Home Projects** section of the freeCodeCamp curriculum.

### User Stories

The brief for the [Show the Local Weather](https://learn.freecodecamp.org/coding-interview-prep/take-home-projects/show-the-local-weather) project was as follows:

1. Objective: Build a CodePen.io app that is functionally similar to this: http://codepen.io/freeCodeCamp/full/bELRjV.
2. Rule #1: Don’t look at the example project’s code. Figure it out for yourself.
3. Rule #2: Fulfill the below user stories. Use whichever libraries or APIs you need. Give it your own personal style.
4. User Story: I can see the weather in my current location.
5. User Story: I can see a different icon or background image (e.g. snowy mountain, hot desert) depending on the weather.
6. User Story: I can push a button to toggle between Fahrenheit and Celsius.
7. Note: Many internet browsers now require an HTTP Secure (https://) connection to obtain a user’s locale via HTML5 Geolocation. For this reason, we recommend using HTML5 Geolocation to get user location and then use the freeCodeCamp Weather API https://fcc-weather-api.glitch.me which uses an HTTP Secure connection for the weather. Also, be sure to connect to CodePen.io via https://.
8. Remember to use Read-Search-Ask if you get stuck.
9. When you are finished, click the “I’ve completed this challenge” button and include a link to your CodePen.
10. You can get feedback on your project by sharing it with your friends on Facebook.
