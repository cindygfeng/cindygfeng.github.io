---
layout: post
title: Grad School HCI Research
# date: 
description: Research I've worked on as an HCDE grad student in the Machine Agency lab at the University of Washington. # Add post description (optional)
img: jubilee/header.jpg # Add image post (optional)
tags: [Machines, Research, HCDE, HardwareDev, Prototyping, Wiring, Tuning, Testing] # add tag
---

Last updated: 10-05-2020

I'm a part time graduate student researcher in the [<b>University of Washington Machine Agency lab</b>](https://depts.washington.edu/machines/){:target="_blank"}.  I am conducting research under the guidance of Professor Nadya Peek and HCDE PhD candidate Joshua Vasquez.  My research project is improving the build process for an open-source, extensible multi-tool motion platform (CNC machine) called [<b>Jubilee</b>](https://www.jubilee3d.com){:target="_blank"}.

### Fall 2020

I decided to try a new tool with Jubilee, and proceeded to make a pen plotting tool. Assortment of photos and gifs below.

![frame-assembly]({{site.baseurl}}/assets/img/jubilee/plotted-sheep.jpg)

![frame-assembly]({{site.baseurl}}/assets/img/jubilee/plotted-states.jpg)

<iframe width="560" height="315" src="https://www.youtube.com/embed/D2jvEphMjew" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/vff4AMWqegQ" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/DiALLmjsyYI" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

------------------------

### Summer 2020

I graduated from my Masters program but I was so excited to keep on working on Jubilee through the summer. I am still in the process of fine tuning the multi-material 3D printing. After that, I plan on making custom tool heads to take the project beyond 3D printing.

Single material flexible prints, and my first dual material cat:
![frame-assembly]({{site.baseurl}}/assets/img/jubilee/3d-assortment.jpg)

Dual material pokemon:
![frame-assembly]({{site.baseurl}}/assets/img/jubilee/dual-pokemon.jpg)

Dual material Moai head, with purge tower shown, fresh off the print!:
![frame-assembly]({{site.baseurl}}/assets/img/jubilee/dual-moai.jpg)

And here is a video of a tool change.

<iframe width="560" height="315" src="https://www.youtube.com/embed/KIAemZzsxLs" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

------------------------

### Spring 2020

In Spring 2020, because of the closure of UW campus due to COVID-19, the Machine Agency was kind enough to deliver the components so I can work on Jubilee from home.

As of June 11, 2020, the machine is a functioning dual extruder 3D printer. The machine's first duty once I got the first 3D extruder head running in May was to print parts for itself (no more dangling EMI filter!), including parts for a second extruder head. I also added some photos and contributed to pages on the [<b>Jubilee project wiki</b>](https://www.jubilee3d.com){:target="_blank"}.

![frame-assembly]({{site.baseurl}}/assets/img/jubilee/jubilee-spring2020.jpg)
![frame-assembly]({{site.baseurl}}/assets/img/jubilee/jubilee-firstparts.jpg)

Full extruder head assembly with wiring harness:

![frame-assembly]({{site.baseurl}}/assets/img/jubilee/extruder-harness.jpg)

Upon start up, the tool carriage is empty so that it can home all X, Y, Z, and U axes. The XY axes is the belt drive. the Z axes is the toolbed, and the U axis is the tool changer lock.

After sending a print in gcode format to the printer, it heats up the extruder tool to the user's set temperature and heats up the bed. When set temperatures are reached, the tool carriage picks up the tool to start printing. 

![frame-assembly]({{site.baseurl}}/assets/img/jubilee/single-toolchanging.gif)

I followed wiring diagrams for the [<b>Duet 2</b>](https://duet3d.dozuki.com/Wiki/Duet_Wiring_Diagrams/){:target="_blank"} and [<b>Duex 5</b>](https://duet3d.dozuki.com/Wiki/Duex_wiring_diagrams/){:target="_blank"} boards that are on the machine.

![frame-assembly]({{site.baseurl}}/assets/img/jubilee/jubilee-05022020.jpg)

I also found it helpful to label the wires that plug into the boards.

![frame-assembly]({{site.baseurl}}/assets/img/jubilee/jubilee-duet-labels.jpg)

Here is an old time lapse (5x speed) of it homing the X, Y, and Z axes. It automatically levels the tool bed.

![]({{site.baseurl}}/assets/img/jubilee/homing.gif)

And of course, never forget the tool squad:

![frame-assembly]({{site.baseurl}}/assets/img/jubilee/tool-squad.jpg)

------------------------

### Winter 2020

My team of 3 grad students delved into the instructions of building Jubilee, and got as far as the frame, shown below.  We focused on improving documentation and learning how to operate an existing model of Jubilee.

![frame-assembly]({{site.baseurl}}/assets/img/jubilee/frame-winter2020.jpg)


Bird's eye videos of frame assembly to include in documentation:
![frame-assembly-gif]({{site.baseurl}}/assets/img/jubilee/frameassembly.gif)