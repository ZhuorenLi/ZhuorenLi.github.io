---
title: Parking Path Planning
date: '2021-08-22'
tags:
- Parking
- Smooth Driving
image:
  placement: 1
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/CpkOjOcXdUY)'
  focal_point: ""
  preview_only: true 
summary: Simple and effective parking path planning based on geometric curve and MPC optimization. (From Feb 2021 to Aug 2021)
---

## **Parking Path Planning in AVP System**
<!-- Collaborating student: *Guizhe Jin, 1st-year Gruaduated Student*. -->

<!-- ### **Motivation**
When DRL directly control the vehicle's motion:
- The output commands are easy to change continuously whent DRL agent directly generates the control command.
- The control commands generated in real-time are prone to sudden changes in dynamically changing environments due to the lack of long-term motion planning. -->

The whole system is consisted of outdoor/indoor localization, parking slot perception, path planning and trakcing control.The overall framework is as following：
![png](featured.png)

Firstly, the minimum road width required for one-step parking is calculated by considering the geometric relationship between the initial position of the vehicle and the parking slot. Secondly, the parking path is determined based on the collision constraints of the parking slot. Finally, we establish the vehicle kinematics error model and use the MPC algorithm to optimize the parking path.
![png](allalg.png)
![png](alg.png)

### **This research havs supported many engineering projects**

AVP system for SAIC Motor Corporation, Ltd. (mass-produced electric vehicle: Marvel X)
![png](marvelx.png)

AVP system for New Energy Vehicle Corporation, Jiangxi Jiangling Motors Group.
![png](jianglinproj.png)

Autonomous Parking of Tiev-Plus vehicl for China Future Challenge of Intelligent Vehicles 
![png](realtest.png)


## **Published Paper:**
1. Zhuoren Li, Lu Xiong, Bo Leng, et.al. Path Planning Method for Perpendicular Parking Based on Vehicle Kinematics Model Using MPC Optimization. SAE Technical Papers, 2022-01-0085, 2022. 
