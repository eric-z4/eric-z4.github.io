---
layout: essay
type: essay
title: "A Lesson in Reusability"
# All dates must be YYYY-MM-DD format!
date: 2023-11-23
published: true
labels:
  - Software Engineering
  - Design Patterns
---

<img width="430px" class="rounded float-start pe-4" src="../img/reusability/blueprint-image.jpg">

## Introduction

If you ever took the time to have a closer look at things, you will notice that our roofs, cars, bags, and other such things typically follow design patterns. There are different types of roofs, such as gable roofs, shed, flat, and so on; cars have an assortment of body types like a sedan or pickup truck; and bags have various designs for people to carry things in different manners (e.g. backpacks, purses, duffel bags, etc.). These design patterns do not define exact measurements or specifications. Instead, they describe a general template used to solve a particular, common problem. For instance, there are a variety of backpacks with different shapes, sizes, features, colors, etc., but they all allow people to carry things on their backs.

## In Software Engineering

Another way to think about a design pattern is as a blueprint for a house. This blueprint contains instructions for building the house but leaves the width, length, and height up to the architects to determine. The blueprint can be used to create a set of homes that perfectly fit in a city block. What I just described is a [Factory pattern](https://www.patterns.dev/vanilla/factory-pattern) in software engineering, in which a function can make multiple objects with similar properties but different values (e.g. many users with different usernames). This pattern is prevalent in the design of [React Bootstrap components](https://react-bootstrap.netlify.app/docs/components/buttons). For instance, multiple Button components can be created simply by writing `<Button />` several times (after importing it from the react-bootstrap framework). These Buttons can be individually altered by changing their properties like `variant="warning"` to make them yellow or `size="lg"` to make them big.

## Conclusion

When developing a solution for a common problem, a design pattern often gives a versatile template for creating one. Due to the generality of design patterns, they are reusable in different situations. As an example, the Factory pattern may be used to write a function that creates "car" or "cheese" objects with their corresponding properties (e.g. name, type, etc.). This pattern, among [other patterns for JavaScript and Node.js](https://www.patterns.dev/), promotes ways to reuse or modularize code, which is especially crucial in developing large web applications.
