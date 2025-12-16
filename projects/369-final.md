---
layout: project
type: project
image: img/369-final/clip1.png
title: "ICS 369 Final Project"
date: 2025-4-11
published: true
labels:
  - Python
  - Maya
summary: "An ICS 369 animation project using python to create simple particle systems."
---
<video width="960" height="540" controls>
	<source src="img/369-final/ICS369_HW5_ericzhou.mp4" type="video/mp4">
</video>

## About

This was my final project for ICS 369, which was made and rendered in [Maya](https://www.autodesk.com/products/maya/overview). The goal was to use Python to create and animate several particle systems in a ~30 second animation. This was achieved by using Maya's [script editor](https://help.autodesk.com/view/MAYAUL/2024/ENU/?guid=GUID-55B63946-CDC9-42E5-9B6E-45EE45CFC7FC) to create objects, set materials, set transforms, add keyframes, etc. For instance, the speed lines, asteroids, clouds, and trees are some of the particle systems that are included in the animation that I made. Other models, such as the UFO and cow, were manually created and animated.

## Experience

ICS 369 was where I used scripts to animate for the first time. I also extensively utilized classes and first-class functions to create a custom particle system with emitters and forces. To make the clouds at 0:14, for example, an emitter spawns in a set number of randomly-sized spheres that are pushed outward by a point force in the center.