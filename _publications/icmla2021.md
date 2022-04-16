---
title: "ECG-Adv-GAN: Detecting ECG Adversarial Examples with Conditional Generative Adversarial Networks"
collection: publications
permalink: /publications/icmla2021
venue: "2021 20th IEEE International Conference On Machine Learning And Applications (ICMLA)"
date: 2021-09-13
citation: 'Khondker Fariha Hossain, <b>Sharif Amit Kamran </b>, Alireza Tavakkoli, Lei Pan, Daniel Ma, Sutharshan Rajasegarar, Chandan Karmaker.'
---
[[IEEE]](https://ieeexplore.ieee.org/document/9680168)

## Abstract
Electrocardiogram (ECG) acquisition requires an automated system and analysis pipeline for understanding specific rhythm irregularities. Deep neural networks have become a popular technique for tracing ECG signals, outperforming human experts. Despite this, convolutional neural networks are susceptible to adversarial examples that can misclassify ECG signals and decrease the model's precision. Moreover, they do not generalize well on the out-of-distribution dataset. The GAN architecture has been employed in recent works to synthesize adversarial ECG signals to increase existing training data. However, they use a disjointed CNN-based classification architecture to detect arrhythmia. Till now, no versatile architecture has been proposed that can detect adversarial examples and classify arrhythmia simultaneously. To alleviate this, we propose a novel Conditional Generative Adversarial Network to simultaneously generate ECG signals for different categories and detect cardiac abnormalities. Moreover, the model is conditioned on class-specific ECG signals to synthesize realistic adversarial examples. Consequently, we compare our architecture and show how it outperforms other classification models in normal/abnormal ECG signal detection by benchmarking real world and adversarial signals.