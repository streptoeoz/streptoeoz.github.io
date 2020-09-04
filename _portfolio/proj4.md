---
caption:
  title: Project 4
  subtitle: Drainage Inspection Robot
  thumbnail: assets/img/projects/drainbot2.png

title: Drainage Inspection Robot
subtitle: Robot Platform Development, Object Detection, 3D Reconstruction
image: assets/img/projects/drainbot1.png
alt: image alt text
---
We develop an autonomous drains inspection robot platform that detects water and debris by using its onboard vision system. I mainly worked on debris detection algorithm utilizing 3D point cloud constructed from the stereo system and deployment of the visual module on the robot. <br>

The debris detection algorithm is separated into three different parts. Firstly, the point cloud of the scene is reconstructed based on the stereo vision cameras' output. Then, two sections of points along the drain are extracted and projected onto the X-Y plane. Secondly, an iterative constrained line searching algorithm is applied to obtain the drain ground markers, which represent the ground's shape. Subsequently, this shape is extended to 3D dimensions to remove the cloud's points along the ground planes. Finally, the rest of the points are clustered and classified as debris or obstacles based on their positions to the ground markers. <br>

The robot was tested in a 100-meter drain in Singapore. 99% and 91% of the water and debris were correctly detected, respectively. Furthermore, an obstacle obstructing the robot's progression inside the drain was recognized 90% out of 20 trials. 

<!-- {:.list-inline}
- Date: January 2017
- Client: Explore
- Category: Graphic Design -->