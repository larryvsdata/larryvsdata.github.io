---
layout: post
title:      "Hashes, Dictionaries, Hashtables"
date:       2019-05-07 22:58:54 +0000
permalink:  hashes_dictionaries_hashtables
---


A lot of developers refer to hashes but not very many people understand how hashes operate. In this article, I want to elucidate how hashes are designed and working logic behind them.

Hashes go by different names in different programming languages like hashtable, dictionary etc. Hashes are preferred because appropriate values are accessed via corresponding  keys in constant time. Or else people presume so.

Hashes are nothing but a list. It is the hash function that maps the key to the value. The keys are input into a hashfunction that returns the location of the corresponding value to be put into. This is the whole magic behind the scenes.

The delusion with the constant time is partially accurate. If there is a collision between two keys, which is if two keys have the same hashvalue, then linear probing has to be utilized. Then, the search process takes linear time.

Everyone should be familiar with these concepts and better should implement hashes from scratch to get a better understanding.

Life is short, let's code.
