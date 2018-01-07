---
title: "Modelling a Robot Gripper"
layout: post
date: 2018-12-27 15:58
tag: jekyll
image: https://koppl.in/indigo/assets/images/jekyll-logo-light-solid.png
headerImage: false
projects: true
hidden: true # don't count this post in blog pagination
description: "Modelling a Robot Gripper"
category: project
author: fredk
externalLink: false
---

![Go Kart Progress]({{ site.url }}/assets/gripper.jpg)

This semester I took a Machine Design class, and for my final project I chose to analyze a robot gripper, as described in the paper The GR2 Gripper: An Underactuated Hand for Open-Loop In-Hand Planar Manipulation. The GR2 gripper has the capability to reorient an object being gripped over a range of 90° without needing additional control complexity.

In my analysis, I personally did a CAD simulation to show the unique functionality of a simplified GR2, as well as a Force Analysis for an example use case.

The following images are from the paper cited.

![GR2 Design]({{ site.url }}/assets/gr2draw.gif)
![GR2 Built]({{ site.url }}/assets/gr2real.gif)


To generate a CAD model I simplified the GR2 and animated it. After running the animation, I added a measure for the distance between the two "fingers". The distance change was negligible, indicating that the object would not be ejected.

![GR2 CAD]({{ site.url }}/assets/gr2cad.png)

A kinematic analysis and force analysis were done in MATLAB with assumed data, which would be tedious to list. The point was to see if a probable situation would result in easy to achieve force requirements for the servos controlling the gripper "fingers". For an angular acceleration of 1 rad/s^2 and angular velocity of 1 rad/s the result for the moment from the drive servo was 18.2 Nm, which was a reasonable result.
