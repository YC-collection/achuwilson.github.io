---
title: "How I did research and wrote a conference paper in under 30 days, while working a full time startup job"
author: achu
layout: post
permalink: /blog/2016/09/how_i_wrote_research_paper_in_30_days/
categories:
  - Research
excerpt: "How I choose, did research and wrote a conference paper in under less than a month  ."
---

## What is this about?

Finally, I did it. Wrote a research paper and submitted for the IEEE International Conference on Robotics and Automation, ICRA-2017. I know submitting a paper is not as big/valued as getting it accepted, since anyone can submit a paper to the top conferences. It is under review and I doubt whether it would be accepted, but even then I am happy that I could put my best effort into it and learn much. I worked on three research ideas in a couple of months and the final one was rolled out in just under 30 days.
So following is a write up on why and how I did it.

## Why I did it?
1. I always wanted to become a scientist and make my little contribution to science/robotics.
2. I wanted to get into a Ph.D program and I had no research papers.
3. To experience how it was like doing research and writing a technical paper.
4. Attend conferences like ICRA and IROS again, meet smart people and their work.

## My Background and Constraints

Ever since I was rejected from a couple of Ph.D programs in 2014 due to lack of research experience, I have been making plans and trying to do research on my own and write a couple of papers. But nothing moved past making elaborate plans and maybe a little literature study for all the research ideas I had. The stresses of working in a startup consume so much of your mental strength as well as time. Thus I failed in materializing all my research Ideas. My research ideas are interdisciplinary and spans over computer vision for robotics, novel actuators for robots, robotic manipulators and motion planning to name a few.

My constraints are:

1. Demanding Job.
* Working in a startup is very much different that a normal 9-5 job. You have got multiple responsibilities and more work. On some days I may have to pull all-nighters to meet the deadlines
  
2. No research experience
* Even though I always wanted to be a scientist, I never had any formal training in research. I am an engineer and all my prior works were on building and hacking some stuff.

3. No mentor
* Wish I had some professors to guide me. I was alone and my guide was the books and the Internet.

4. Limited Time
* Since one of the goals of undertaking a research project is going to the next ICRA, I have to submit the paper before 15th September 2016.


## How it Started?


### **-16 to 21st May 2016:  Attending ICRA**

