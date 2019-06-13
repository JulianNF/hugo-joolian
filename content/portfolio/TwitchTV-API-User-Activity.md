---
title: "TwitchTV API User Activity"
date: 2017-05-31T16:50:46Z
draft: false

showonlyimage: false
image: "images/portfolio/twitchtv-api-project_banner.jpg"
image_alt_text: "A composited screenshot of the project showing the search bar and matching TwitchTV user results."
weight: 0

categories: [freeCodeCamp, learning, portfolio]
tags: [bootstrap, font awesome, freeCodeCamp, front-end, API, TwitchTV, JSON, web dev, jQuery]
---

This web-app checks the status of various TwitchTV users and provides links to their streams if they are live.

<!--more-->

{{< codepen id="bWJgao" >}}

This project is my take on the final **Intermediate Front End Development Project** for [freeCodeCamp's](http://freeCodeCamp.org/) Front End Developer Certification

Though the styling of this one isn’t as polished as I’d like it to be, I had a lot of fun working on this challenge. My second day on this project in particular was really energizing, and saw me working a lot with createElement methods, adding simpler and clearer ways to announce the live feeds, finalizing the dynamic search, and more.

One challenge that I wasn’t able to fully resolve to my level of satisfaction was making the user’s avatar images dynamic. Unfortunately, whenever I did (and no matter what methods I tried), making the images responsive disrupted their proportions when I tested them under certain screen-size conditions.

All told, this project took me a little less than 23 hours to complete from conception to submission and was a good challenge.

Given that this is the last of the four Intermediate Front End Development Projects on freeCodeCamp, I’m happy to report that it took me 58 hours to complete all four of the challenges in this section, especially as the estimated completion time for all of these projects is 100 hours of work.

I’d love to hear your thoughts, questions, or any feedback you might have on my implementation and code. In particular, if you have any tricks for making the images responsive, I would love to figure out a tidy way to do this!

### User Stories

The brief for the [Use the Twitch JSON API](https://learn.freecodecamp.org/coding-interview-prep/take-home-projects/use-the-twitch-json-api) project was as follows:

1. Objective: Build a CodePen.io app that is functionally similar to this: https://codepen.io/freeCodeCamp/full/Myvqmo/.
2. Fulfill the below user stories. Use whichever libraries or APIs you need. Give it your own personal style.
3. User Story: I can see whether Free Code Camp is currently streaming on Twitch.tv.
4. User Story: I can click the status output and be sent directly to the Free Code Camp’s Twitch.tv channel.
5. User Story: if a Twitch user is currently streaming, I can see additional details about what they are streaming.
6. Hint: See an example call to Twitch.tv’s JSONP API at http://forum.freeCodeCamp.org/t/use-the-twitchtv-json-api/19541.
7. Hint: The relevant documentation about this API call is here: https://dev.twitch.tv/docs/v5/reference/streams/#get-stream-by-user.
8. Hint: Here’s an array of the Twitch.tv usernames of people who regularly stream: [“ESL_SC2”, “OgamingSC2”, “cretetion”, “freeCodeCamp”, “storbeck”, “habathcx”, “RobotCaleb”, “noobs2ninjas”]
9. UPDATE: Due to a change in conditions on API usage explained here Twitch.tv now requires an API key, but we’ve built a workaround. Use https://wind-bow.glitch.me/twitch-api instead of twitch’s API base URL (i.e. https://api.twitch.tv/kraken ) and you’ll still be able to get account information, without needing to sign up for an API key.
10. Remember to use Read-Search-Ask if you get stuck.
11. When you are finished, click the “I’ve completed this challenge” button and include a link to your CodePen.
12. You can get feedback on your project by sharing it with your friends on Facebook.
