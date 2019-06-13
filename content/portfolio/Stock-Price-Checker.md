---
title: "Stock Price Checker"
date: 2019-04-26T18:26:50+02:00
draft: false

showonlyimage: false
image: "images/portfolio/stock-price-checker-project_banner.jpg"
image_alt_text: "A screenshot of my take on the stock price checker project for freeCodeCamp."
weight: 0

categories: [freeCodeCamp, learning, portfolio]
tags: [freeCodeCamp, web dev, HTML, CSS, JavaScript, Node.js, Express.js, MongoDB, body-parser, jQuery, request package, helmet.js, chai.js, chai-http, Mocha]
---

An app that uses stock ticker symbols to report the stock's price and its recorded number of ¨likes¨. The app also allows comparing two stocks to see their relative number of likes (i.e. which stock is most popular between the two, and by how much).

<!--more-->

I built this app for [freeCodeCamp's](http://freeCodeCamp.org/) fourth **Information Security and Quality Assurance Projects**.

{{< glitch project="inquisitive-mandolin" >}}

FreeCodeCamp proposed using Google Finance's API to retrieve stock price data; unfortunately, this API has not been accessible for some time. Instead, I chose to use [Alpha Vantage](https://www.alphavantage.co) for the project. The limits imposed by this service (5 request per minute) seriously complicated the test cases I wrote in Chai/Mocha. To resolve the issue, I implemented an `afterEach()` function containing a 20 second `setTimeout()` delay. This was designed to reduce the test suite to less than 5 API requests per minute. 

This project also saw me learn how to pass headers (`.set()`) and query parameters (`.query()`) in my Chai tests, a lesson that took me unfortunately longer than expected to figure out, but that I'm sure will prove itself very useful in the future.

### User Stories

The brief for the [Stock Price Checker](https://learn.freecodecamp.org/information-security-and-quality-assurance/information-security-and-quality-assurance-projects/stock-price-checker) project was as follows:

1. Set the content security policies to only allow loading of scripts and css from your server.
2. I can GET /api/stock-prices with form data containing a Nasdaq stock ticker and recieve back an object stockData.
3. In stockData, I can see the stock(string, the ticker), price(decimal in string format), and likes(int).
4. I can also pass along field like as true(boolean) to have my like added to the stock(s). Only 1 like per ip should be accepted.
5. If I pass along 2 stocks, the return object will be an array with both stock's info but instead of likes, it will display rel_likes(thedifference betwwen the likes) on both.
6. A good way to recieve current price is the following external API(replacing 'GOOG' with your stock): https://finance.google.com/financeinfo?q=NASDAQ%3aGOOGAll
7. 5 functional tests are complete and passing.
