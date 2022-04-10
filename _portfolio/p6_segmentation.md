---
title: "Semantic Segmentation using FCN"
excerpt: "* A Fully Convolutional Neural Network with multi-scale skip connection and dilated convolution for Semantic Segmentation."
collection: portfolio
---

[[GitHub: Dilated-FCN2s]](https://github.com/SharifAmit/DilatedFCNSegmentation)

Semantic Segmentation using deep convolutional neural network pose more complex challenge for any GPU intensive task. As it has to compute million of parameters, it results to huge memory consumption. Moreover, extracting finer features and conducting supervised training tends to increase the complexity. With the introduction of Fully Convolutional Neural Network, which uses finer strides and utilizes deconvolutional layers for upsampling, it has been a go to for any image segmentation task. In this paper, we propose two segmentation architecture which not only needs one-third the parameters to compute but also gives better accuracy than the similar architectures. The model weights were transferred from the popular neural net like VGG19 and VGG16 which were trained on Imagenet classification data-set. Then we transform all the fully connected layers to convolutional layers and use dilated convolution for decreasing the parameters. Lastly, we add finer strides and attach four skip architectures which are element-wise summed with the deconvolutional layers in steps. We train and test on different sparse and fine data-sets like Pascal VOC2012, Pascal-Context and NYUDv2 and show how better our model performs in this tasks. On the other hand our model has a faster inference time and consumes less memory for training and testing on NVIDIA Pascal GPUs, making it more efficient and less memory consuming architecture for pixel-wise segmentation. 


![img6](/images/sain.png)
<!--<br/><img src='/images/sain.png'>-->
