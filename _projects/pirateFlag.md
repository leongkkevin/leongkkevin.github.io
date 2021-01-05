---
layout: page
title: Pirate Flag
permalink: /Pirate_Flag/
---
# Pirate Flag

Combining all my skills with modeling (and some animation/VFX), I wanted to try something a little more "real-world". This project, I modeled a pirate flag (and flagpole), then create some nCloth dynamics to make the tattered flag fly in the wind (just like something out of Pirates of the Caribbean).

The first thing I did was create the flag itself. Using a simple image of a torn pirate flag (shown below) as an image plane, I modeled the basic shape/outline of the flag (including the rips and tears). I did this by deleting entire sections of the flag and manipulating vertices to match the shape from the image almost exactly. By evenly inserting edges and rearranging vertices, I was ensured that the model of the flag had clean and organized geometry (which would later on aid in making a good looking nCloth simulation). Afterwards, I selected the entire flag and created an nCloth object using my selection. Specifically, I used a basic shirt preset to give the flag simple cloth properties. 

|Flag Reference Image| Flag Texture | Final Product |
|-------|--------|---------|
| <img align="left" src="/assets/PirateFlagImage.png" style="width:200px;"> |  <img align="right" src="/assets/PirateFlagTexture.jpg" style="width:300px;"> | <img align="right" src="/assets/PirateFlagOnly.png" style="width:300px;"> |

Now, a pirate flag is just a piece of cloth if it can't fly in the wind - so the next thing I created was the flagpole. This consisted of modeling 3 cylinders of increasing width layered on top of one another. Next, I took a torus shape, scaled it, and copied it down the middle section of the pole. Together, this gave the flagpole some weight, as well as a more interesting design than a simple long rod. In order to constrain one of the flag's sides onto the pole, I selected the vertices on the far left side of the flag and created a constraint, then grouped the constraints to the pole. 

*This was the finished flag:*
<img align="center" src="/assets/PirateFlagMaya.png" style="width:100;">

When running the simulation, the cloth simply folds along the constraint, dangling. That's no fun! So, selecting the nucleus, I added some wind to the scene, bringing life into the torn pirate flag. I also added the texture of a basic pirate flag (shown below). With a little bit of editing to the friction, thickness, and stickiness of the cloth, I managed to get a beautiful simulation of a pirate flag bellowing in the wind. 

<img align="center" src="/assets/PirateFlag.gif" style="width:100;">

Afterwards, I imported a nice sunset skydome light from <a href="https://hdrihaven.com/">HDRI Haven</a> and captured a wonderful rendered image as well!

<img align="center" src="/assets/PirateFlagRender.jpg" style="width:100;">

This proejct was a great combination of a lot of skills I had learned (plus many new ones). I got to model 2 items completely from scratch, and play around with their materials and designs. I also got to use skydome lighting to create a beautiful scene. I also learned how to create nCloth simulations - a tool that is used in almost every blockbuster film these days. This project was really eye-opening to how realistic these simulations are becoming. If a basic engine like Maya can create such fantastic looking cloth simulations, I can only imagine what amazing software big-time studios use!

[*Back to 3D Modeling and Animation Projects*]({{site.baseurl}}/Modeling_and_Animation/)