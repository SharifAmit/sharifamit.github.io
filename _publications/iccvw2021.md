---
title: "VTGAN: Semi-supervised Retinal Image Synthesis and Disease Prediction using Vision Transformers"
collection: publications
permalink: /publications/iccvw2021
venue: "2021 IEEE/CVF International Conference on Computer Vision Workshop (ICCVW)"
date: 2021-08-11
citation: '<b>Sharif Amit Kamran </b>, Khondker Fariha Hossain, Alireza Tavakkoli, Stewart Lee Zuckerbrod, Salah A Baker.'
---
[[IEEE/CVF]](https://openaccess.thecvf.com/content/ICCV2021W/CVAMD/html/Kamran_VTGAN_Semi-Supervised_Retinal_Image_Synthesis_and_Disease_Prediction_Using_Vision_ICCVW_2021_paper.html) [[Arxiv]](https://arxiv.org/abs/2104.06757) [[Code]](https://github.com/SharifAmit/VTGAN)

## Abstract
In Fluorescein Angiography (FA), an exogenous dye is injected in the bloodstream to image the vascular structure of the retina. The injected dye can cause adverse reactions such as nausea, vomiting, anaphylactic shock, and even death. In contrast, color fundus imaging is a non-invasive technique used for photographing the retina but does not have sufficient fidelity for capturing its vascular structure. The only non-invasive method for capturing retinal vasculature is optical coherence tomography-angiography (OCTA). However, OCTA equipment is quite expensive, and stable imaging is limited to small areas on the retina. In this paper, we propose a novel conditional generative adversarial network (GAN) capable of simultaneously synthesizing FA images from fundus photographs while predicting retinal degeneration. The proposed system has the benefit of addressing the problem of imaging retinal vasculature in a non-invasive manner as well as predicting the existence of retinal abnormalities. We use a semi-supervised approach to train our GAN using multiple weighted losses on different modalities of data. Our experiments validate that the proposed architecture exceeds recent state-of-the-art generative networks for fundus-to-angiography synthesis. Moreover, our vision transformer-based discriminators generalize quite well on out-of-distribution data sets for retinal disease prediction.