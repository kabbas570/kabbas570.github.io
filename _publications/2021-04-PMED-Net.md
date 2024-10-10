---
title: "PMED-Net: Pyramid Based Multi-Scale Encoder-Decoder Network for Medical Image Segmentation"
collection: publications
permalink: /publication/2021-04-PMED-Net
excerpt: "Medical Image Segmentation."
date: 2021-04-16
venue: 'IEEE Access'
imageurl: '/images/publications/PMED.PNG'
paperurl: '/files/PMED-Net.pdf'
link: 'https://doi.org/10.1109/ACCESS.2021.3071754'
citation: '<strong>Khan. A</strong>,H. Kim and L. Chua. &quot;PMED-Net: Pyramid Based Multi-Scale Encoder-Decoder Network for Medical Image Segmentation.&quot; <i> IEEE Access , 2021</i>(9). doi:10.1109/ACCESS.2021.3071754'
---


<center><img src = '/images/publications/PMED.PNG'></center>

## Abstract
A pyramidical multi-scale encoder-decoder network, namely PMED-Net, is proposed for medical image segmentation. Different variants of encoder-decoder networks are in practice for segmenting the medical images and U-Net is the most widely used one. However, the existing architectures for segmenting medical images have millions of parameters that require enormous computations which results in memory and cost-inefficiency. To overcome such limitations, we come up with the idea of training small networks in
a cascaded form for coarse-to-fine prediction. The proposed adaptive network is extended up to six pyramid levels, and at each level, features are extracted at different scales of the input image. Each lightweight encoder-decoder network is trained independently to minimize loss, where succeeding level networks further refine the prior predictions. Evaluation and comparison of our architecture were performed on four different publicly available medical image segmentation datasets: International Skin Imaging Collaboration (ISIC) challenge 2018 dataset, brain tumor dataset, nuclei dataset, and X-ray dataset. The experimental results of the PMED-Net are either better or on par with other state-of-the-art networks in terms of IoU, F1-Score, and sensitivity metricsMoreover, PMED-Net is efficient in terms of parameterized complexity as it has 1/21.3, 1/21.1, 1/14.0, 1/11.6, 1/11.2, 1/6.64, and 1/4.95 times fewer parameters than SegNet, U-Net, BCDU-Net, CU-Net, FCN-8s, ORED-Net, and MultiResUNet respectively. 

## Files
- [Paper](/files/PMED-Net.pdf)
