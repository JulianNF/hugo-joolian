---
title: "Exercise Tracker"
date: 2019-03-15T18:21:37+02:00
draft: false

showonlyimage: false
image: "images/portfolio/exercise-tracker-project_banner.jpg"
image_alt_text: "A screenshot of my take on the exercise tracker project for freeCodeCamp."
weight: 0

categories: [freeCodeCamp, learning, portfolio]
tags: [freeCodeCamp, web dev, HTML, CSS, JavaScript, Node.js, Express.js, MongoDB, mongoose, body-parser]
---

A simple exercise-logging web app.

<!--more-->

I built this web app for [freeCodeCamp's](http://freeCodeCamp.org/) fourth **APIs and Microservices Projects**.

{{< glitch project="coconut-turner" >}}

longer form project descripton - what worked, what didnt

The project depends on the `required` attributes of the form fields for validation. Though I have implemented server-side data validation on the `_id` fields, a more robust project would include server-side data validation on all the required form inputs, returning appropriate warnings to the user as needed.

I spent 25h15 working on this project, from start to finish, and I'm pretty pleased with the results.

### User Stories

The brief for the [Exercise Tracker](https://learn.freecodecamp.org/apis-and-microservices/apis-and-microservices-projects/exercise-tracker) project was as follows:

1. I can create a user by posting form data username to /api/exercise/new-user and returned will be an object with username and _id.
2. I can get an array of all users by getting api/exercise/users with the same info as when creating a user.
3. I can add an exercise to any user by posting form data userId(_id), description, duration, and optionally date to /api/exercise/add. If no date supplied it will use current date. Returned will the the user object with also with the exercise fields added.
4. I can retrieve a full exercise log of any user by getting /api/exercise/log with a parameter of userId(_id). Return will be the user object with added array log and count (total exercise count).
5. I can retrieve part of the log of any user by also passing along optional parameters of from & to or limit. (Date format yyyy-mm-dd, limit = int)
