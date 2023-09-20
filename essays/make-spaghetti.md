---
layout: essay
type: essay
title: "Make Spaghetti Code look Appetizing"
# All dates must be YYYY-MM-DD format!
date: 2023-09-19
published: false
labels:
  - Software Engineering
  - Coding Standard
---

<img width="200px" class="rounded float-start pe-4" src="../img/back-to-basics/3-point-perspective.jpg">

## Introduction

If you have never heard of the term "spaghetti code," it refers to code that is difficult to understand due to not having a defined structure or way of writing. It can be confusing and frustrating for people to read, almost like an essay with no headers, transitions, or punctuation. To avoid this problem, software engineers usually have coding standards that specify the rules and guidelines for writing code. For instance, a standard for writing in JavaScript may suggest that strings should have single quotation marks rather than double quotation marks (i.e. `'example of string'` instead of `"example of string"`). There are possibly many different coding standards, but they all serve to keep code organized and consistent.

## Why would I bother with coding standards if I am just coding for myself?

Other than making code more legible, following coding standards can provide advantages such as practicing good coding habits. Using the [AirBnB JavaScript Style Guide](https://github.com/airbnb/javascript) as an example, one of the things that the guide recommends is to use `const` instead of `var` for all references by default ([Link to that section in the guide](https://github.com/airbnb/javascript#references)). As mentioned in the style guide, `const` prevents the variable's value from being changed intentionally or mistakenly when coding. If the value must be changed, the style guide suggests using `let` instead. 