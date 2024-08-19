---
title: "Inter-Vehicular Depth and Velocity Estimation using a Monocular Camera"
excerpt: "<br/><img src='/images/VLR_PROJ.gif'>"
collection: portfolio
---

The goal of this project was to estimate the relative velocity and depth of a specific vehicle from the camera mounted on the ego vehicle to develop ADAS which help cars respond better to unforeseeable triggers from the surroundings.


[![Inter-Vehicular Depth and Velocity Estimation using a Monocular Camera](https://markdown-videos-api.jorgenkh.no/url?url=https%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3D7-9PSNdkp2w%26ab_channel%3DSiddharthaNamburu)](https://www.youtube.com/watch?v=7-9PSNdkp2w&ab_channel=SiddharthaNamburu)


Since a majority of modern approaches tackling the problem of depth and velocity estimation are very data hungry and need a large amount of ground truth annotations, the focus of our project was to reduce this dependence on data, while maintaining the performance of the architecture.

We utilize the monocular 3D detection architecture Monoflex to estimate depth and then utilizes the Kalman Filter based AB3DMOT network to estimate the velocity of the object. Experiments on KITTI benchmark show that our approach is able to reduce its dependence on data while experiencing just a 3.7 % decrease in accuracy of depth estimation. 

![](/images/VLR_PROJ.gif)
