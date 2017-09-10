---
title: "Image Labeller for YOLO"
layout: post
date: 2017-09-10 15:47
tag: jekyll
image: https://koppl.in/indigo/assets/images/jekyll-logo-light-solid.png
headerImage: false
projects: true
hidden: true # don't count this post in blog pagination
description: "Image Labeller"
category: project
author: fredk
externalLink: false
---

I have been using the Darknet Yolo v2 Neural Network for my map merging software. Unfortunately, training a neural network involves boring image labelling, since I was training a custom category. While doing this, I became aware of the shortcomings of many popular image labelling programs. None were able to the native YOLO format, some were slow and yet others depended on excessive Python libraries. I eventually used BBox Label Tool, and used Guanghan Ning's conversion script to get the labels into YOLO format. I did not look forward to going through this process again, and I figured it'd be a good idea to learn JavaFX either way, so I decided to build my own image labelling tool. Currently it's working but I need to add features.

![LabelDemo]({{ site.url }}/assets/labelflower.jpg)

<a href="https://it.stonybrook.edu/news/articles/kozwolski-and-torza-win-innovation-labs-3d-the-campus-competition">Link to repository</a>.
