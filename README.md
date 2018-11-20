# **CarND-Path-Planning-Project** 

---

**CarND Path Planning Project**

The goals / steps of this project are the following:
* Implement a path planning algorithm to drive a car on a simulator trying to change lanes if needed and get best maximum available speed
* Test on simulator that the car successfully drives on simulator without any accidents about 7 miles
* Summarize the results with a written report


[//]: # (Image References)

[image1]: ./image1.jpg "Test Result"

---
### Files Submitted 

The following files were changed during the implementation:
* main.cpp contains car driving logic
* spline.h added this is the [Cubic Spline interpolation in C++](https://kluge.in-chemnitz.de/opensource/spline/)  suggested from class QA video.


#### 1. Project Basics

In this project the C++ was used to program. The project goal is to safely navigate around a virtual highway with other traffic where speed limit is 50MPH. The car should pass slower traffic when possible  and should avoid hitting other cars. The car should be able to make one complete loop around the 6946m highway. The total acceleration limit is 10m/s^2 and jerk limit is 10m/s^3.
Part of functionality were taken from lesson QA video.


#### 3. Accuracy

Accuracy was tested using Udacity simulator

![alt text][image1]
