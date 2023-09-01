---
layout: project
type: project
image: img/snake/snake-logo.png
title: "Grid Snake"
date: 2019-04-24
published: true
labels:
  - Game Development
  - Javascript
  - p5js
summary: "A game of Snake that I made during my junior year in high school."
---

<img class="img-fluid" src="../img/snake/snake-full.png">

## About

This was a personal project that I created in 2019 (along with the racing game) to experiment with [p5js](https://p5js.org/), a Javascript library that includes various creative tools, and to practice programming in Javascript. The game involves a snake (the green boxes) that never stops moving. As the snake, the player must navigate around the grid to collect food (the yellow boxes) and avoid crashing into a wall or their body.

With the exception of p5js, I developed the entire project on my own. I was able to create the grid by using a double for loop to find the coordinates for the grid lines. For the snake body to follow the head, I used two arrays that kept track of their current x and y coordinates. Whenever the head moves, the coordinates of the closest body is assigned the head's previous position, and the coordinates of the following bodies are assigned the old position of the body in front of them. There are improvements to be made with the code, but I made this when I only had some experience with Javascript.

## Experience

I learned about 
