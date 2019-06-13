---
title: "Timestamp Microservice"
date: 2019-03-07T17:24:57+02:00
draft: false

showonlyimage: false
image: "images/portfolio/timestamp-microservice-project_banner.jpg"
image_alt_text: "A screenshot of my take on the timestamp microservice project for freeCodeCamp."
weight: 0

categories: [freeCodeCamp, learning, portfolio]
tags: [freeCodeCamp, web dev, HTML, CSS, JavaScript, Node.js, Express.js]
---

This simple microservice responds with the Unix and UTC timestamp for any valid time (milliseconds or YYYY-MM-DD) sent to it.

<!--more-->

I built this little website for [freeCodeCamp's](http://freeCodeCamp.org/) first **APIs and Microservices Projects**.

{{< glitch project="separated-cowl" >}}

This was my first time building a microservice and it was a good first step in learning how to correctly set up my project in a Node- and Express-based environment. I learned a lot working through this one, and no doubt, I'll continue to learn a lot working through the subsequent APIs and Microservices Projects.

### User Stories

The brief for the [Timestamp Microservice](https://learn.freecodecamp.org/apis-and-microservices/apis-and-microservices-projects/timestamp-microservice/) project was as follows:

1. The API endpoint is GET [project_url]/api/timestamp/:date_string?
2. A date string is valid if can be successfully parsed by new Date(date_string).
Note that the unix timestamp needs to be an integer (not a string) specifying milliseconds.
In our test we will use date strings compliant with ISO-8601 (e.g. "2016-11-20") because this will ensure an UTC timestamp.
3. If the date string is empty it should be equivalent to trigger new Date(), i.e. the service uses the current timestamp.
4. If the date string is valid the api returns a JSON having the structure
`{"unix": <date.getTime()>, "utc" : <date.toUTCString()> }`
e.g. `{"unix": 1479663089000 ,"utc": "Sun, 20 Nov 2016 17:31:29 GMT"}`
5. If the date string is invalid the api returns a JSON having the structure
`{"error" : "Invalid Date" }`.
