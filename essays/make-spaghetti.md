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

Other than making code more legible, following some coding standards can provide other advantages such as preventing bugs. Using the [AirBnB JavaScript Style Guide](https://github.com/airbnb/javascript) as an example, one of the things that the guide recommends is to use `const` or `let` instead of `var` for variables ([Link to that section in guide](https://github.com/airbnb/javascript#references)). As mentioned in the style guide, `const` prevents the variable's value from being changed intentionally or mistakenly later on. On the other hand, `let` allows changes to the value like `var` but has the benefit of being block-scoped rather than function-scoped. What "block-scoped" means is the variable locally exists within the code block, indicated by curly braces `{...}`, it is created in. In comparison, function-scoped means the variable exists within the function without regarding the code block it is in. To further elaborate, here is an example showcasing the difference.

```
function foo() {
  for (var a = 0; a < 10; a++) {
    console.log(a);
  }
  // This will print out 10 even though "a" was declared in the for loop code block
  console.log(`"var a" value is: ${a}`);

  for (let b = 0; b < 10; b++) {
    console.log(b);
  }
  // This will result in a ReferenceError since "b" only exists in the for loop
  console.log(`"let b" value is: ${b}`);
}

foo();
```

The advantage that block-scoped has over function-scoped is the additional control over the scope that variables can exist.