I had the priceless opportunity to attend the IEEE sponsored International Conference on Robotics and Automation [(ICRA)](https://www.icra2016.org) at Stockholm. I was one of the three-member team "Autobots" that won the Humanitarian Robotics Challenge (HRATC).

The benefits brought by ICRA were many. I met so many researchers and came to know about their work. I could attend a series of workshops by leading roboticists. It was my first time seeing papers being presented. Even though I couldn't make sense of many papers due to my limited knowledge, it was an awesome learning experience. The papers published at ICRA comes from all realms of robotics. Coming from a background more inclined seeing the real-hardware robots, I could classify them into two- purely theoretical/mathematical papers and  papers on 'real robot hardware' . 

Apart  from meeting awesome people, the best thing ICRA gave me is the following.

{% include image.html url="https://c3.staticflickr.com/9/8638/29756697346_5594573f25_c.jpg" caption="The ICRA Proceedings in USB Drive" href="https://c3.staticflickr.com/9/8638/29756697346_5594573f25_c.jpg" width=650 align="center" %}


Yeah, it is an USB pen drive, which contains data of immense value. It was the first time I had access to this much research papers. It was awesome to go through all of the papers, even though I couldn't understand many of the purely theoretical ones.

During the conference itself, a vague idea was formed on the research topic I am going to pick up. It was to develop a Direct Drive linear actuator based clone of the MIT Junior Cheetah

 
{% include image.html url="https://biomimetics.mit.edu/sites/default/files/images/Render.jpg" caption="The MIT Junior Cheetah. Image Courtesy: MIT Biomimetrics Lab"  href="https://biomimetics.mit.edu/sites/default/files/images/Render.jpg" width=700 align="center" %}

Replacing the geared motors in the above figure with antagonistically coupled direct drive linear actuators was my first research idea. It was in line with my interest in direct drive and compliant actuators. I met the following persons at ICRA that fuelled my thoughts in this direction.

1. Will Bosworth
* Bosworth is a Ph.D student at MIT. He is the one that made Super Mini Cheetah. I met him during his interactive session at the conference. He explained me the drive systems they use in Cheetah. 
2. Zachary Batts
* Batts is with Disney Research. He presented a direct drive hopping mechanism at the conference.
3. Gavin Kenneally
* Kenneally is a Ph.D student at UPenn. He is one of the brains behind Minitaur, a highly dynamic legged robot, which is again direct driven by off the shelf motors.

I have seen Super Mini Cheetah (SMC) before and had a plan to make a clone of it as a hobby project even before coming to the conference. Instead of making a clone, as I thought before, now I wanted to make a contribution. SMC uses off the shelf DC geared motors and impedance control for jumping around. Cheetah uses permanent magnet synchronous motors with a low ratio planetary gear. A low gear ratio can improve the backdrivability and actuator transparency. I choose to upgrade the cheetah using an entirely direct driven actuator. Unlike the rotary actuators used in its present implementation, my plan was to use linear actuators- antagonoisticaly coupled as in animal muscular structures. Thus I selected my first research project- to develop a **direct driven actuator for a legged robot**, which meets the following criterions:


1. Entirely direct driven.
* This means no gearboxes are to be used. It will help in achieving much higher bandwidth control and actuator transparency.
2. Linear in motion.
* Inspired by nature, to use two antagonistically coupled linear actuators 
3. High Force Density
* The higher the force output per mass, the better.
4. Highly Efficient
* robots are often constrained by the energy that they can carry.





### **-26th May 2016 : Back home**

I returned back home from ICRA. There was plenty of work pending at the office since I was gone for over a week. I had to take care of that.

### **-30th May to June 5 2016 : Literature Search**

So thus began the literature search. I searched all over the internet and gathered a ton of research papers. Now I had to read through all of them, make notes and think how to build upon that.  Finding time to read all these was the first problem I faced. I cannot sit and read the entire day. I started using Mendeley app in PC and my Android smartphone to organize the papers and make notes. Having all the papers in my smartphone helped to make use of every bit of time otherwise spent useless. I read during my daily commute to and from work, during meals, when I am travelling outside etc





### **-6 to 18th June 2016 : Job Calls for Travel**

As a part of my job, I had to travel for some meetings and demos during these days. I drove from Cochin to Chennai, had half a dozen meetings and demos to various clients in and around Chennai. Indian cities are notorious for the traffic jams. Moreover, Chennai was hot and uncomfortable. The next week I drove to Bangalore, where a dozen other meetings and demos were scheduled. After all these demos I drove back to Cochin on 18th. Total Kilometers driven: 3500 

It was very difficult to indulge in studies and research during this time. I was staying at different places- with friends, relatives, in hotels etc. Moreover, I would be often exhausted after the day's toil, that even the possibility of staying up late reading was not imaginable. Still, I managed to read quite a bit by making best usage of time and not wasting any. Often I would end up sleeping reading some papers on my smartphone or in front of the open laptop.

Even though finding time to read was difficult, there was enough and more time to think. I could think while waiting in traffic blocks, while driving, during meals, and even during boring and useless meetings. My thoughts wandered around various problems associated with direct drive mechanisms and technologies, how animal muscles work and limbs move, tactile and vision feedback, power consumption for these drives etc to name a few.

**Birth of research topic 1**

My thoughts began to converge around the  suitability of electric direct drive linear actuators for a high-performance anthropomorphic manipulator, which is highly dynamic and at the same time safe and compliant enough to work alongside humans. Two linear actuators would be coupled antagonistically at each joint analogous to mammalian muscle structure. A quick search on the internet convinced me that little or no research has been done in this area. So as the first step, I had to study, design and make the *direct drive linear actuator, or as in my dreams, the ideal human muscle replacement.*

### **-18th - 25th June 2016 : Background Study**

I am back at my hometown and began reading papers on direct drive manipulators. I read papers ranging from those published in 1981(Design of direct drive robots by H. Asada & T. Kanade )  to the recently published papers on direct drive jumping robots at UPenn and MIT.  I also referred The Springer Handbook of Robotics,  especially the chapters on Force Control to gain the theoretical knowledge. Also, the 2009 September IEEE Robotics and Automation Magazine article titled "Compliant Actuator Designs" by Bram Vanderborght helped me understand better about the various compliant systems. 

As I began studying more and more about direct drive actuators and their suitability in human safe robots, it became clear the vastness and depth of the subject. I have chosen a vast area. From my experience on building  and working with robot manipulators for a couple of years, it was evident that building a linear actuated direct drive robot is going to take a lot of time, Moreover, building a robot arm may not be cool,  but building a running and jumping cheetah-like robot is definitely cool and satisfying. I was sort of confused on whether to choose the research topic on a jumping robot or a robot manipulator. Instead of making a direct drive robot arm, that may take a long time, why not figue out a way to make use of the same linear actuator to make my cheetah robot run and jump. So my research turned to designing a jumping leg using linear direct drive actuators. Thus my reference literature also started to include quadruped robots capable of jumping and hopping. One of the notable sources from which I studied  about quadruped robots is the Ph.D thesis of Claudio Semini, in which he develops HyQ robot


### **-25th June 2016 -  Idea 1: Direct Drive Linear Actuator**


Once I felt enough background study has been done, I resorted to my research and design. It was a variation of the tubular liner shaft actuators. I had to sharpen my math skills , learn new things like electromagnetic FEM analysis etc to name a few. The first draft of the design was done using the old school method of paper and pencil. Then an initial design in CAD was done and was verified using mechanical and electromagnetic FEM. Once the design parameters were verified, it was time for the detailed mechanical drawing. Once the detailed design was completed, the respective parts were 3D printed.



{% include image.html url="https://c2.staticflickr.com/8/7540/27320610433_f9db1bbab9_h.jpg" caption="The 3D pinted cylindrical shaft, coil holder and the couplers assembled" href= "https://c2.staticflickr.com/8/7540/27320610433_f9db1bbab9_h.jpg" width=800 align="center" %}

The cylindrical shaft was to be filled with Neodymium magnets in such a way that the magnetic flux lines will be perpendicular to the shaft. The magnetic field produced by the 3 phase coil will then interact with the magnetic field of the permanent magnets to induce force in them. Thecurrent in the coils have to be commuted properly depending on the position of the magnet using hall sensors.

### **-27th June 2016 -  Assembling the 3D Printed parts**

I choose to use 3D printing to make my the parts of my first prototype. The 3D printing started and it took a couple of days to print all the parts successfully. The linear moving shaft, the coupler that connects the shaft to the external load, and the support structure for winding the coil all were 3D printed. Since the mechanical components were designed to be tight-fit, the shrinkage and expansion of the material during 3D printing made the fitting and assembly impossible, I had to spend a decent amount of time filing, and using sandpaper to get the exact fit.

### **-30th June 2016 -  Winding the coils**

 
 The next step was winding the coils. I started winding manually using the hand, but grew impatient quickly  and ended up using an electric screwdriver to speed up the winding process.

### **-3rd to 4 th July 2016 -  Initial success with Idea1**


The next step was the electronics assembly. The control system was based on a Teensy board. The coils were driven by  MC33926 motor drivers which had an excellent motor current feedback functionality, which could be used for impedance control of the actuator.I decided to add the Hall sensors at next stage after verifying whether the system works fine.

Next step was the barebones controller software. Teensy generated 3 phase PWM which was used to drive the coil, and viola, the coil moved at the first attempt itself. The motion was not smooth as expected, but could be made smoother using Hall sensor feedback and a simple PID . The output force was good enough and could be increased by increasing the current. So, I decided to go ahead and figure out the maximum force it can  apply without overheating and external cooling.I found it to be  satisfactory, and with a little bit of cooling, it can provide enough force to make the robot jump like the cheetah. So I went to sleep happily. 

### **-5th July 2016 -  The disappointment** 

The next day, when I resumed work on the actuator, soon it was found that the linear shaft is stuck inside the coil. Even though the heating caused by the previous day's force testing  was below limits for the coil winding, it was enough to weaken the 3D printed plastic. Since the shaft had opposing Neodymium magnets inside, the internal stresses are high and it caused the shaft to bend, melt and lock inside the coil.

### **-10th July 2016 : Retrying Idea1**

I had to 3D print another set. This time, I went for hollow aluminum tubes as the shaft. Aluminum rods were lighter, will dissipate heat effectively and the thickness was less than 1 mm. This meant that the coils can carry higher current and the air reduction in thickness will reduce the air gap. 
So again the FEM analysis was done, CAD models redrawn.

### **-14th to 20th July 2016 : Travelling**

I had to travel again. This time it was to Bangalore and Coimbatore, to provide support to one of our client. This means my research is now paused. All I can do is keep on reading  the papers, think think think. 

### **-22nd to 24th July 2016 :  Version 2 of Idea1**

Back at home, purchased  the aluminum rods, 3D printed the components 

{% include image.html url="https://c3.staticflickr.com/9/8148/29798020906_fb95fa3449_b.jpg" caption="The 3D pinted cylindrical shaft, coil holder and the couplers assembled" href="https://c3.staticflickr.com/9/8148/29798020906_fb95fa3449_b.jpg" width=800 align="center" %}


So, again began the long coil winding process. 

### **-24th July to 4th August 2016 : Don't Re-invent the wheel**

While winding the coil, a stark realization hit me. If I am proceeding at this pace. it will take me long to complete my reasearch. I need to do the commutation, impedance and dampng controllers in software etc etc.. Then I have to machine it sturdy to that cheeta can jump etc. My resarch is not just the development of a linear direct drive actuator, it is much broader. the linear actuator is just a component that enables my research on its usage in highly dynamic robot environments. As of now, the component that I am making now, is available in the market, even though it doesnt have all the qualities i dreamed of. So why should I spend my time on problems already solved. In fact, i was reinventing the wheel. So I should just make use of the.

### **-5th to 9th August 2016 : More Travel and the 2nd Idea**

Again.. the travel, this time it is a customer support at Hyderabad. I couldnt work on my project, but during the 48 hours of time spend travelling I could read papers and think in a relaxed state. I began thinking about a robot leg actuated by a direct drive linear actuator and started the design and reiteration process in mind.The design was centered around an off the shelf direct drive linear actuator made by Faulhaber.


The innovation I would bring to table would be the designing of a controller capable of force control with variable compliance and damping, to handle the extreme dynamics of jumping.

{% include image.html url="/images/LM1247_11_P.JPG" caption=" Faulhaber Direct Drive Linear motor"  href="/images/LM1247_11_P.JPG" width=500 align="center" %}


### **-10th to 16th August 2016 : Failure of 2nd Idea**
Once back at home, the design I had in my mind was transferred to paper, calculations were done and verified and then to the CAD program. The materials required, including the Faulhaber motor, controllers, aluminun extrusions all were procured. The Faulhaber direct drive motor is pretty expensive and is out of reach of a typical hobbyist.
Once everyting was procured, then the assembly of the design was done.


{% include image.html url="https://c8.staticflickr.com/9/8055/29264131351_95474fe8c8_h.jpg" caption="The jumping leg actuated by a Faulhaber Direct Drive Linear motor"  href="https://c8.staticflickr.com/9/8055/29264131351_95474fe8c8_h.jpg"
width=800 align="center" %}

Now I could start writing the controller. I could get to move the leg up and down, but it didnt had the enough power to lift it from ground. The motor heated up very much that I feared I would see the magic blue smoke coming out of the expensive motor and I had to shut it down frequently to allow for the cooling.  I was also unable to send quick bursts of high current using the default motor driver it came with. The time was running out to develop a custom driver for this motor. So I was again in geopardy.  I realized and accepted this is also going to fail.


### **-16th to 22nd August 2016 : More Travel, More Study**

I had to travel to Chennai for supporting a customer of my company. I stayed with my uncle in chennai and the daily commute to the client was about 70 kms one side distance. I was travelling in the crowded suburbun trains of Chennai and the hot climate made it worse. I had to start my journey at abot 8 AM and would be back only by 11PM. I would be very exhaused  by the time I reach my room. So reading at night was beyond consideration. But I could make use of the commute time. In total it took around 7 hours an average per day for my commute. I spend this time reading through the papers that came in the ICRA USB drive. There were over a thousand papers in my reading list. I skimmed through most of them, stopping and reading only those portions I could understand/was interested in. I came across the paper titled " Design and Development of a Hybrid Magneto-Rheological Clutch for Safe Robotic Applications" by Masoud Moghani and Mehrdad R. Kermani. It captured my attention and I began to study more about Magneto Rheological fluids and their application in human safe robotics. I found out a couple more papers by the same authors on the fundamentals.


### **-23rd to 26th August 2016 :  3rd Idea- MR Linear Clutch**

Once I was back at home, I began to delve deep into MR Fluids and their characterization. More reading... More searching.. I came up with an idea to make use of the properties of MR Fluid to make a Linear clutch -  a clutch which controls force transmitted from input to output through MR fluid. 

### **-28th August 2016 : Making my own MR Fluid**

MR fluids are expensive and the lead time will be a couple of weeks. Since I cannot afford both, I resorted to making my own MR fluid. I filed myself a piece of iron to the fine powdered form and used vegetable oil as the medium to make my own MR fluid for the prototype.
Here is a small video with the MR fluid


<div align="center">
<iframe width="700" height="394" src="https://www.youtube.com/embed/9ZZQn46WvLg" frameborder="0" allowfullscreen></iframe>
</div>

<br>
<br>

### **-30th August 2016 : CAD Design of Clutch**

The FEM analysis and CAD design of the MR Linear clutch is completed.
 
{% include image.html url="/images/csa_arrow_labelled.jpg" caption="Cross section of the MR linear clutch." href="/images/csa_arrow_labelled.jpg"  width=450 align="center" %}

{% include image.html url="/images/cad_clutch.jpg" caption="Rendered CAD model of MR linear clutch."  href="/images/cad_clutch.jpg" width=250 align="center" %}

{% include image.html url="/images/FEM_clutch.jpg" caption="Electromagnetic FEM analysis." href="/images/FEM_clutch.jpg"  width=650 align="center" %}

### **-4th September 2016 : Fabricating the parts of Clutch**

The 3D printing of the parts of the clutch is complete.


{% include image.html url="https://c5.staticflickr.com/9/8388/29309356476_d7b4660548_h.jpg" caption="3D printed clutch casing." href="https://c5.staticflickr.com/9/8388/29309356476_d7b4660548_h.jpg"  width=650 align="center" %}


{% include image.html url="https://c7.staticflickr.com/9/8381/29055571110_74ba98692c_h.jpg" caption="3D printed clutch support." href="https://c7.staticflickr.com/9/8381/29055571110_74ba98692c_h.jpg"  width=650 align="center" %}

Now I have to wind the coils


{% include image.html url="https://c2.staticflickr.com/9/8334/29343014345_a5cbf09c2f_h.jpg" caption="The Coil ." href="https://c2.staticflickr.com/9/8334/29343014345_a5cbf09c2f_h.jpg"  width=650 align="center" %}

The winding of coil over the 3D printed cutch casing is completed. 

{% include image.html url="https://c2.staticflickr.com/9/8572/29264211761_1b61932867_h.jpg" caption="Initial Assembly."  href="https://c2.staticflickr.com/9/8572/29264211761_1b61932867_h.jpg" width=650 align="center" %}


 Now I have to procure a couple of items including linear shaft bearings, aluminum rods etc.


### **-6th September 2016 : Success of 3rd Idea**

Once all the parts are procured, the the clutch was assembled and the cavity inside was filled with MR Fluid. Then i had to test the working of the clutch and study its characteristics.  **Yeah.. It worked as I expected and designed**. Finally I could relax a bit and sleep peacefully.

{% include image.html url="/images/clutch_photo.jpg" caption="The  assembled MR linear clutch." href="/images/clutch_photo.jpg"   width=650 align="center" %}


### **-8th September 2016 : Assembling the arm**

In order to demonstrate the usefulness and study more about the MR linear clutch, a single degree of freedom robot joint was designed and fabricated. It used the standard 30x30 Aluminum profiles. The arm was driven by a Firgelli linear actuator

{% include image.html url="/images/firgelli.jpg" href="/images/firgelli.jpg" caption="The  Firgelli linear actuator which is used to power the arm."  width=650 align="center" %}


{% include image.html url="/images/arm_render_labelled.jpg" href="/images/arm_render_labelled.jpg" caption="The rendered CAD model of the prototype arm."  width=650 align="center" %}


{% include image.html url="https://c5.staticflickr.com/9/8386/29234935852_1dacb77667_h.jpg" href="https://c5.staticflickr.com/9/8386/29234935852_1dacb77667_h.jpg" caption="Photo of the prototype arm."  width=650 align="center" %}


{% include image.html url="https://c3.staticflickr.com/9/8301/29309434866_92436b37c8_h.jpg" href="https://c3.staticflickr.com/9/8301/29309434866_92436b37c8_h.jpg" caption="Photo of the prototype arm."  width=650 align="center" %}



### **-9th and 10th September 2016 : More Experiments**

More experiments are done with the arm to validate the functionality of MR Linear clutch.

{% include image.html url="/images/MR_clutch_result_plot.jpg" href="/images/MR_clutch_result_plot.jpg" caption="Plot of Coil current vs the Force transmitted."  width=500 align="center" %}


### **-11 to 15th September 2016 :  Writing the paper**

Experiments are completed and data collected. Now I have to write the paper. Since I didn't have any previous experience writing an academic paper, it took some time.  I read a couple of articles online and referred IEEE guides and instructions. Instead of starting with the abstract and introduction, I started directly with the content- the things I did and the results obtained. Once it was done, I had to refer more literature to write the introductory pages. Luckily, due to the local festival of Onam, I got holidays for a couple of days and could work on the paper full time. Even then, I felt time was running out fast. I had to plot the graphs, make diagrams and pictures and it took lot more time than expected. I worked on the paper for about 4days clocking about 20 hours of work daily. Just a couple of hours before the deadline, I completed the final proofreading and submitted the paper. I was so exhaused after this that I literally slept an entire day after this.

The final paper is embedded below

<div align="center">
<iframe src="https://drive.google.com/file/d/0B1VQQE8L69dvOVgxSzF1anV1dzQ/preview" width="780" height="880" align="center"></iframe>
</div>
<br>
<br>

### **-16th September 2016 :  Making the Video**

Finally I took my time to make a small video clip of the research output.
It was then uploaded to the RAS Papercept page
<br>

<div align="center">
<iframe width="700" height="394" align ="middle" src="https://www.youtube.com/embed/ES0q4eb1TYo" frameborder="0"  allowfullscreen></iframe>
</div>
<br><br>

## **Final Words - Lessons learned**

No matter whether the paper is acccepted or rejected, it was an awesome experience. I pushed myself to the limits, learned a lot of things.

When I started working on the research project, the only thing that mattered to me was doing such an awesome work so that it is accepted at a top conference like ICRA. But as I finished the paper,  I realised that it doesn't matter much whether the paper is accepted or rejected.  Only thing that matters is how much impactful is your work and how much satisfied you are. 

Along the course of working on the paper, I learned much beyond the robotics stuff. The main ones being,

* **There is plenty of wasted time.**
In most cases, scientific research and publication of results takes enormous amount of time and resources. It may takes months or even years of research to make an impactful invention and maybe even more months to author a paper on it.   But in my case, the time was fixed as the paper was to be submitted before the deadline, which is just a couple of months away. On top of that, I was working a full time job  at a startup, which made finding the time extremely difficult.I had to find extra time after my work and make best use of the time wasted. I made time by sleeping less, only about 4-5 hours a day.  After my daytime job, I worked almost daily from around 7PM till I was exhausted by around 2/3AM or even 4AM. 

	Having a smartphone always with me was the greatest tool that I used to save time. I had Mendeley on my phone to keep track of all the papers that I am reading. I could read on the phone irrespective of where I am -  while travelling in a crowded bus, when having meals, when having a haircut at the saloon, when stuck in a traffic jam, while waiting for someone, when in a queue or even when I am in the toilet seat. These are the bits of time wasted by not being productive. Somehow I managed to squeeze out every bit of time wasted and use it for productive things.


* **Do not take broad subjects, be specific.**
 Designing a clone of Cheetah using direct drive actuators is a very broad topic. Studies must be done on the actuators, optimum kinematic structure, gait generation, stability and much more. Each of these require considerable research effort in itself and has been only possible by the collective effort of many researchers. So concentrate on something that may seem simple and small, go deep and push forward. 
*  **Dont reinvent the wheel.**
 This was a lesson that I learned the hard way. Better not to start from scratch, unless your idea is  revolutionary and  novel. Study about and make use of the progress brought about by past researchers.  If some part of your research depends on something that has been previously done, make use of it and build upon it or reuse it. Your time is limited (not just the conference submission deadline), so why spend time reinventing the wheel, when you can invent time travel.
