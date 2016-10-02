---
title: HSV Values in OpenCV
author: achu
layout: post
permalink: /blog/2012/02/hsv-values-in-opencv/
categories:
  - OpenCV
excerpt: "A Simple and useful script to find out the HSV/RGB Values of a pixel on the fly"
---

#HSV Pixel values in OpenCV


HSV color space is more often used in machine vision owing to its superior performance compared to RGB color space in varying illumination levels. Often thresholding and masking is done in HSV color space. So it is very important to know the HSV values of the color which we want to filter out. HSV color space of  OpenCV is a bit complicated than other software programmes like Gimp, Photoshop etc.So  I have written a small python script to grab frames from a camera, and print the HSV value of the pixel under the cursor

HSV means Hue-Saturation-Value, where the Hue is the color.Saturation is the greyness, so that a Saturation value near 0 means it is dull or grey looking.And Value is the brightness of the pixel.(For a lot more info about HSV and other color spaces, refer to HSL and HSV on Wikipedia)

The python code is given below . It prints the HSV values under the cursor into the terminal as well as overlays on the video as text.

{% highlight python %}


#!/usr/bin/env python
# -*- coding: utf-8 -*-
# returns HSV value of the pixel under the cursor in a video stream
# author: achuwilson
# achuwilson.github.io
import cv
import time
x_co = 0
y_co = 0
def on_mouse(event,x,y,flag,param):
  global x_co
  global y_co
  if(event==cv.CV_EVENT_MOUSEMOVE):
    x_co=x
    y_co=y

cv.NamedWindow("camera", 1)
capture = cv.CaptureFromCAM(0)
font = cv.InitFont(cv.CV_FONT_HERSHEY_SIMPLEX, 0.5, 1, 0, 2, 8)
while True:
    src = cv.QueryFrame(capture)
    cv.Smooth(src, src, cv.CV_BLUR, 3)
    hsv = cv.CreateImage(cv.GetSize(src), 8, 3)
    thr = cv.CreateImage(cv.GetSize(src), 8, 1)
    cv.CvtColor(src, hsv, cv.CV_BGR2HSV)
    cv.SetMouseCallback("camera",on_mouse, 0);
    s=cv.Get2D(hsv,y_co,x_co)
    print "H:",s[0],"      S:",s[1],"       V:",s[2]
    cv.PutText(src,str(s[0])+","+str(s[1])+","+str(s[2]), (x_co,y_co),font, (55,25,255))
    cv.ShowImage("camera", src)
    if cv.WaitKey(10) == 27:
        break
{% endhighlight %}
