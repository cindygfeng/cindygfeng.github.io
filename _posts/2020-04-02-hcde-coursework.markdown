---
layout: post
title: Grad School Projects
# date: 
description: An assortment of projects I've worked on as part of my HCDE coursework. # Add post description (optional)
img: hcde-projects/physicalprototyping-finalproject.jpg # Add image post (optional)
tags: [masters, hcde, univesityof washington, humancentereddesign] # add tag
---

In June 2020 I graduated with my Masters in Human Centered Design & Engineering.

I've been a part time grad student from 2017-2020 learning and applying all aspects of the human centered design process.  The program is largely group projects, and I have learned so much from my classmates and the HCDE department and brought a unique perspective with my mechanical engineering background as well.  Below is my coursework and some project highlights, in chronological order:

* <b>User Centered Design, HCDE 518 Fall 2017</b>
* <b>International User Experience and Communication, HCDE 512 Fall 2017</b>
* <b>Usability Studies, HCDE 517 Winter 2018</b>: Worked in team of 3 students with Alaska Airlines to conduct usability studies of the booking and airport experience for parents of children under age 2.  Involved in data synthesis and presented findings to Alaska Airlines UX team at the end of the quarter.
* <b>Qualitative Research Methods, HCDE 519 Spring 2018</b>
* <b>Information Visualization, HCDE 511 Fall 2018</b>: Worked in team of 4 HCDE and Data Science masters students to create Tableau website to visualize Seattle crime data between 2008 and 2018.  [<b>See the Tableau Seattle Crime Map here.</b>](https://public.tableau.com/profile/cindy.feng#!/vizhome/crime_seattle/SeattleCrimeMapOverview){:target="_blank"}
* <b>Physical Computing and Prototyping, HCDE 539 Fall 2018</b>: Final individual project below
* <b>Navigating Design in Organizations, HCDE 513 Winter 2019</b>
* <b>Special Topics: Digital Fabrication, HCDE 598 Spring 2019</b>: Projects below
* <b>Theoretical Foundations of Human Centered Design and Engineering, Fall 2019<b>
* <b>Master of Science Capstone, HCDE 592 and 593, Winter and Spring 2020</b>

------------------------
------------------------

### Physical Prototyping Final Project - Individual - Cardboard Wind Tunnel Simulation

<b>Autumn 2018</b> - HCDE 539 Physical Prototyping is one of the few engineering, hands-on classes in my department, so I was very excited to take it.  Though I already had Arduino experience from my undergraduate Mechanical Engineering program, I was excited to get a new circuits kit and see what I could build.  The class was mostly individual project, with the final project being open-ended.  I decided to bring some components that I already had, and build a mock up of a wind tunnel!

[<b>Download the final report here.</b>](/assets/documents/physical-prototyping-final-project.pdf){:target="_blank"}  Summary and video below!

<i>Conveying basic concepts of aerodynamic wind tunnels -- adjusting an airfoil and calculating wind speed from a pressure difference along a duct. (It blows air and rotates an airplane! Not intended to be a scientific wind tunnel)</i>

A cardboard wind tunnel using a 12V computer fan and a model airplane on an axis controlled by a servo.  The user can control the angle of attack of the plane via a potentiometer knob that is connected to the servo. The system has one pressure sensor in the airstream of the fan, and another pressure sensor behind the model plane.  The code uses a pressure difference between the two sensors to compute the duct wind speed on the rear side of the plane in the path of the air stream.  It prints this speed and the angle of attack on an LCD display.

The ATTACK ANGLE KNOB is a potentiometer whose position controls the position of the servo behind the duct (not pictured).  The servo position is mapped to the angle of attack of the airplane, which is printed on the MESSAGE DISPLAY LCD, which also displays the theoretical wind speed at the PRESSURE SENSOR 2 location.  This system does not take into account friction forces and is not intended for use as a scientific wind tunnel.

![physicalprototyping-explanation]({{site.baseurl}}/assets/img/hcde-projects/physicalprototyping-explanation.jpg)

* Connect the microcontroller to the USB port of the laptop to start the system
* Rotate the ATTACK ANGLE KNOB (slowly!) knob to control the pitch of the plane
* The MESSAGE DISPLAY LCD prints angle of attack, and wind speed at the opening of the duct

<center><iframe width="560" height="315" src="https://www.youtube.com/embed/P0JwScpqCy8" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></center>

------------------------
------------------------

### Digital Fabrication Projects - Individual

<b>Spring 2019</b> - HCDE 598 Digital Fabrication was a special topics engineering class which I am so grateful to have taken, because that's how I was introduced to the Machine Agency, a lab that I am now a part of!  Below are some of the assignments I completed as part of the Digital Fabrication class, in which we used CAD and slicer programs (Rhino 3d, Fusion360, OnShape, Prusa, etc.) and used a variety of CNC fabrication methods (milling, 3D printing, lasercutting, etc.).

------------------------

<b>Repeated lasercut shapes using 2 different thicknesses.  Software used: Rhino 3D, Grasshopper, and Adobe Illustrator.</b>

![dfab]({{site.baseurl}}/assets/img/hcde-projects/dfab-lasercut.jpg)

![dfab]({{site.baseurl}}/assets/img/hcde-projects/dfab-lasercut-assembly.jpg)

------------------------

<b>Milled a sheet of FR-1 (blank PCB material) to assemble a tiny box. In the future since I have some more FR-1 sheets, I hope to mill PCB boards of my own designs. Software used: Fusion360, Bantam Tools</b>

![dfab]({{site.baseurl}}/assets/img/hcde-projects/dfab-milling-process.jpg)

![dfab]({{site.baseurl}}/assets/img/hcde-projects/dfab-box-sides.jpg)

![dfab]({{site.baseurl}}/assets/img/hcde-projects/dfab-boxassembly.jpg)

------------------------

<b>3D printed a propeller keychain in 2 pieces, with a pin in between! Software used: Onshape, Fusion360, Dremel DigiLab 3D Slicer</b>

![dfab]({{site.baseurl}}/assets/img/hcde-projects/dfab-onshape-blades.jpg)

![dfab]({{site.baseurl}}/assets/img/hcde-projects/dfab-onshape-assembly.jpg)

![dfab]({{site.baseurl}}/assets/img/hcde-projects/dfab-printed-propeller.jpg)

![dfab]({{site.baseurl}}/assets/img/hcde-projects/dfab-propeller-assembly.jpg)

![dfab]({{site.baseurl}}/assets/img/hcde-projects/dfab-propeller.gif)

------------------------

<b>Molding and casting of climbing foot holds (not for actual climbing use).  Milled machineable wax to create a tool for the mold.  Software used: Fusion360, Bantam Tools

![dfab]({{site.baseurl}}/assets/img/hcde-projects/dfab-bantam-isometricview.jpg)

![dfab]({{site.baseurl}}/assets/img/hcde-projects/dfab-mill-progress.gif)

![dfab]({{site.baseurl}}/assets/img/hcde-projects/dfab-mold-prep.jpg)

![dfab]({{site.baseurl}}/assets/img/hcde-projects/dfab-mold-cured.jpg)

![dfab]({{site.baseurl}}/assets/img/hcde-projects/dfab-plaster-cure.jpg)

After the plaster cured, but before finishing the surface from sand blasting.  Notice the plaster wasn't mixed thoroughly for one of the holds!

![dfab]({{site.baseurl}}/assets/img/hcde-projects/dfab-plaster-holds.jpg)