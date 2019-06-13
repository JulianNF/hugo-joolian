---
title: "Markdown Previewer"
date: 2019-01-21T13:06:01+02:00
draft: false

showonlyimage: false
image: "images/portfolio/markdown-previewer-project_banner.jpg"
image_alt_text: "A composited image showing a screenshot of the project in the background, with the Markdown logo overlaid on top."
weight: 0

categories: [freeCodeCamp, learning, portfolio]
tags: [freeCodeCamp, front-end, markdown previewer project, web dev, CSS, responsive, SASS, HTML, JavaScript, React, marked.js]
---

A markdown previewer that dynamically updates HTML output in one window pane when you type markdown in the adjacent window pane.

<!--more-->

I built this previewer for [freeCodeCamp's](http://freeCodeCamp.org/) second **Front End Libraries Projects**.

{{< codepen id="WLWero" >}}

Nothing major to report for this project. Things went smoothly and I learned a bunch more about markdown syntax, which was nice. From start to finish, the project took me 18h30 to complete, including research and working on the optional bonus requirements.

### User Stories

The brief for the [Build a Markdown Previewer](https://learn.freecodecamp.org/front-end-libraries/front-end-libraries-projects/build-a-markdown-previewer) project was as follows:

1. I can see a textarea element with a corresponding id="editor".
2. I can see an element with a corresponding id="preview".
3. When I enter text into the #editor element, the #preview element is updated as I type to display the content of the textarea.
4. When I enter GitHub flavored markdown into the #editor element, the text is rendered as HTML in the #preview element as I type (HINT: You don't need to parse Markdown yourself - you can import the Marked library for this: https://cdnjs.com/libraries/marked).
5. When my markdown previewer first loads, the default text in the #editor field should contain valid markdown that represents at least one of each of the following elements: a header (H1 size), a sub header (H2 size), a link, inline code, a code block, a list item, a blockquote, an image, and bolded text.
6. When my markdown previewer first loads, the default markdown in the #editor field should be rendered as HTML in the #preview element.
7. Optional Bonus (you do not need to make this test pass): When I click a link rendered by my markdown previewer, the link is opened up in a new tab (HINT: read the Marked.js docs for this one!).
8. Optional Bonus (you do not need to make this test pass): My markdown previewer interprets carriage returns and renders them as br (line break) elements.
