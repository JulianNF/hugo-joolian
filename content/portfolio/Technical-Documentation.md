---
title: "Technical Documentation"
date: 2018-10-09T14:33:48+02:00
draft: false

showonlyimage: false
image: "images/portfolio/technical-documentation-project_banner.jpg"
image_alt_text: "A composited image showing multiple screenshots of the project, stacked on top of each other as though there are a pile of printed papers."
weight: 0

categories: [freeCodeCamp, learning, portfolio]
tags: [freeCodeCamp, front-end, technical documentation project, web dev, CSS, responsive, HTML]
---

A sample documentation reference website built using pure CSS.

<!--more-->

I built this little website for [freeCodeCamp's](http://freeCodeCamp.org/) fourth **Responsive Web Design Projects**.

{{< codepen id="gBaeYg" >}}

I kept this one simple, working to implement best-practice design principles to make the documentation as easy to navigate and read as possible. Thought the design is responsive (enough to work in split-screen mode on the average computer), I chose not to implement a collapsing menu, as I thought this would detrimentally affect usability for the most common use cases (i.e. quick reference and ability to jump around the document while coding on a computer).

### User Stories

The brief for the [Build a Technical Documentation Page](https://learn.freecodecamp.org/responsive-web-design/responsive-web-design-projects/build-a-technical-documentation-page) project was as follows:

1. I can see a main element with a corresponding id="main-doc", which contains the page's main content (technical documentation).
2. Within the #main-doc element, I can see several section elements, each with a class of main-section. There should be a minimum of 5.
3. The first element within each .main-section should be a header element which contains text that describes the topic of that section.
4. Each section element with the class of main-section should also have an id that corresponds with the text of each header contained within it. Any spaces should be replaced with underscores (e.g. The section that contains the header "Javascript and Java" should have a crresponding id="Javascript_and_Java").
5. The .main-section elements should contain at least 10 p elements total (not each).
6. The .main-section elements should contain at least 5 code elements total (not each).
7. The .main-section elements should contain at least 5 li items total (not each).
8. I can see a nav element with a corresponding id="navbar".
9. The navbar element should contain one header element which contains text that describes the topic of the technical documentation.
10. Additionally, the navbar should contain link (a) elements with the class of nav-link. There should be one for every element with the class main-section.
11. The header element in the navbar must come before any link (a) elements in the navbar.
12. Each element with the class of nav-link should contain text that corresponds to the header text within each section (e.g. if you have a "Hello world" section/header, your navbar should have an element which contains the text "Hello world").
13. When I click on a navbar element, the page should navigate to the corresponding section of the main-doc element (e.g. If I click on a nav-link element that contains the text "Hello world", the page navigates to a section element that has that id and contains the corresponding header.
14. On regular sized devices (laptops, desktops), the element with id="navbar" should be shown on the left side of the screen and should always be visible to the user.
15. My Technical Documentation page should use at least one media query.
