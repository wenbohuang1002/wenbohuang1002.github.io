---
title: "Wenbo Huang (黄文博) - SK"
layout: gridlay
excerpt: "Wenbo Huang: sk"
sitemap: false
permalink: /sk/
---

[comment]: Title
<h2 align="center"> Deep Neural Networks for Sensor-Based Human
Activity Recognition Using Selective
Kernel Convolution </h2>
<p>&nbsp;</p>

[comment]: Authors
<p style="text-align: center;">
<a style="color: #CC0000">Wenbin Gao </a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a style="color: #CC0000"> Lei Zhang* </a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a style="color: #CC0000">Wenbo Huang</a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</p>
<p>&nbsp;</p>

[comment]: Abstract
<h3> Abstract </h3>
<p style="text-align:justify; text-justify:inter-ideograph;">Recently,
the state-of-the-art performance
in various sensor-based human activity recognition (HAR) tasks has
been acquired by deep learning, which can extract automatically
features from raw data. In standard convolutional neural networks (CNNs), there is usually the same receptive field (RF)
size of artificial neurons within each feature layer. It is well
known that the RF size of neurons is able to change adaptively
according to the stimulus, which has rarely been exploited in
HAR. In this article, a new multibranch CNN is introduced,
which utilizes a selective kernel mechanism for HAR. To the best
of our knowledge, it is for the first time to adopt an attention
idea to perform kernel selection among multiple branches with
different RFs in the HAR scenario. We perform extensive
experiments on several benchmark HAR datasets, namely, UCI-
HAR, UNIMIB SHAR, WISDM, PAMAP2, and OPPORTUNITY,
as well as weakly labeled datasets. Ablation experiments show
that the selective kernel convolution can adaptively choose an
appropriate RF size among multiple branches for classifying
numerous human activities. As a result, it can achieve a higher
recognition accuracy under a similar computing budget.</p>

<center>
<figure>
		<div id="projectid">
    <img src="{{ site.url }}{{ site.baseurl }}/images/projectpic/21_TIM_SK.png" width="700px" />
		</div>

<figcaption>
<br>
Figure 1. Overview of the proposed SK network. The “SKConv” means the
selective kernel convolution.

</figcaption>
</figure>
</center>


[comment]: Paper
<h3> Paper </h3>

- Paper: <a href="{{ site.url }}{{ site.baseurl }}/papers/10.1109_tim.2021.3102735.pdf" style="color: #CC0000"> Full-text link </a>

Please consider citing if this work and/or the corresponding code are useful for you:

```
@article{gao2021deep,
  title={Deep neural networks for sensor based human activity recognition using selective kernel convolution},
  author={Gao, Wenbin and Zhang, Lei and Huang, Wenbo and Min, Fuhong and He, Jun and Song, Aiguo},
  journal={IEEE Transactions on Instrumentation and Measurement},
  year={2021},
  publisher={IEEE}
}
```

[comment]: Code
<h3> Code </h3>
We use PyTorch to build network framework. Code is available online in ths github repository:
<a href="https://wenbohuang1002.github.io/404" style="color: #CC0000">Coming soon</a>.
