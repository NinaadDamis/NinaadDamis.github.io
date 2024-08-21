---
title: "Robot Localization and Mapping"
excerpt: "<br/><img src='/images/SLAM_1.gif'>"
collection: portfolio
---

## Particle Filter Localization

Implemented a Particle Filter to estimate pose of a differential drive robot using measurements from a 180-degree laser range finder.
<!-- - **Objective:** Design and analyze differential gearboxes using SAE 8620 and EN 36C to determine the most suitable material for specific automotive uses. -->
![](/images/pf_gif.gif)


## Extended kalman Filter SLAM

- Implemented a 2D EKF-SLAM solver in Python to estimate the trajectory of a 2D robot and the positions of the landmarks from the control input and measurements in an unknown environment.

- The magenta and blue ellipses represent the predicted and updated uncertainties of the robot’s position. The red and green ellipses represent the initial and updated uncertainties of the landmarks.

![](/images/ekf_slam.png)


## Dense 3D SLAM 

- Implemented a 3D dense SLAM system using point-based fusion by utilizing projective Iterative Closest Point (ICP) algorithm and point-based fusion.
- The image shows the resultant 3D reconstruction obtained for the ICL-NUIM dataset

<!-- ![](/images/slam_icp.png) -->
![](/images/slam_recon.png)