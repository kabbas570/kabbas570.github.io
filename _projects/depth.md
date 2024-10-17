---
title: "End-to-End Supervised Stereo Imaging-Based Method for Depth Estimation
"
collection: projects
excerpt: "Measure of the distance of each point of the scene.
"
date: 2021-08-30
imageurl: '/images/projects/DEPTH1.png'

---

<center><img src="/images/projects/DEPTH1.png"></center>

## proposed Architecture

The proposed approach employs two encoders and one decoder. The encoders extract the features of stereo images, and the decoder reconstructs the depth map.
- An attention module named Spatial and Channel Attention Module (SCAM) is incorporated in the bottleneck to combine and emphasize the most meaningful features of encoders.
- Moreover, for better gradient propagation and faster convergence, the decoder module reuses the feature maps of encoders in two different ways, i.e., (1) concatenation and (2) element-wise addition using non-identity mapping.
- Extensive ablation studies are conducted to evaluate the proposed architecture's effectiveness and strategies. The experiments are conducted on three publicly available datasets: RGB+D scene, Cityscapes, and KITTI dataset

<center><img src="/images/projects/arch.png"></center>
<center><img src="/images/projects/R1.png"></center>
<center><img src="/images/projects/R2.png"></center>



