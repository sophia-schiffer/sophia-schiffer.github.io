---
layout: default
title: Pinshooter
youtubeId: HQIWntieInI
---

# Pinshooter
## ME495 Embedded Systems Final Project
### Authors: Joel Goh, Maximiliano Palay, Rahul Roy, Sophia Schiffer, Jialu Yu

In this project, the Franka arm searches for known randomly placed pins and shoots them down. It is fitted with an onboard camera to see its environment and a Nerf blaster to be able to shoot the targets. The user can specify the color of the pins that the arm is going to shoot first and then once all of those colored pins are shot, the arm will wait for a second input to continue shooting different colored targets.


{% include youtubeplay.html id=page.youtubeId %}


This project uses Robot Operating System 2 (ROS2) to interface between our Python code and the Franka Emika Panda robot.

My primary role was ensuring robust and repeatable pick and place operations for the arm. I developed the code for our
robot to pick up the proper gun and replace it on the correct gun mount with enough precision that the gun can be
picked up again as many times as necessary to shoot down all desired pins. To achieve this, I used MoveIt and AprilTag
ROS, which are "packages" of code that allow robots to move to desired coordinates and track positions using QR codes,
respectively. 


