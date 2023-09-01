---
layout: project
type: project
image: img/racing-game/racing-game-snippet.png
title: "Untitled Racing Game"
date: 2019-07-18
published: true
labels:
  - Game Development
  - Javascript
  - p5js
summary: "A racing game that I made during my junior year in high school."
---

<div class="text-center p-4">
  <img width="500px" src="../img/racing-game/racing-game-full.png" class="img-thumbnail">
  <img width="500px" src="../img/racing-game/racing-game-full-alt.png" class="img-thumbnail">  
</div>

## About

This was a personal project that I created in 2019 (along with Grid Snake) to experiment with [p5js](https://p5js.org/), a Javascript library that includes various creative tools, and to practice programming in Javascript. It is a minimalistic racing game where the player drives through the two courses (shown above) as fast as you can. There are no obstacles, no boosts, and no gimmicks; there is only the "car" and the finish line. 

Since this project was made a few years ago, the code is not the most organized, polished, nor smart. Due to how I programmed the collision detection (using functions from [p5.collide2D](https://github.com/bmoren/p5.collide2D), there are a few places against the walls that will push the player in an unintended way (e.g. out of bounds). Nonetheless, the project was mostly intended for testing my programming knowledge at the time.

## Experience

When I created this project, I realized how much programming it takes to create a game from scratch. Since I wanted to make freeform tracks, I also needed a way to program the collision for the walls of each track. I did this by finding the intersection of the four lines from the "car" (see left image) and the walls. By finding these intersections, I am basically finding the farthest point the "car" can go in the four directions.
