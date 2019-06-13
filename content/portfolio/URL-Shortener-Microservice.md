---
title: "URL Shortener Microservice"
date: 2019-03-18T18:24:39+02:00
draft: false

showonlyimage: false
image: "images/portfolio/url-shortener-microservice-project_banner.jpg"
image_alt_text: "A screenshot of my take on the URL shortener microservice project for freeCodeCamp."
weight: 0

categories: [freeCodeCamp, learning, portfolio]
tags: [freeCodeCamp, web dev, HTML, CSS, JavaScript, Node.js, Express.js, MongoDB, Mongoose, body-parser]
---

<!--more-->

A microservice that generates short URLs for any valid website submitted by users. The short URLs can then be used to access the original website by simply typing in the short URL in any browser.

{{< glitch project="pinto-potato" >}}

I had a spectacular struggle with this project that I only resolved -- after much head scratching -- when I finally figured out that the MongoDB Node package included in the boiler plate code was outdated, making it impossible to use the SRV URI link that I had been using to connect to the database for the project.

### User Stories

The brief for the [URL Shortener Microservice](https://learn.freecodecamp.org/apis-and-microservices/apis-and-microservices-projects/url-shortener-microservice) project was as follows:

1. I can POST a URL to [project_url]/api/shorturl/new and I will receive a shortened URL in the JSON response.
Example : {"original_url":"www.google.com","short_url":1}
2. If I pass an invalid URL that doesn't follow the http(s)://www.example.com(/more/routes) format, the JSON response will contain an error like {"error":"invalid URL"} .
HINT: to be sure that the submitted url points to a valid site you can use the function dns.lookup(host, cb) from the dns core module.
3. When I visit the shortened URL, it will redirect me to my original link.
