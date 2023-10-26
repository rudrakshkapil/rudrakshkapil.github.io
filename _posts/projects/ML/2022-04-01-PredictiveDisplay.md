---
title:  "Predictive Display for Simulated Robotic Arm Tele-operation"
layout: post
categories: project-ML
img: predictivedisplay.png
img2: predictivedisplay2.png
alt: "Overview of Proposed Simulation Setup"
alt: "Overview of ROS communication"
---

**Skills**: MATLAB, Python, ROS, OpenSfM, CARV 3D Reconstruction, ORB-SLAM, Ubuntu, OpenCV, Eigen, Pangolin, Unity 3D, C#.


**Description**: For this 3D Computer Vision grad course project, my team and I programmed a system in Unity for the remote tele-operation of a robotic arm mounted with a camera in the presence of significant communication delay due to the immense distance between operator and arm (e.g., ground to space). The goal is to alleviate the delay by predicting the imaged view of the camera assuming no delay. The predicted stream of data is used to dynamically texture a 3D reconstruction of the remote scene and thus show the operator the orientation of the arm at that exact moment in time (overcame delay). 

We quantitatively demonstrated the utility of the developed predictive display algorithm through repeated trials of several testers comparing performance over varying lengths of communication delay. Specifically, we considered the task of organizing desk items using a dual joystick controller in the Unity simulation. Computer networks principles are used along with C# and ROS for simulating the delay by buffering the video frames streamed from the camera. 

We opted for a simulation because we can have a communication delay without having the remote and operator sites actually separated by a large distance. Simulations also provide a cost-effective way to compare different implementations of predictive display in a timely manner, which is important considering the timeframe of this project. To make the predicted view more realistic, we project it onto a 3D reconstruction of the scene, so that the relative position of objects at the remote site is portrayed more clearly.

The code implementation, project report, and presentation slides are all available on my GitHub.


<div class="button-container" style="margin-bottom:10px;justify-content:center">
  <div class="more"><a href="https://github.com/rudrakshkapil/Simulated-Teleoperation-with-Predictive-Display">Github Repo</a></div>
</div>


<div style="display:flex;justify-content:center;align-items:center">
  <img src="{{ site.baseurl }}/resources/projects/{{ page.img }}" alt="{{ page.alt }}" style="width:300px;height:auto;justify-content:center;margin:5px">
  <img src="{{ site.baseurl }}/resources/projects/{{ page.img2 }}" alt="{{ page.alt2 }}" style="width:300px;height:auto;justify-content:center;margin:5px">
</div>

