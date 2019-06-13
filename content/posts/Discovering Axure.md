---
title: "Discovering Axure through the course Mastering Axure RP 7: UX Design Prototyping"
date: 2017-03-12T13:02:02Z
draft: false

showonlyimage: false
image: "images/blog/starbuck-cups_banner.jpg"
image_alt_text: "A repeating pattern of hand-drawn Starbucks coffee cups. Original image (I think) by transparentt on Tumblr."
weight: 0

categories: [learning, UI/UX]
tags: [Axure, image carousel, Mastering Axure, menu, nav bar, not working, RP, solution, Starbucks, UI/UX]
---

I’ve been poking about the edges of the world of UX/UI sketching, wireframing, and prototyping over the past few weeks and decided to take the plunge.

After a bit of reading up, I chose to start playing with Axure RP and found a class on re-creating the key elements of Starbuck’s (old) website. It was a great class (it’s been replaced, see below) that starts with 8 theory videos and followed by a further 9 videos of practice work.

The pacing of the instructions are quick and so I found myself pausing a lot to jump back and forth between Axure and the videos in order to keep on track and not miss any steps. Nothing wrong with that however, as the instructions are clear. I will however point out two things that I had to figure out on my own:

#Labels blocking the navigation menu rectangles
When building the nav menu, I found that the labels (e.g. Beans Blends Brewing, Drinks Food Nutrition) that are placed on top of the menu’s tab rectangles (e.g. Coffee, Menu, Coffeehouse) were blocking the tabs and causing the rectangles to behave in a way similar to an OnMouseOut event each time the cursor rolled over the labels.

My solution was to add OnMouseOver and OnMouseOut events to the labels in the nav bar.

Here are the interaction cases that I added:

    OnMouseEnter
		Case 1
			Set is selected of Coffee tab equal to “true”
	OnMouseOut
		Case 2
			Set is selected of Coffee tab equal to “false”

Here’s a screenshot of this solution:

![Interaction cases for the Beans Blends Brewing label](/images/blog/Interaction-cases-for-the-Beans-Blends-Brewing-label.jpg)

Please leave a comment if there’s a better way to do this. I looked around on the web but couldn’t find an “ignore” type of property for the labels, which would have been a much quicker solution.

#Some key cases are missing from the course for creating the image carousel menu
The Starbucks website includes a side menu for the image carousel and a big part of the class (~40%) involves recreating the carousel and this menu.

After following through the instructions, I found that my menu simply wasn’t working and I couldn’t figure out why. After much head scratching while trying to figure what was going on, I went back over the course video to see if I had perhaps missed a step. Nothing. Nada. Zilch.

… but I did find a still frame in the video where the instructor shows just how many cases will need to be created to make it all work, and in that still frame, I saw that there were a few extra cases that needed to be added. It seems the instructor simply forgot to mention these steps in the course, but no bother, it made for some good problem-solving practice.

In case anyone else is stumped, here is the complete set of interaction cases that you need to have for each of the images in the image carousel menu. The missing cases are the OnMouseEnter and OnMouseOut events:

![Missing interaction cases for the Starbucks image carrousel menu](/images/blog/Missing-interaction-cases-for-the-image-carrousel-menu.jpg)

#Summary
On the whole, the class is at times a bit quick, but otherwise it’s an excellent introduction and a great crash course for Axure. The course levelled up throughout at a rapid learning pace and avoided all of the tedium of childish intro videos, “real world scenarios”, and questionnaires that I have often found in other MOOC courses.

If you’re interested in taking this same course, do bear in mind that the exact course that I took (Mastering Axure RP 7: UX Design Prototyping) is no longer available on Udemy, as it has been replaced by a new class for Axure 8 by the same instructor, Radu Fotolescu.

If you’re new to Axure, I highly recommend the class that I took and can only imagine that the new course will be equally worthwhile. You can find the new course, [Learning Axure RP 8 – UX Design Fundamentals](https://www.udemy.com/axure-fundamentals/) on Udemy.