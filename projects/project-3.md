---
layout: project
type: project
image: images/CollectGame.png
title: Item Collecting
permalink: projects/collecting
date: 2016
labels:
  - Lisp
  - GitHub
summary: A graphical game created for ICS 111.
---

<img class="ui image" src="{{ site.baseurl }}/images/CollectGameRect.png">

## The game

This game was created by myself, though I used the EZ Graphics package. The goal is simple: collect all of the fruits. Hitting the toxic waste subtracts a point each time.

This game was our second project for the class and demonstrates our knowledge of object oriented programming.

There is a point counter in the corner of the screen. For every fruit that you collect, the counter increments by one. The goal is to just collect all of the fruits with a score higher than 0.

If the player hits the toxic waste, the pointer decrements by one. If the score reaches 0, you lose and the program terminates.
