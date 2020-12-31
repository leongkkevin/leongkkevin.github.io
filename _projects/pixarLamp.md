---
layout: page
title: Pixar's Lamp
permalink: /Pixar_Lamp/
---
# The Pixar Lamp

In this project, I rigged a model of a lamp using inverse kinematics (IK). The project is based off of the most famous character from one of my favorite animation studios: The Pixar Lamp.

First, I began by finding a very basic lamp model - which was already seperated into 4 parts: the head, the upper neck, the lower neck, and the base. From those parts, I created joints that connected from the base of the lamp, to the midpoint of the neck, to the head, and one past the head (so I could see which way the lamp was facing). After, I parented the joints to their respective parts of the lamp. With the joints in place, I connected the head and the base joint via an IK handle, so that I would not have to move every individual joing if I wanted the head to move correspondingly. In order to make the rig more user friendly, I created some controls and parented them to the specific joints. 

*Below is a picture of the lamp, its joints, and its controls:*
<img align="center" src="/assets/lampMaya.png" style="width:200;">

*Here is a short demo of the lamp's IK controllers:*
<iframe width="700" height="395" src="https://www.youtube.com/embed/sy7A8hQUBaI?controls=0" frameborder="10" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"></iframe>

After finishing the lamp's rig, I created a short animation of the lamp jumping. Using only keyframes (I was unaware of animation graphs at the time), I created this short gif from a playblast of the jumping lamp animation: 

<img align="center" src="/assets/lampGif.gif" style="width:200;">

I had a blast creating this project. Having grown up with Pixar classics like *Finding Nemo*, *Toy Story*, and *Wall-E*, I was excited to see the basics of what goes behind creating such amazing characters. This project taught me a lot about the basics of rigging up a basic character with joints and handles. I also got to dabble into some basic keyframe animations using the timeline. 

[*Back to 3D Modeling and Animation Projects*]({{site.baseurl}}/Modeling_and_Animation/)