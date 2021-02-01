---
layout: page
title: MASH Particles
permalink: /MASH_Particles/
---
# MASH Particles

An aspect 3D modeling that I found especially interesting is special effects. In this age of huge blockbuster movies, being able to add out-of-this-world experiences only adds to increasing the audience's attention to the big screen. Luckily for me, Maya's plugin - MASH - helps create motion graphics and certain visual effects quite easily. In this project, I created three particle effects: Trail, Outline, and Pulse.

## Trail
This effect was created by animating a simple jump and flip (with bounce) for each letter of "TRAILZ". Then, I created a simple MASH network using a cube and distributed it along the text's mesh. Then, by hiding the original node and adding a trail effect (thickened by a circle poly), we get the finished product below:

<img align="center" src="/assets/Trails.gif" style="width:600px;"/>

## Outline
I created a MASH network using a simple sphere as the node. By selecting the edges/curves on the "OUTLINE" text, I created a curve node. By adding a trails node (thickened by a circle object), we see the finished product below:

<img align="center" src="/assets/Outline.gif" style="width:600px;"/>

## Pulse
Starting with a simple cube, I again, created several mash distribution nodes to stick to that cube logo. I then adjusted the size of those nodes and implementing a color node with randomized colors (that slowly ramped down to orange). After, using a Falloff object (with a transparency setting) and the pre-existing logo, I passed the Falloff object through the MASH, seemingly making it disappear while also having the logo underneath reveal itself. With some textures and color, the final project is shown below:

<img align="center" src="/assets/Pulse.gif" style="width:400px;"/>

<br>
<a href="{{site.baseurl}}/portfolioPage.html">*Back to Portfolio*</a>

[comment]: [*Back to 3D Modeling and Animation Projects*]({{site.baseurl}}/Modeling_and_Animation/)