---
title: "File Metadata Microservice"
date: 2019-03-25T17:25:44+02:00
draft: false

showonlyimage: false
image: "images/portfolio/file-metadata-microservice-project_banner.jpg"
image_alt_text: "A screenshot of my take on the file metadata microservice project for freeCodeCamp."
weight: 0

categories: [freeCodeCamp, learning, portfolio]
tags: [freeCodeCamp, web dev, HTML, CSS, JavaScript, Node.js, Express.js, multer]
---

A microservice that responds with the file name, file type, and file size metadata of any file uploaded to it.

<!--more-->

I built this microservice for [freeCodeCamp's](http://freeCodeCamp.org/) fifth and final **APIs and Microservices Projects**.

{{< glitch project="axiomatic-charger" >}}

Everything went smoothly with this project, and it took me 5h30 to complete from start to finish, of which a good third was me messing around with styling.

### User Stories

The brief for the [File Metadata Microservice](https://learn.freecodecamp.org/apis-and-microservices/apis-and-microservices-projects/file-metadata-microservice) project was as follows:

1. I can submit a form object that includes a file upload.
2. The from file input field has the "name" attribute set to "upfile". We rely on this in testing.
3. When I submit something, I will receive the file name, and size in bytes within the JSON response.
