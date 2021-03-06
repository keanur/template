---
layout: project
type: project
image: images/micromouse.jpg
title: Micromouse
permalink: projects/micromouse
date: 2016
labels:
  - Robotics
  - C/C++
summary: Develop a robotic "mouse" for the 2016 UH Micromouse competition.
---

  <img class="ui large right floated rounded image" src="../images/uMouse_v2.jpg">

Micromouse is an event where small robotic “mice” solve a 16 x 16 maze. The maze is made up of a 16 by 16 gird of cells, each 180 mm square with walls 50 mm high. The mice are completely autonomous robots that must find their way from a predetermined starting position to the central area of the maze unaided.  The mouse will need to keep track of where it is, discover walls as it explores, map out the maze and detect when it has reached the center.  When it does reach the center, the mouse will typically perform additional searches of the maze until it has found the most optimal route from the start to the center.  Once the most optimal route has been determined, the mouse will run that route in the shortest possible time.

For this project I was the hardware lead, and was in charge of the hardware layout and schematic for our mouse. For this mouse we went through various revisions when it came to the method for navigating through the maze. Ultimately we settled for a side sensor mouse, which had sensors mounted to the front and sides of the mouse in order to detect its placement in the maze. We also experimented with a top down sensor, which had sensors that hung above the walls in order to sense their presence. However, this approach requires much more sensors and was more inefficient than we had anticipated.  

You can learn more at the [UH Micromouse Website](http://www-ee.eng.hawaii.edu/~mmouse/about.html).



