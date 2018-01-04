---
layout:     post
title:      Tencent Captcha Recognition Using MobileNet
category: project
description: This project is to recognize the Captcha of Tencent QQ zone.
---

## This is the magic of CNN.

[Tencent-Captcha-Recognition][1] project is to recognize the Captcha of Tencent QQ zone using MobileNet.

The Captcha contains four English characters:

![Captcha Sample](http://bohaohan.github.io/images/projects/cap_sample.png)

Instead of using regular convolutional filter, MobileNet adopts the combination of Deptwise filters
and Pointwise filters, which significantly reduces the parameters and operations of the convolution.


## The base module for MobileNet is:
![MobileNet Base Module](http://bohaohan.github.io/images/projects/mobilenet.png)

Using the feature maps produced by MobileNet, we add four parallel Fully connected layers and each layer outputs
the character respectively based on the feature maps.


## Reference
[MobileNets: Efficient Convolutional Neural Networks for Mobile Vision Applications](https://arxiv.org/abs/1704.04861)
[MobileNets Tensorflow](https://github.com/Zehaos/MobileNet)






  [1]: https://github.com/bohaohan/Tencent-Captcha-Recognition





  
