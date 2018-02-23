---
title: The law of large numbers animation in R
categories: 
 - R
 - Statistics
tags:
 - R
 - Animations
 - Plots
---

The law of large numbers explains why repeatedly sampling from a population is something we want to do. Assume we want to determine the sex-ratio of a population by sampling individuals and determining their sex as feminine or masculine. The sex-ratio represents the probability of finding a male or a female, depending on the code we assign to either sex, and can be modelled using a ![Bernoulli distribution](https://en.wikipedia.org/wiki/Bernoulli_distribution). If we sample individuals repeatedly and start accumulating all the information to calculate the proportion of females (coded 1) sampled after N individuals have been evaluated, we will see that the obtained proportion will approach the true proportion as sample size grows.

I published code to visualize this using the R package 'animation' as a gist:

{% gist 33fed7c29a1e2748eac4da371fb003a4 %}

You will hopefully get an animated gif (i.e. Law_of_Large_Numbers.gif) looking like this:

![](https://i.imgur.com/4U14J94.gif)
  
