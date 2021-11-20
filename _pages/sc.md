---
title: "Wenbo Huang (黄文博) - SC"
layout: gridlay
excerpt: "Wenbo Huang: sc"
sitemap: false
permalink: /sc/
---

[comment]: Title
<h2 align="center"> The Convolutional Neural Networks Training with Channel-Selectivity for Human Activity Recognition based on Sensors </h2>
<p>&nbsp;</p>

[comment]: Authors
<p style="text-align: center;">
<a href="https://wenbohuang1002.github.io/" style="color: #CC0000">Wenbo Huang </a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a style="color: #CC0000"> Lei Zhang* </a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a style="color: #CC0000">Qi Teng</a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</p>
<p>&nbsp;</p>

[comment]: Abstract
<h3> Abstract </h3>
<p style="text-align:justify; text-justify:inter-ideograph;">Recently, the state-of-the-art performance in various sensor based human activity recognition (HAR) tasks have been acquired by deep learning, which can extract automatically features from raw data. In order to obtain the best accuracy, many static layers have been always used to train deep neural networks, and their weight connectivity in network remains unchanged. Pursuing the best accuracy in mobile platforms with a very limited computational budget at millions of FLOPs is impractical. In this paper, we make use of shallow convolutional neural networks (CNNs) with channel-selectivity for the use of HAR. As we have known, it is for the first time to adopt channel-selectivity CNN for sensor based HAR tasks. We perform extensive experiments on 5 public benchmark HAR datasets consisting of UCI-HAR dataset, OPPORTUNITY dataset, UniMib-SHAR dataset, WISDM dataset, and PAMAP2 dataset. As a result, the channel-selectivity can achieve lower test errors than static layers. The existing performance of deep HAR can be further improved by the CNN with channel-selectivity without any extra cost.</p>

<center>
<figure>
		<div id="projectid">
    <img src="{{ site.url }}{{ site.baseurl }}/images/projectpic/21_JBHI_SC.png" width="700px" />
		</div>

<figcaption>
<br>
Figure 1. Overview of the model for HAR with channel-selectivity. Acc., Gyro. and Magn. independently represent accelerometer, gyroscope and magnetometer. The data collected by these sensors will be sent to computer. On the computer screen, it is the plot of snesor data on time.

</figcaption>
</figure>
</center>


[comment]: Paper
<h3> Paper </h3>

- Paper: <a href="{{ site.url }}{{ site.baseurl }}/papers/Huang-2021-The-convolutional-neural-networks-t.pdf" style="color: #CC0000"> Full-text link </a>

Please consider citing if this work and/or the corresponding code are useful for you:

```
@article{huang2021convolutional,
  title={The convolutional neural networks training with Channel-Selectivity for human activity recognition based on sensors},
  author={Huang, Wenbo and Zhang, Lei and Teng, Qi and Song, Chaoda and He, Jun},
  journal={IEEE Journal of Biomedical and Health Informatics},
  year={2021},
  publisher={IEEE}
}
```

[comment]: Code
<h3> Code </h3>
We use PyTorch to build network framework. Code is available online in ths github repository:
<a href="https://github.com/wenbohuang1002/-IEEE-JBHI-2021-Channel-Selectivity-CNN-for-HAR" style="color: #CC0000">https://github.com/wenbohuang1002/-IEEE-JBHI-2021-Channel-Selectivity-CNN-for-HAR</a>.
