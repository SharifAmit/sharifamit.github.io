---
title: "Retinal Image Synthesis from Fundus to Fluroscein Angiography"
excerpt: "* A Conditional Generative Network for synthesizing Fluroscein Angio images from Fundus Photography."
collection: portfolio
---

[[GitHub: Fundus2Angio]](https://github.com/SharifAmit/Fundus2Angio)
[[GitHub: Attention2Angio]](https://github.com/SharifAmit/Attention2Angio)

Fluorescein Angiography (FA) is a technique that employs the designated camera for Fundus photography incorporating excitation and barrier filters. FA also requires fluorescein dye that is injected intravenously, which might cause adverse effects ranging from nausea, vomiting to even fatal anaphylaxis. Currently, no other fast and non-invasive technique exists that can generate FA without coupling with Fundus photography. To eradicate the need for an invasive FA extraction procedure, we introduce two Generative networks 1) Fundus2Angio and 2) Attention2Angio, that can synthesize Fluorescein Angiography from Fundus images. The proposed gan incorporates multiple attention based skip connections in generators and comprises novel residual blocks for both generators and discriminators. It utilizes reconstruction, feature-matching, and perceptual loss along with adversarial training to produces realistic Angiograms that is hard for experts to distinguish from real ones. Our experiments confirm that the proposed architecture surpasses recent state-of-the-art generative networks for fundus-to-angio translation task.

![img1](/images/isvc.png)
<!--<br/><img src='/images/isvc.png'>-->