---
title: Wenbo Huang (黄文博) - TSAT"
layout: gridlay
excerpt: "Wenbo Huang: tsat"
sitemap: false
permalink: /tsat
---

[comment]: Title
<h2 align="center"> Deep Convolutional Networks with Tunable Speed-Accuracy Trade-off for Human Activity Recognition Using Wearables </h2>
<p>&nbsp;</p>

[comment]: Authors
<p style="text-align: center;">
<a style="color: #CC0000"> Xing Wang </a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a style="color: #CC0000"> Lei Zhang* </a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://wenbohuang1002.github.io/" style="color: #CC0000">Wenbo Huang </a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a style="color: #CC0000"> Shuoyuan Wang </a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a style="color: #CC0000"> Jun He </a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a style="color: #CC0000"> Aiguo Song </a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</p>
<p>&nbsp;</p>

[comment]: Abstract
<h3> Abstract </h3>
<p style="text-align:justify; text-justify:inter-ideograph;">Activity recognition plays a critical role in various
applications such as medical monitoring and rehabilitation. Deep
learning has recently made great development in wearable
based human activity recognition (HAR) area. However, real
HAR applications should be adaptive and flexible to available
computational budget. So far, this problem has rarely been
explored. In contrast to existing deep HAR researches focusing
on static networks, this paper aims to investigate adaptive net-
works, which can adjust their structure conditioned on available
computing resource to trade off between accuracy and speed.
We for the first time present an adaptive convolutional neural
network by dynamically modifying network width. Specifically,
first, instead of normal convolution, the network is stacked
by lower-triangular convolutional layers in order to remove
the impact of activation statistics caused by varying widths.
Second, instead of fixed sampling, we perform random sampling
over width, which can provide smooth control for trade-off
between accuracy and speed. As a consequence, the networks
with different widths are simultaneously trained as subnetworks
by accumulating their losses during each iteration. On multiple
HAR datasets such as UCI-HAR, PAMAP2 and OPPORTUNITY,
extensive experiments verify that the proposed approach can
consistently provide further improved efficiency on top of state-
of-the-art CNNs for HAR. Finally, evaluations are conducted
on a Raspberry Pi platform to demonstrate its usefulness and
practicality.</p>

<center>
<figure>
		<div id="projectid">
    <img src="{{ site.url }}{{ site.baseurl }}/images/projectpic/21_TIM_TSAT.png" width="700px" />
		</div>

<figcaption>
<br>
Figure 1. The overview

</figcaption>
</figure>
</center>


[comment]: Paper
<h3> Paper </h3>

- Paper: <a href="{{ site.url }}{{ site.baseurl }}/papers/Deep_Convolutional_Networks_with_Tunable_Speed-Accuracy_Trade-off_for_Human_Activity_Recognition_Using_Wearables.pdf" style="color: #CC0000"> Full-text link </a>

Please consider citing if this work and/or the corresponding code are useful for you:

```
@article{wang2021deep,
  title={Deep Convolutional Networks with Tunable Speed-Accuracy Trade-off for Human Activity Recognition Using Wearabless},
  author={Wang, Xing and Zhang, Lei and Huang, wenbo and He, Jun and Song, Aiguo},
  journal={IEEE Transactions on Instrumentation and Measurement},
  volume={70},
  pages={1--13},
  year={2021},
  publisher={IEEE}
}
```

[comment]: Code
<h3> Code </h3>
We use PyTorch to build network framework. Code is available online in ths github repository:
<a href="https://github.com/Chauncey-Wang/Tunable-Speed-Accuracy-Trade-off-for-HAR" style="color: #CC0000">[](https://github.com/Chauncey-Wang/Tunable-Speed-Accuracy-Trade-off-for-HAR)</a>.
