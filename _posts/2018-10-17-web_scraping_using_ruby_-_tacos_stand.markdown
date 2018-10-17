---
layout: post
title:      "Web Scraping using Ruby - Tacos Stand"
date:       2018-10-17 23:41:59 +0000
permalink:  web_scraping_using_ruby_-_tacos_stand
---


Tha aim of this project is to provide an interface to the menu of a tacos restaurant, http://www.letstaco.com/index.html#menu-online through an interactive console.

The data scraped off the webpage is stored in an variable firstly. That is the raw data encompassing everything on the page. That data needs to parsed into chunks and stored in objects ultimately. However, right after parsing the data, we need to save them in data structures. Those data structures, lists ans hashes per se can be cast into objects. This project  needs to follow an OO pattern.

Top-down design is mandatory and crucial for software engineering. My design here stores everything in a large object, which I refer to as "First Layer". Basically, a collection of titles of sub-menus, lists of names of food, prices and descriptions. This layer hands the data over to the  "Second Layer" for further processing.

Second layer stands for a single sub-menu i.e Tacos, Burritos .. Basically, casts the information into hashes for a single item : name, price, description. It holds the subtitle in a variable, as well. Hence, this second layer is hashes plus s string for the sub-title. 

A food item object holds a price, description and a name. It has print methods to output info. It is the simples building block for the design.

Please see : https://www.youtube.com/watch?v=A3iq-DsRcfg for a complete walkthrough.
