---
layout: post
title:      "Sorting out Sorting"
date:       2019-05-01 17:43:14 +0000
permalink:  sorting_out_sorting
---


Fullstack engineers have less emphasis on  algorithms. This is a reality. We don't bother ourselves with efficiency and we don't contemplate on doing things the smart way. But when we need to utilize certain algorithms, we go and excel at them. 

I want to cover some sorting algorithms in this article with the main reason being the frequency of the related questions during coding interviews.

You need to know some terminology before going into sorting:
-Time Scaling: With n items, how does the time needed for the algorithm to finish scale?  n is good. n^2 is acceptable but not really. Exponential is unacceptable.
-Space Needed: How much space is needed to be allocated for the algorithm?
-  Stability: This is about duplicates. Do these duplicates end up in the same order after they get sorted? If no, unstable.



-Selection Sort: n^2, inplace, stable.
-Bubble Sort: n^2, inplace, stable.
-Insertion Sort: n^2, inplace, stable.
-Shell Sort: May scale in various ways, inplace, unstable.
-k-Sort: n, inplace, stable
