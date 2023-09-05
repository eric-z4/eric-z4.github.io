---
layout: essay
type: essay
title: "Asking smart questions rather than shallow ones"
# All dates must be YYYY-MM-DD format!
date: 2023-09-03
published: true
labels:
  - Stack Overflow
  - Smart Questions
---

<img width="300px" class="rounded float-start pe-4" src="../img/asking-questions/questions-img.jpg">

## Introduction

Questions are important. They usually present an opportunity for someone to discuss something with another person or a group. This prompt for discussion may lead to a conclusive answer(s) (or more questions), but it depends on what is being asked. In the case of software engineers, there are numerous questions that are asked on forums, like Stack Overflow, and not every user has the time to answer all of them. A question like "how do I use X to do Y?" will either be met with "rtfm (read the flippin manual)" or "stfw (search the fudging web)" replies, or simply be ignored. To ensure questions are worthy to be answered, they have to be relevant, explicit, and informed.

## Asking "Smart" Questions

To show what could be considered a smart question, I found a forum post on Stack Overflow, a forum for programmers, that asks why does `window.open(url, '_blank');` not open a new tab on IMac/Safari.

```
Header: window.open(url, '_blank'); not working on iMac/Safari

I've build a web page that let's you select a page name from a drop down list and then transfers the browser to that page. The code that does the transfer is

if (url){
  window.open(url, '_blank');
}

where "url" is the page selected.
A console log just before the window.open line prints something like:

executing: window.open('http://www.mywebsite.com/44/threats.html', '_blank')

and then the browsers opens the page in a new tab.
This works fine on Windows 7 for all the browsers, including Safari.
On an iMac it works for Firefox but not for Safari.
Does anyone know why iMac/Safari won't do this?
```
[Link to the above post](https://stackoverflow.com/questions/20696041/window-openurl-blank-not-working-on-imac-safari)

### Analysis

The header of the post concisely specifies a function and an issue with said function. The asker proceeds to give background information such as the purpose for using "window.open" and what OS/browsers they have tested the code on. While they could be more specific on what browsers they used for testing, their question was sufficient enough to yield several answers such as the one below. The only major flaw with the post is that it has never selected a final answer. Due to this, it has receieved answers up to 2023 despite being posted in 2013.

```
Safari is blocking any call to window.open() which is made inside an async call.

The solution that I found to this problem is to call window.open before making an asnyc call and set the location when the promise resolves.

var windowReference = window.open();

myService.getUrl().then(function(url) {
     windowReference.location = url;
});
```

## Asking "Not so Smart" Questions

On the other hand, here is an example of a stupid question (also from Stack Overflow) that seeks a way to read a text file using JavaScript Rhino. 

```
Header: Read text file in JavaScript Rhino

I am writing a code to read a local text file into my No Magic Cameo Systems Modeler. I am using JavaScript Rhino for the same. But not getting any viable solution to read the text file.

I used Java's bufferedReader class but then I am getting the following error :

"org.mozilla.JavaScript.EvaluatorException: missing ; before statement (#25)"

Can anyone assist me in what I am doing wrong. I am fairly new to JavaScript .
```
[Link to the above post](https://stackoverflow.com/questions/71822558/read-text-file-in-JavaScript-rhino)

### Analysis

The header and the blatant "I am fairly new to JavaScript" makes it obvious that the asker is new to programming. There is little to imply that the asker has done any prior research or testing on how to "read \[a\] text file in JavaScript Rhino." In addition, the grammatical inconsistencies (e.g. lack of commas, question needs question mark, etc.) suggests that the asker does not care to proofread his work. The post only recieved one actual answer, which simply points out a syntax error.

## Conclusion

While asking questions is usually a good way to learn and improve, it requires other people to offer up their time and knowledge. There are various resources (e.g. books, websites, videos, etc.) that exist to provide answers to previously-asked questions. However, some questions might have never (or rarely) been brought up. By asking these unexplored questions in a smart way, others could spend their time learning something new or solving an obscure problem. This way, everyone in the community can benefit from a single question.
