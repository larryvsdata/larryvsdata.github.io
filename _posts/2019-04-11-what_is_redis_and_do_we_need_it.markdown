---
layout: post
title:      "What is Redis and Do We Need It?"
date:       2019-04-12 01:23:01 +0000
permalink:  what_is_redis_and_do_we_need_it
---


Many say that Redis is inspired fro Radish, being a non-relational database. Redis, literally meaning REmote DIctionary Server was invented for a web analyzer to overcome the overhead of traditional relational databases like MSSQL.

Unlike regular relational databases, Redis utilizes a key-value pair. Much like a hash structure in Ruby. Redis utilizes a dual process: a parent process serving the client and a second process saving the data to memory.

Much ado aside, what is the use of it? First off, it is blazing fast. Time limits may be imposed on the data and this property only exists in Redis. Financial institutions, especially those involved in stock market use Redis excessively.

Do we need to use Redis as Fullstack engineers?

Maybe yes, mostly no. Fullstack developers should stick to relational databases. However, for financial applications running on the frontend, Redis may be an option.

Life is short, let's code.
