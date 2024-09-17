---
title: "Using deep learning to map retrogressive thaw slumps in the Beiluhe region (Tibetan Plateau) from CubeSat images"
collection: publications
category: manuscripts
# permalink: /publication/2010-10-01-paper-title-number-2
excerpt: 'This paper is the first attempt to automatically delineate permafrost-thaw landslides from high-resolution (3-m) satellite imagery.'
date: 2019-11-22
venue: 'REMOTE SENSING OF ENVIRONMENT'
# slidesurl: 'http://academicpages.github.io/files/slides2.pdf'
paperurl: 'https://doi.org/10.1016/j.rse.2019.111534'
citation: 'Huang, L., Luo, J., Lin, Z., Niu, F., Liu, L., 2020. Using deep learning to map retrogressive thaw slumps in the Beiluhe region (Tibetan Plateau) from CubeSat images. Remote Sens Environ 237, 111534.'
---

Retrogressive thaw slumps (RTSs) are among the most dynamic landforms in permafrost areas, and their formation can be attributed to the thawing of ice-rich permafrost. The spatial distribution and impacts of RTSs on the Tibetan Plateau are poorly understood due to their remote location and the technical challenges of automatic mapping. In this study, we innovatively applied DeepLabv3+, a cutting-edge deep learning algorithm for semantic segmentation, to Planet CubeSat images, which are satellite images with high spatial and temporal resolution. Our method allows us to automatically delineate 220 RTSs within an area of 5200 km2 with an average precision of 0.541. The corresponding precision, recall, and F1 score are 0.863, 0.833, and 0.848 respectively, when the threshold of intersection over union is 0.5. Moreover, approximately 100 experiments on k-fold cross-validation (k = 3, 5, and 10) and data augmentation show that our method is robust. And a test in a different geographic area shows that the generalization of the trained model is very good. We find that (1) most of the RTSs are small (areas < eight ha and perimeters < 2000 m) and (2) RTSs preferentially develop at locations with gentle slopes (four to eight degrees), and in areas lower than the surroundings (the mean topographic position index is − 0.17 ) and receiving less solar radiation (i.e., north-facing slopes). The results show that the method can map RTSs automatically from Planet CubeSat images and can potentially be applied to larger areas.