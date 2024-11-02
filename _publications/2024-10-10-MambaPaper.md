---
title: "CAMS: Convolution and Attention-Free Mamba-based Cardiac Image Segmentation"
date: 2025-02-28
collection: publications
excerpt: "Convolution and self-attention-free Mamba-based semantic Segmentation Network named CAMS-Net, Linearly Interconnected Factorized
Mamba (LIFM) block, Mamba-based Channel Aggregator and Spatial Aggregator"
venue: IEEE/CVF Winter Conference on Applications of Computer Vision (WACV-2025)
imageurl: '/images/publications/mamba.png'

---
<center><img src='/images/publications/mamba.png' alt='CAMS-Net Architecture' style="width:80%;"></center>
## Our Contributions   
- To the best of our knowledge, we are the first to
propose a convolution and self-attention-free Mambabased segmentation network, CAMS-Net.
- We propose a Linearly Interconnected Factorized
Mamba (LIFM) block to reduce the trainable parameters of Mamba and improve its non-linearity. LIFM
implements a weight-sharing strategy for different scanning directions, specifically for the two scanning
direction strategies of vision Mamba [55], to reduce the computational complexity further whilst maintaining accuracy.
- We propose a Mamba Channel Aggregator (MCA) and Mamba Spatial Aggregator (MSA) and demonstrate
how they can learn information along the channel and spatial dimensions of the features, respectively.
- Extensive experimental validation, including ablation studies, is conducted to showcase the efficacy of
our proposed model. Our proposed CAMS-Net outperforms existing state-of-the-art segmentation models on the CMR and the Multi-Disease, Multi-View, and Multi-Center (M&Ms-2) segmentation datasets, including pure CNN, self-attention, and hybrid self-attention, as well as methods using the original Mamba-based architecture combined with CNNs.

## [Paper Available Here](https://arxiv.org/abs/2406.05786)
