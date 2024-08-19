---
title: "Visual Learning and Recognition"
excerpt: "<br/><img src='/images/VLR_1.gif'>"
collection: portfolio
---

## Weakly Supervised Object Localization

Implements a weakly supervised object detector which utilizes only image-level annotations and no bounding box annotations on the PASCAL VOC 2007 dataset.


![](/images/heat_combined.png)


![](/images/obj_combined.png)

## Visual Question Answering

In Visual Question Answering (VQA), given an image and a question about it, our goal is to select an answer from a large pool of possible answers. We implement a transformer based architecture which uses pre-trained ResNet18 and RoBERTa to featurize input images and text.


![](/images/vlr_3_vqa.png)

![](/images/arch_vqa.png)


## Generative Adversarial Networks

Trained GAN's with various losses on the CUB 2011 Dataset to generate realistic-looking samples of these birds.


### Vanilla GAN


![](/images/gan_3.png)


### Least Squares GAN


![](/images/lsgan_3.png)


### Wassertein GAN with Gradient Penalty


![](/images/wgan_3.png)