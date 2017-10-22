---
title: "Poocha -  Active spine based inertial reorientation for quadrupeds"
author: achu
layout: post
permalink: /projects/poocha
categories:
  - Research
  - Quadrupeds
 
     
excerpt: "Poocha -  Active spine based inertial reorientation for quadrupeds  ."
---




"Poocha" is the malayalam word for cat. Apart from their cuteness, what makes cats interesting to an engineer is their ability to upright itself land safely on all its limbs, no matter what orientation they were initially. So, why not make the dumb quadrupeds smarter by teaching them to land safely on all its four legs.

[Cat righting reflex](https://en.wikipedia.org/wiki/Cat_righting_reflex){:target="_blank"} been extensively studied before. In 1942 US Air Force played with kittens in microgravity. The same lab, in 1962, published a report titled ["Weightless Man: Self-Rotation Techniques"](http://www.dtic.mil/dtic/tr/fulltext/u2/400354.pdf){:target="_blank"}, as a guidline for future astronauts on how to move around in zero gravity.  1960s. The falling cat was also studiedextensively by NASA to prepare the astronauts for Zero-G environments. A 1969 paper in the International Journal of Solids and Structures  titled ["A Dynamical Explanation of the Falling Cat Phenomenon"](http://www.sciencedirect.com/science/article/pii/0020768369900869) {:target="_blank"}explains this. 

Past research attributes the cat reflex to law of conservation of momentem.  Flexible bodies can generate internal forces and moments, by the motion of limbs. But the rest of the body rotates in opposite direction owing to the conservation of momentum, so that net angular momentum remains zero.  However the rate of rotation can be controlled by extending or pulling back the limbs. Wikipedia summarises it to three key steps:


1. Bend in the middle so that the front half of their body rotates about a different axis from the rear half.
2. Tuck their front legs in to reduce the moment of inertia of the front half of their body and extend their rear legs to increase the moment of inertia of the rear half of their body so that they can rotate their front further (as much as 90°) while the rear half rotates in the opposite direction less (as little as 10°).
3. Extend their front legs and tuck their rear legs so that they can rotate their rear half further while their front half rotates in the opposite direction less.

Depending on the cat's flexibility and initial angular momentum, if any, the cat may need to perform steps two and three repeatedly in order to complete a full 180° rotation.

Project Poocha aims to replicate the same behaviour in a qaudruped. A quadruped based on EPFL's Bobcat was designed and control system implemented and tested in simulation. Is is less heartbreaking to throw around and torture the poocha in simulation than the real hardware. Following is the simulation done in VREP:



<div align="center">
<iframe width="900" height="506" src="https://www.youtube.com/embed/4Hg29l2iCJo" frameborder="0" allowfullscreen></iframe>
</div>


Since the control system is verified in simulation, Now I have to make the actual robot. I decided to take the 3D printing way. It is still ongoing. As of now, following are some photos.It uses an MPU6050 accelerometer for sensing its orientation and a Teensy 3 to control. The motors are the lightweight, SG90 micro servo.

{% include image.html url="https://farm5.staticflickr.com/4504/37596498780_a8c6e78535_k.jpg" caption=" " href="https://farm5.staticflickr.com/4504/37596498780_a8c6e78535_k.jpg" width=650 align="center" %}


{% include image.html url="https://farm5.staticflickr.com/4490/37854267941_fccfcb060e_k.jpg" caption=" " href="https://farm5.staticflickr.com/4490/37854267941_fccfcb060e_k.jpg" width=650 align="center" %}

{% include image.html url="https://farm5.staticflickr.com/4456/37596522940_a23cdd867f_k.jpg" caption=" " href="https://farm5.staticflickr.com/4456/37596522940_a23cdd867f_k.jpg" width=650 align="center" %}





The page will be updated in future as the real poocha grows up and becomes able to jump and land with confidence. More photos, videos and a couple of technical papers are coming up.Make sure to come back later. Cheers.