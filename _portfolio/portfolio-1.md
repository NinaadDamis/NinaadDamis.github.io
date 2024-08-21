---
title: "Planning and Decision Making in Robotics"
excerpt: "<br/><img src='/images/Planning_1.gif'>"
collection: portfolio
---

## Path Planning Towards a Moving Target

Implemented a Weighted A* planner to generate a plan for a point Robot (Pink) to catch a moving target (Green) on a 8-connected 2D grid.

![](/images/map1_catch.gif)


## Planning for N-DOF Arms

Implemented sampling-based planners to plan a collision-free path from a start to a goal position defined as joint angles for a high DOF planar arm.

### RRT

![](/images/rrtgif_16782.gif) 

### RRT*

![](/images/rrtstar_16782.gif)

### RRT-Connect

![](/images/rrtconnect_16782.gif)

### PRM

![](/images/prm_16782.gif)


## Symbolic Planner for Task Planning

Implemented a generic symbolic planner based on the STRIPS framework, and validated it on three environments - Blocks, Blocks and Triangles and Fire Extinguisher.

![](/images/symbolic_planner_1.png)