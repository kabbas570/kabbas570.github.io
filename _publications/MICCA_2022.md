---
title: "Sequential Segmentation of the Left Atrium and Atrial Scars Using a Multi-scale Weight Sharing Network and Boundary-based Processing"
collection: publications
permalink: /publication/2020-02-SEEK
excerpt: "Left atrial (LA) segmentation and quantification of atrial scars"
date: 2022-09-18
venue: 'MICCAI 2022'
imageurl: '/images/publications/MICCAI2022.png'
paperurl: '/files/MICCAI2022.pdf'
link: '/publication/2020-02-SEEK](http://eecs.qmul.ac.uk/~gslabaugh/publications/Khan_MICCAIW2022.pdf'

---
<center><img src = '/images/publications/MICCAI2022.png'></center>
## Abstract  
Left atrial (LA) segmentation and quantification of atrial
scars have opened a path to automating Atrial Fibrillation (AF) diagnosis. This paper proposes a two-stage approach for sequential segmentation of the LA cavity and scars. Our Multi-scale Weight Sharing (MSWS) Network extracts features at multiple scales and is used for LA cavity segmentation. We also propose a Boundary2Patches method which performs segmentation of scars around the detected LA cavity boundary. The MSWS network learns a better representation of features through sharing weights across scales, and the Boundary2Patches method focuses on smaller scars constrained in the region around the LA cavity wall. On the challenge cohort (validation set), our method achieves an average Dice score of 0.938 and 0.558 for the LA cavity and scars segmentation of task 1, and a Dice score of 0.846 for LA cavity segmentation of task 2. The pre-trained models, source code, and implementation details are
available at https://github.com/kabbas570/LAScarQS2022.
## Files
- [Paper](/files/MICCAI2022.pdf)
