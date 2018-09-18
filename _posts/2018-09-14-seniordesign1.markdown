layout: post
date: 2018-09-14 13:19
tag: jekyll
image: https://koppl.in/indigo/assets/images/jekyll-logo-light-solid.png
headerImage: false
projects: true
hidden: true # don't count this post in blog pagination
description: "Senior Design Week 1"
category: project
author: fredk
externalLink: false
---
My group and I chose to design and build a 6 degree of freedom motion platform. The idea is to use this in conjunction with a VR headset and a flight simulator, to replicate the feeling of flying. Below is a picture of a setup someone else built, this sort of design is called a Stewart platform.

![LabelDemo]({{ site.url }}/assets/stewart.gif)

While we’re excited about this project, I’m concerned about the budget. We have a budget of $840, which is not enough for a project like this. $840 will hardly cover the cost of the motors and gearboxes for creating a motion platform. There are, however, a few ways around this.
I hope that there is some way to do this project on a budget. Seeing how one of the design constraints was creating a product that could be marketed towards the flight simulation hobbyist, budget is a gigantic concern, since a hobbyist would not consider buying products available today, which will cost around $3000 when DIYed. $840 is quite low though, and while I am not opposed to spending some of my own money to achieve the project, I would like to not spend more than I need to.
With such a small budget, I’ll need to either consider scaling down the project, maybe by reducing it to a 3 degree of freedom platform, or by trying to innovate, and create a novel product that will cost less. Through my research, I have found that the greatest costs in the production of the motion platform are the gearboxes, motors, and power supply. Generally, most ideas I’ve had are related to reducing the load that needs to be handled by the platform.
Counterweighting the platform in some way would reduce the load but would increase the total inertia of the platform. This may not end up with cheaper motors, since while the motors won’t be carrying the full load, they will still have to accelerate a larger mass.
Another idea is to place the platform on a spring, then the only force needed would be to move the platform by a certain distance, assisted by the spring. The issue then is that the spring needs to be factored into force calculations, and the resulting oscillations need to be controlled. An offshoot of this idea is to place a hydraulic cylinder under the motion platform and let that hold the weight.
I think that for force generation, we’ll be choosing between linear actuators and DC motors. Hydraulics seem too expensive and brushless motors are worse than brushed DC motors for this application.
For power, I don’t think that mains power will be enough. If one of the ideas ends up working, and less power will be needed to shift the user’s weight, we may end up using mains power. Otherwise, we’ll end up using a battery pack.
By next week, hopefully we’ll have a finalized budget and 3 designs from which to choose from.


