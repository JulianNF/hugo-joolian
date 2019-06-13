---
title: "Anonymous Message Board"
date: 2019-05-22T14:27:41+02:00
draft: false

showonlyimage: false
image: "images/portfolio/anonymous-message-board-project_banner.jpg"
image_alt_text: "A photoshopped image of the final my take on freeCodeCamp's Anonymous Message Board project."
weight: 0

categories: [freeCodeCamp, learning, portfolio]
tags: [freeCodeCamp, web dev, HTML, CSS, JavaScript, Node.js, Express.js, MongoDB, body-parser, helmet.js, chai.js, chai-http, Mocha]
---

A messaging board developped from scratch, with mobile-first design.

<!--more-->

I built this project for [freeCodeCamp's](http://freeCodeCamp.org/) fifth and final **Information Security and Quality Assurance Projects**.

{{< glitch project="chiseled-squid-1" >}}

As this is the last project in freeCodeCamp's curriculum , I decided to enjoy it and take the project a few steps beyond the basic user story requirements.

Here are the key additional features I've worked on:

* I've designed the project to be more mobile-friendly, making this my first design for mobile first project. Ideally, I'd like to make the aesthetic of the project visually "lighter", but I'm already well beyond the project requirements and, for now at least, it's time to ship this puppy.
* The app/site is fully responsive and will resize itself to match the user's screen size.
* The phone bezel should disappear on mobile devices or when using device-mimicking views in a browser's developper tools. The bezel itself is pure CSS.
* I've written server-side form data validation for the key form fields. Even if the fields in all the forms are set to "required", a sneaky user who turns off this setting in the developer tools should not be able to break the API by submitting faulty data or empty fields.
* I've striven to incorporate web accessibility for this project from the start, adding titles and labels everywhere in an effort to be inclusive and provide all users equal access to the information and functionality of the site/app.
* I've chosen to make the alert messages prescribed by the user stories more informative and thorough in order to improve the user experience.
* I've added a home page that dynamically lists all the existing message boards and provides links to each one.
* That silly little clock in the status bar tells time. It was a fun few lines of code to write over a cup of tea at breakfast. ^_^
* I've went to town writing Chai TDD/assertion tests (with iteration loops, I have 134 test, all passing) in order to thoroughly test the project's functionality.
* I've also checked the spelling on the different pages.

To push myself a bit further, I chose not to use any external scripts or code snippets (e.g. for menus, sliders, etc.).

Of the bits of boilerplate code that still remain in the project (I didn't touch the freeCodeCamp testing code files), I worked a lot to tidy up and simplify all of it. This means that I:

* corrected single quotes where standards say there should be double quotes, such as in HTML tag attributes
* refactored code, expanded functionality, and combined similar code, such as with the form submission functions
* ensured that all elements on a page have unique ID attributes, particularly for dynamically added content
* updated package versions for the project and removed any unused and unnecessary packages.

### User Stories

The brief for the [Anonymous Message Board](https://learn.freecodecamp.org/information-security-and-quality-assurance/information-security-and-quality-assurance-projects/anonymous-message-board/) project was as follows:

1. Only allow your site to be loading in an iFrame on your own pages.
2. Do not allow DNS prefetching.
3. Only allow your site to send the referrer for your own pages.
4. I can POST a thread to a specific message board by passing form data text and delete_password to /api/threads/{board}.(Recomend res.redirect to board page /b/{board}) Saved will be _id, text, created_on(date&time), bumped_on(date&time, starts same as created_on), reported(boolean), delete_password, & replies(array).
5. I can POST a reply to a thead on a specific board by passing form data text, delete_password, & thread_id to /api/replies/{board} and it will also update the bumped_on date to the comments date.(Recomend res.redirect to thread page /b/{board}/{thread_id}) In the thread's 'replies' array will be saved _id, text, created_on, delete_password, & reported.
6. I can GET an array of the most recent 10 bumped threads on the board with only the most recent 3 replies from /api/threads/{board}. The reported and delete_passwords fields will not be sent.
7. I can GET an entire thread with all it's replies from /api/replies/{board}?thread_id={thread_id}. Also hiding the same fields.
8. I can delete a thread completely if I send a DELETE request to /api/threads/{board} and pass along the thread_id & delete_password. (Text response will be 'incorrect password' or 'success')
9. I can delete a post(just changing the text to '[deleted]') if I send a DELETE request to /api/replies/{board} and pass along the thread_id, reply_id, & delete_password. (Text response will be 'incorrect password' or 'success')
10. I can report a thread and change it's reported value to true by sending a PUT request to /api/threads/{board} and pass along the thread_id. (Text response will be 'success')
11. I can report a reply and change it's reported value to true by sending a PUT request to /api/replies/{board} and pass along the thread_id & reply_id. (Text response will be 'success')
12. Complete functional tests that wholely test routes and pass.
