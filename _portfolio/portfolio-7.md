---
title: "Unpaired Image-to-Image translation from simulation to real world images"
excerpt: "<br/><img src='/images/VLR_PROJ_1.gif'>"
collection: portfolio
---

Unpaired image-to-image translation is a class of vision problems where the goal is to find the mapping between different image domains using unpaired training data.

![](/images/intro_1.png)

Simulation can be a powerful tool for understanding machine learning systems and designing methods to solve real-world problems. 
Machine learning systems for autonomous agents are often trained purely in simulation due to the abundance of data which can be generated. But these systems “doomed to succeed” at the desired task in a simulated environment, with the resulting models being incapable of operation in the real world. This project attempts to tackle this simulation-to-reality gap.

Our proposed method Trans-Cycle GAN tries to convert semanically segmented images from CARLA simulation into real-world Cityscapes images, which can then be used downstream for multiple tasks. We modify the CycleGAN architecture to introduce bipartite attention layers in the generator network to enable long range interactions between the encoded features. 

![](/images/vlr_arch.png)

We compare the results of our method with two standard baselines, CycleGAN and CUT GAN. 

![](/images/vlrprojres.png)



