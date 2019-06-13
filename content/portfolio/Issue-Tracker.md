---
title: "Issue Tracker"
date: 2019-04-15T11:26:37+02:00
draft: false

showonlyimage: false
image: "images/portfolio/issue-tracker-project_banner.jpg"
image_alt_text: "A screenshot of my take on the issue tracker project for freeCodeCamp."
weight: 0

categories: [freeCodeCamp, learning, portfolio]
tags: [freeCodeCamp, web dev, HTML, CSS, JavaScript, Node.js, Express.js, MongoDB, body-parser, helmet.js, chai.js, chai-http, Mocha]
---

Keep track of issues for various projects by adding, viewing, updating, and deleting issue reports.

<!--more-->

I built this app for [freeCodeCamp's](http://freeCodeCamp.org/) second **Information Security and Quality Assurance Projects**.

{{< glitch project="polar-zenith" >}}

No issues to report ^_^ while putting together this project. Everything went smoothly and I took the time to play with my original design in an effort to make it more compact and also worked on accessibility. Total project time from design to submission was 24h30.

### User Stories

The brief for the [Issue Tracker](https://learn.freecodecamp.org/information-security-and-quality-assurance/information-security-and-quality-assurance-projects/issue-tracker) project was as follows:

1. Prevent cross site scripting(XSS attack).
2. I can POST `/api/issues/{projectname}` with form data containing required issue_title, issue_text, created_by, and optional assigned_to and status_text.
3. The object saved (and returned) will include all of those fields (blank for optional no input) and also include created_on(date/time),updated_on(date/time), open(boolean, true for open, false for closed), and _id.
4. I can PUT `/api/issues/{projectname}` with a _id and any fields in the object with a value to object said object. Returned will be 'successfully updated' or 'could not update '+_id. This should always update updated_on. If no fields are sent return 'no updated fieldsent'.
5. I can DELETE `/api/issues/{projectname}` with a _id to completely delete an issue. If no _id is sent return '_id error', success: 'deleted +_id, failed: 'could not delete '+_id.
6. I can GET `/api/issues/{projectname}` for an array of all issues on that specific project with all the information for each issue as wasreturned when posted.
7. I can filter my get request by also passing along any field and value in the query(ie. `/api/issues/{project}?open=false)`. I can pass along as many fields/values as I want.
8. All 11 functional tests are complete and passing.
