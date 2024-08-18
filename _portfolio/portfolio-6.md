---
title: "OpenGL Motion Planning Visualizations"
excerpt: "<br/><img src='/images/OpenGL_1.png'>"
collection: portfolio
---

This project utilizes C++ and custom OpenGL libraries to provide visualizations of various grid-based and sampling-based motion planners through an easily accessible user interface. The user can customize the start position, goal position and environment obstacles for each planner, and visualize how the algorithm propagates to find the optimal path. 

![](/images/opengl_ui.png)

### Grid-Based Motion Planning

Grid-based approaches discretizes the entire configuration space into into grid cells and assume each configuration is identified with a grid point. Search algorithms like A* are then used to find a path from the start to the goal state. Since the grid grows exponentially with the configuration space dimension, they aren't preferred for high-dimensional problems.

#### Djikstra

![](/images/djikstra.gif)

#### A*

![](/images/a_star.gif)

#### Weighted A*

![](/images/wastar.gif)

### Sampling-Based Motion Planning

Sampling-based approaches use random sampling to explore the configuration space, and build a tree or a roadmap connecting feasible states. These algorithms are well suited for high dimensional planning problems.

