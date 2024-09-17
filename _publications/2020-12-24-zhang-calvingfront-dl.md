---
title: "An automated, generalized, deep-learning-based method for delineating the calving fronts of Greenland glaciers from multi-sensor remote sensing imagery"
collection: publications
category: manuscripts
# permalink: /publication/2009-10-01-paper-title-number-1
excerpt: 'This paper integrates seven satellite datasets into a single deep learning network and offers a sub-weekly calving front dataset.'
date: 2020-12-24
venue: 'REMOTE SENSING OF ENVIRONMENT'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://doi.org/10.1016/j.rse.2020.112265'
citation: 'Zhang, E., Liu, L., Huang, L., Ng, K.S., 2021. An automated, generalized, deep-learning-based method for delineating the calving fronts of Greenland glaciers from multi-sensor remote sensing imagery. Remote Sens Environ 254, 112265.'
---

In the past two decades, the data volume of remote sensing imagery in the polar regions has increased dramatically. The calving fronts of many Greenland glaciers have been undergoing substantial variations, and a comprehensive front dataset is necessary for better understanding such frontal dynamics. Therefore, there is a need for an automated approach to identifying glaciological features such as calving fronts. In 2019, three deep-learning-based methods were applied to calving front delineation, but were restricted to a specific area or dataset. Here, we develop a more generalized method that can be applied to a major outlet glacier or remote sensing datasets that are not included in the training. We integrate seven remote sensing datasets into a single deep learning network. The core datasets include optical (Landsat-8 and Sentinel-2) and synthetic aperture radar images (Envisat, ALOS-1 TerraSAR-X, Sentinel-1, and ALOS-2) taken over Jakobshavn Isbræ, Kangerlussuaq, and Helheim, spanning from 2002 to 2019. We evaluate four neural network architectures (e.g., U-Net, DeepLabv3+ with ResNet, DRN, and MobileNet as the backbones) and three histogram modification strategies (e.g., histogram normalization, linear stretching, and no histogram modification). We find that the combination of histogram normalization and DRN-DeepLabv3+ has the lowest test error, at 86 m. These promising results show that our method has a high generalization ability on various glaciers and data types.