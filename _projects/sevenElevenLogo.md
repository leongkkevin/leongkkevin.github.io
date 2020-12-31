---
layout: page
title: 7-11 Logo
permalink: /Seven_Eleven_Logo/
---
# 7-11 Logo

In this project, I really dove into rendering and lighting, as well as getting into some basic keyframe animations. This project had me animating a 7-11 Logo and also working with skydome lighting. <br>

<img align="right" src="/assets/SevElevLogoPic.png" style="width:50;">
I began with a basic black and white 7-11 image (shown to the right). After several failed trials to animate a good-looking 7-11 logo with the PNG image, I realized that I was missing a crucial step in the process of converting an image into a model. I figured out that I should've transformed the PNG into an SVG vector image. This allows the model's edges and outlines to be clean (instead of pixellated and blocky). 

Then, I extruded the flat model to make it three dimensional and added a glossy and colored texture. I also made sure that each individual letter and object (while grouped) was an individual piece of the logo. 

Next, using <a href="https://hdrihaven.com/">HDRI Haven</a>, I found a basic skydome light of a sunny day and imported it into my Maya scene. With a few brightness adjustments, I got the skydome to nicely light my scene.

*The final product of the model is shown below:*

<img src="/assets/SevElevMaya.png">

Now, I was ready to start animating. I created a new camera and a simple half circle line centered around the logo. This would be the basis for the camera motion. I attached the camera to one end and set the curve to be a "motion path". This allowed the camera to move only in the constraints of that line. I set 2 keyframes for the start and end of the camera's path as well as for the path of the circle (which moves from top to bottom of the logo).

After, I started to work on animating the logo. First, I set the final keyframe as the finished, put-together logo. Then, with each individual piece, I rearranged the logo to its "starting positions" and set their opacity to 0 (so they fade into the logo). I also slightly tweaked the rotation of them for some more dynamic movement. 

*The final product is shown in the gif below:*

<img src="/assets/SevElevPlayblast.gif">

This project reminds me a lot about the commercials I see on television. I learned a while back that most of the items (especially cars) that you see on ads are actually 3D models - which makes a lot of sense now. With the 3D model, you can change any aspect of the scene to your wishing. This includes the light, weather, scenery, opacity, and movement of everything! This would make it extremely easy to make an item or logo look idyllic and appealing to the ad's audience.

[*Back to 3D Modeling and Animation Projects*]({{site.baseurl}}/Modeling_and_Animation/)