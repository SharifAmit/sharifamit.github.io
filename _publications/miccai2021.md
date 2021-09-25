---
title: "RV-GAN: Retinal Vessel Segmentation from Fundus Images using Multi-scale Generative Adversarial Networks"
collection: publications
permalink: /publications/miccai2021
venue: "24th International Conference on Medical Image Computing and Computer Assisted Intervention (MICCAI)"
date: 2021-06-06
citation: '<b>Sharif Amit Kamran </b>, Khondker Fariha Hossain, Alireza Tavakkoli, Stewart Lee Zuckerbrod, Kenton M Sanders, Salah A Baker.'
---
[[Springer]](https://link.springer.com/chapter/10.1007/978-3-030-87237-3_4) [[Code]](https://github.com/SharifAmit/RVGAN)

## Abstract
High fidelity segmentation of both macro and microvascular structure of the retina plays a pivotal role in determining degenerative retinal diseases, yet it is a difficult problem. Due to successive resolution loss in the encoding phase combined with the inability to recover this lost information in the decoding phase, autoencoding based segmentation approaches are limited in their ability to extract retinal microvascular structure. We propose RV-GAN, a new multi-scale generative architecture for accurate retinal vessel segmentation to alleviate this. The proposed architecture uses two generators and two multi-scale autoencoding discriminators for better microvessel localization and segmentation. In order to avoid the loss of fidelity suffered by traditional GAN-based segmentation systems, we introduce a novel weighted feature matching loss. This new loss incorporates and prioritizes features from the discriminator's decoder over the encoder. Doing so combined with the fact that the discriminator's decoder attempts to determine real or fake images at the pixel level better preserves macro and microvascular structure. By combining reconstruction and weighted feature matching loss, the proposed architecture achieves an area under the curve (AUC) of 0.9887, 0.9914, and 0.9887 in pixel-wise segmentation of retinal vasculature from three publicly available datasets, namely DRIVE, CHASE-DB1, and STARE, respectively. Additionally, RV-GAN outperforms other architectures in two additional relevant metrics, mean intersection-over-union (Mean-IOU) and structural similarity measure (SSIM). 