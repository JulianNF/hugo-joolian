---
title: "Personal Library"
date: 2019-04-19T11:27:13+02:00
draft: false

showonlyimage: false
image: "images/portfolio/personal-library-project_banner.jpg"
image_alt_text: "A screenshot of the finished version of my Personal Library project."
weight: 0

categories: [freeCodeCamp, learning, portfolio]
tags: [freeCodeCamp, web dev, HTML, CSS, JavaScript, jQuery, Node.js, Express.js, MongoDB, body-parser, helmet.js, chai.js, chai-http, Mocha]
---

A web app where users can add/remove book titles and also add and view comments to each of the books in the library.

<!--more-->

I built this little web app for [freeCodeCamp's](http://freeCodeCamp.org/) third **Information Security and Quality Assurance Projects**.

{{< glitch project="sunrise-raft" >}}

Nothing major to report on this project, other than it was nice to work a bit more with jQuery and to wake up in the mornings with ideas on how to improve the functionality of the web app.

### User Stories

The brief for the [Personal Library](https://learn.freecodecamp.org/information-security-and-quality-assurance/information-security-and-quality-assurance-projects/personal-library) project was as follows:

1. Nothing from my website will be cached in my client as a security measure.
2. I will see that the site is powered by 'PHP 4.2.0' even though it isn't as a security measure.
3. I can post a title to /api/books to add a book and returned will be the object with the title and a unique _id.
4. I can get /api/books to retrieve an aray of all books containing title, _id, & commentcount.
5. I can get /api/books/{_id} to retrieve a single object of a book containing title, _id, & an array of comments (empty array if no comments present).
6. I can post a comment to /api/books/{_id} to add a comment to a book and returned will be the books object similar to get /api/books/{_id}.
7. I can delete /api/books/{_id} to delete a book from the collection. Returned will be 'delete successful' if successful.
8. If I try to request a book that doesn't exist I will get a 'no book exists' message.
9. I can send a delete request to /api/books to delete all books in the database. Returned will be 'complete delete successful' if successful.
10. All 6 functional tests requiered are complete and passing.
