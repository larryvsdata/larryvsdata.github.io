---
layout: post
title:      "Virtual Farm with JS Frontend"
date:       2019-02-04 02:49:45 +0000
permalink:  virtual_farm_with_js_frontend
---



My virtual farm project sparked interest of some people, at least the people who are into the online gaming and commerce. It was about having virtual farms, potentially containing real animals sitting in real embodiments of them somewhere.

This time, I flexed my muscles in Javascript and strived to make the interface friendlier to the end user. Rails does a good job on frontend but Rails comes up short from time to time.

With all these being said, let's talk about the newly added features: 

On the index page, info of each farm is truncated and a 'More Info ' button opens up the full description. Animal lists of each farm were added at the end to showcase the serialization.

Show pages bear a next link to display the next farm info and shuffle through all farms quickly.

Most involved part is the comments section at the bottom of the index page. Anyone can write a comment there anonymously and LIKE & DISLIKE buttons are attached to each comment simultaneously. Like and dislike counts are displayed on these buttons. All of these informations are sent to backend using AJAX and retrieved back to the frontend. Hence, nothing vanished if the page is refreshed.

For the admin, a separate DELETE button is attache, enabling the admin to delete the comment.

I think this project is richer now as the comments section brought in a social aspect.

