---
layout: post
title:      "Webpage for a Condensed Matter Theory Group - Sinatra"
date:       2018-11-26 06:22:01 +0000
permalink:  webpage_for_a_condensed_matter_theory_group_-_sinatra
---

 # I aimed to build a webpage for a research group that is editable and pretty much generic.


There is one professor having the previliges to add members to the group and delete them of the webpage. Professor is the group leader and the sole administrator of the webpage. The professor can be edited but cannot be deleted. This is more or less singleton pattern used by Java developers.

There are postdocs and graduate students. There is a many to many relationship in between them. Activerecord handles all database relations. Graduate students may or may not be delegated to postdocs.

Sign up, edit, delete .. take effect on the group webpage, which is also the index page.

