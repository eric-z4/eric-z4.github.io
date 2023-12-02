---
layout: essay
type: essay
title: "Using the Tools for the Job"
# All dates must be YYYY-MM-DD format!
date: 2023-12-1
published: true
labels:
  - Software Engineering
  - Development Environments
  - Frameworks
---

<img width="415px" class="rounded float-start pe-4" src="../img/tools-for-job/software-toolbox.png">

## Introduction

In my software engineering class, I learned about various concepts such as functional programming, development environments, and user interface frameworks. These were taught in the context of designing a web application, leading up to a [web app project I worked on with a group](https://rainbows-gallery.github.io/) using the [Meteor](https://www.meteor.com/) framework. However, these software engineering concepts apply to much more than just web app development. 

## A Suitable Environment

An integrated development environment (IDE) is a software tool that provides many helpful features for programming and developing software. They may include an autocomplete for faster coding, a built-in file browser for quick access to files, and a syntax highlighter to check for mistakes in writing code. There are many different development environments like [IntelliJ Idea](https://www.jetbrains.com/idea/), [Eclipse](https://eclipseide.org/), and [Visual Studio](https://visualstudio.microsoft.com/). While IDEs can be complicated, they allow software engineers to develop and edit larger software systems. For instance, something as simple as renaming a variable can be tedious since there could be multiple references to that variable hidden within a sea of code. IntelliJ Idea offers several ways of dealing with this: selecting the variable will [highlight](https://www.jetbrains.com/help/rider/Navigation_and_Search__Finding_Usages__Highlighting_Usages_in_File.html) other places it is used; inputting the variable into the [find feature](https://www.jetbrains.com/help/idea/finding-and-replacing-text-in-file.html#findInSelection) will also mark where they are; and using the [rename refactoring](https://www.jetbrains.com/help/idea/rename-refactorings.html) (renaming without altering functionality) option will automatically change every instance of said variable.

## Building on a Foundation

A framework refers to a library that contains objects and utilities typically used as a foundation for some aspect of software development. To elaborate from before, Meteor is a web application framework that includes features like user accounts, database functions, and the ability to run the app locally. Besides Meteor, there are also [React Native](https://reactnative.dev/) and [Flutter](https://flutter.dev/), which are mobile app frameworks. They both have various user interface components (e.g. buttons, text fields, etc.), functions for detecting taps on a touchscreen, and other uses that I have not yet explored. These frameworks help software engineers quickly develop a web or mobile app without coding most of the individual components from scratch. Other than frameworks, some libraries mainly provide functions, such as [Underscore.js](https://underscorejs.org/) and [p5.js](https://p5js.org/). While not quite as large as frameworks, they are still convenient for simplifying code. For example, Underscore.js has the function [`every`](https://underscorejs.org/#reject), which takes an array of values, checks each value with a given function, and returns true if all values also return true in the function. This would usually need a for loop, an if statement, and a variable to store whether all values were true or a value was false, but `every` condenses it into one function. In general, libraries can assist software engineers by providing a template or tools for development.

## Conclusion

As shown, both IDEs, frameworks, and likely other software concepts are essential for any software development. IDEs and frameworks provide numerous tools for software engineers, which would be better than using something like Notepad to code everything from the ground up. While I have used these tools for web application development, I could also use them for any project in the future.

