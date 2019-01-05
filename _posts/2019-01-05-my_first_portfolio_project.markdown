---
layout: post
title:      "My First Portfolio Project!"
date:       2019-01-05 17:30:00 +0000
permalink:  my_first_portfolio_project
---


So, my first project was definitely a great learning experience... both in the program content I'm trying to learn and the confidence I have in myself. I was terrified to start it and while it definitely took me awhile to complete it, I really did enjoy it and think I learned some great problem solving skills.

Ok, so my feelings are probably not why you are here. Let's get down to what this **CLI program** actually does. I decided to focus my project on a hobby of mine. Knitting. I chose to scrape Purl Soho's website, specifically their free knitting patterns. For those unfamiliar, Purl Soho is a company who sells beautiful yarns/fabric/notions/great crafter items with lots of great patterns for several different crafts, some of those patterns being free. I enjoy free, quality knitting patterns so I thought it would be an obvious choice.

I first started out with the idea that I would scrape all the knitting patterns from this website at once and then return the details of the pattern the user chose. However, I quickly learned that would return hundreds of patterns and could easily overwhelm a user. 

Instead I built my program to do the following:
* Greet the user and offer them a list of categories of the free knitting patterns, which is a choice of 8 different options instead of the hundreds it returned in my first idea.
* Once the user picks a category, a list of all the patterns in that category is generated. The list of patterns in a category ranges from 10ish to 200ish, depending on the category.
* The user is then asked to pick a pattern from this list and the details of that pattern are then returned. At the end of the pattern the url is generated, at which point the user can click on this directly.
* Lastly, the user is prompted to chose another pattern or another category or to simply exit the program.

Easy enough, right?

Well, I definitely had some hiccups in my methods and programs. I did find myself a little confused at times on which class does what and which methods should be class methods vs instance methods. I found myself thinking almost all my methods needed to be class methods, because then I bypassed creating new instances. To a seasoned coder that probably makes little sense and I don't know that I could describe why my brain went that direction but nevertheless, it did. I can tell you I now understand the **class method** is for *functionality for the class* and an **instance method** is for *fuctionality for an instance of the class*. 

Scraping was also a fun new adventure. I am thankful for **Nokogiri **and the magic it works. I enjoyed digging into those nested arrays and figuring out just how in the world to find the name of a pattern from Purl Soho's website. And then of course the real magic of running the program and seeing all the titles I scraped show up at once. Like I said, MAGIC!

Without the videos listed on the project's page itself, I would've been totally lost. I am thankful I am able to learn from other student's projects and experiences. I am happy to say my program does what it should and while I do think there is always room for improvement I still remain proud of it. 

I hope you enjoy it!


