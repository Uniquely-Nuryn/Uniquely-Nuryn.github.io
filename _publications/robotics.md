---
layout: publication_new
title: TurtleBot3 Autonomous Navigation 
slug: intelligent_robotics
year: 2024
subject: Term 7 Intelligent Robotics
order: 3
description: Our team configured a TurtleBot3 to navigate autonomously through a maze and count the images it passed by using ROS 2 and Python.

---

## 1. About this Project
This project, which was part of our Intelligent Robotics course, required us to use to work in teams of 4 to programme a pre-assesmbled TurtleBot3 robot. Our task was to make it navigate through a given maze at the back of our classroom and achieve the following outcomes:

1. Map the maze with **manual waypoints** using Nav2 + SLAM;
2. Map the maze **autonomously** using Frontier Based Exploration;
3. Use **image recognition** to count number of items seen plus stop autonomously upon seeing the 'STOP' sign.

We used ROS 2 (Humble) instead of ROS 1 as Ubuntu 22.04 has been pre-installed for us on the given team laptop (Legion). But before continuing, I found a picture online (see below) to help alleviate confusion between the different terms that keep popping up in ROS — Noetic, Jammy, Foxy, Humble, Jazzy, etc. which I know can be super confusing.

<figure>
  <img src="/assets/img/robotics_md.png" alt="User interacting with VR interface">
  <figcaption style="font-size: 0.8em; color: #666; text-align: center;">
  Basically, Ubuntu versions are called 'distros' and ROS versions are called 'distributions'. For Ubuntu, common 'distros' are 18.04 (Bionic), 20.04 (Focal) and 22.04 (Jammy). Whereas for ROS, common 'distributions' are Foxy, Galactic, Humble, Melodic, Noetic and Jazzy. 
</figcaption>
</figure>


## 2. Main Contributions
- Configuring the TurtleBot3, following the step-by-step <a href="https://emanual.robotis.com/docs/en/platform/turtlebot3/quick-start/#pc-setup">e-Manual Guide</a> from ROBOTIS. I was happy to be able to apply my prior knowledge of terminal commands to support my team in completing the software set up for the TurtleBot3 with all the necessary installations.
- Report writing (structure + content)

## 3. Takeaways 
As a beginner in robotics, working with my peers to program, debug, and test the TurtleBot3 using ROS 2 was challenging yet rewarding. I am still very new to the field of robotics, but I learnt a lot more about ROS 2, OpenCV using YOLO, and how to troubleshoot errors effectively as a team. I am curious to explore more about this field in the future and am confident that the more I learn, the more interesting it will be. 
