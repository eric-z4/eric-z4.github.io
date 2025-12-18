---
layout: project
type: project
image: img/369-final/clip1.png
title: "ICS 369 Final Project"
date: 2025-11-4
published: true
labels:
  - Python
  - Maya
summary: "An ICS 369 animation project using python to create simple particle systems."
---
<video width="960" height="540" controls>
	<source src="ICS369_HW5_ericzhou.mp4" type="video/mp4">
</video>

## About

This was my final project for ICS 369, which was made and rendered in [Maya](https://www.autodesk.com/products/maya/overview). The goal was to use Python to create and animate several particle systems in a ~30 second animation. This was achieved by using Maya's [script editor](https://help.autodesk.com/view/MAYAUL/2024/ENU/?guid=GUID-55B63946-CDC9-42E5-9B6E-45EE45CFC7FC) to create objects, set materials, set transforms, add keyframes, etc. For instance, the speed lines, asteroids, clouds, and trees are some of the particle systems that were made using a Python script. Other models, such as the UFO and cow, were manually created and animated.

## Experience

ICS 369 was where I used scripts to animate for the first time. I also extensively utilized classes and first-class functions in my particle system script to have customizable emitters and forces. For instance, I can set the amount of objects an emitter emits per frame, how long it will emit for, what the particle's polygon/model will be, the area that particles can spawn in, and so on. 

Below is a snippet showing the emitter class and all the properties that can be set.

{% gist bcad1fbf27ee64e3d7c68fc8c55a9dca %}

The entire script can be viewed in [this gist](https://gist.github.com/eric-z4/00e3a46cade54cb699a09d1b7b08d3dd)