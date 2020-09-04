---
caption:
  title: Project 4
  subtitle: Mobile Robot Maze Exploration
  thumbnail: assets/img/projects/botlab1.png

title: Mobile Robot Maze Exploration
subtitle: Robot Platform Development, Forward/Inverse Kinematics, Particle Filter, Path Planning
image: assets/img/projects/botlab2.png
alt: image alt text
---
The SLAM (with particle filter), path planning, exploration and block retrieval functions are designed and implemented on a mobile robot. 
The robot is equipped with BeagleBone Green for motion control and Raspberry Pi for SLAM and arm module. <br>

With these subsystems, the robot is capable of exploring in unknown environment, constructing a map of the environment and retrieving blocks in it. The occupancy grid mapper in the SLAM system is able to generate grid maps at the resolution of 0.05 m, the Monte Carlo localization algorithm is able to reach a mean accuracy of 0.05 m in translation and 0.08 rad in rotation. <br>

This system completed four tasks which included: 1) completing four circuits around a convex arena, 2) detection and relocation of six blocks within convex area, 3) exploration and mapping of an unknown environment, and 4) detection and relocation of 8 blocks scattered across a map.