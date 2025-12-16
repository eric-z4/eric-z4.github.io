---
layout: project
type: project
image: img/two-dice-pig/two-dice.jpg
title: "Two-dice Pig"
date: 2021-11-11
published: false
labels:
  - Java
summary: "A simple game of two dice pig that I developed for an ICS 111 assignment"
---

<img class="img-fluid" src="../img/two-dice-pig/two-dice-pig-snippet.png">

## About

Two-dice Pig is a variation of the dice game called [Pig](https://en.wikipedia.org/wiki/Pig_(dice_game)). It is a two player game that involves a pair of dice and the following rules when a player rolls the dice:
- If neither dice is 1, the sum of the dice is added to the turn total
- If one of the dice is 1, the player ends their turn and scores nothing
- If both of the dice is 1, the player loses their current score and ends their turn
- If a double is rolled, the sum of the dice is added to the turn total and the player must roll again
Each player can either hold or roll. Holding will add their turn's total points to their score and passes the turn to the other player. Rolling allows the player to possibly earn more points, but runs the risk of either earning nothing or losing everything. The goal is to be the first to get a score of 100.

I was responsible for recreating two-dice Pig in Java with GUI elements. I used components from Java Swing, a GUI widget toolkit, to create the visuals for the dice, player panels, and turn summary. This was made for an assignment when I was in ICS 111.

## Experience

Before I did this assignment, the programs I developed mainly used a console or web browser to display its contents. The two-dice Pig game has helped me gain some experience using Java and designing GUIs with Java Swing.

Source: <a href="https://github.com/eric-z4/two-dice-pig"><i class="large github icon "></i>eric-z4/two-dice-pig</a>
