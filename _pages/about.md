---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I’m a senior student majoring in Robotics Engineering at [Guangzhou University](https://www.gzhu.edu.cn/). My research interest includes：
-  **AI for Healthy**
-  **Medical Image Processing**
-  **Computer Vision**
-  **Machine Learning**


I am very fortunate to be advised by [Prof. Huang](https://jd.gzhu.edu.cn/info/1150/3954.htm) from Guangzhou University.

You can find my CV here:[ Haizhou Xu’s Curriculum Vitae](../files/CV.pdf).

# 🔥 News
- *2024.06*: &nbsp;🎉🎉 ‘Occult lymph node metastasis prediction in non-small cell lung cancer based self-supervised pretrained and hyperbolic theory’ have been accepted by **Applied Soft Computing**. [Link](https://www.sciencedirect.com/science/article/abs/pii/S1568494624007233) (Top Journal Q1 IF=7.2)
- *2023.10*: &nbsp;🎉🎉 I received a first prize scholarship.
- *2023.05*: &nbsp;🎉🎉 ‘MRP-Net: Seizure detection method based on modified recurrence plot and additive attention convolution neural network’ have been accepted by **Biomedical Signal Processing and Control***. [Link](https://www.sciencedirect.com/science/article/abs/pii/S1746809423005980) (First Student Author) [Link] (Q1 IF=4.9)
- *2023.03*: &nbsp;🎉🎉 ‘Hyperbolic Music Transformer for Structured Music Generation’ have been accepted by **IEEE Access**. [Link](https://ieeexplore.ieee.org/document/10070602) (Q2 IF=3.4)

# 📝 Publications

- Occult lymph node metastasis prediction in non-small cell lung cancer based self-supervised pretrained and hyperbolic theory <br/>
**Haizhou Xu**, Jiaqi Wu, Yujia Yu, Wenkai Huang*, Jiong Ni* <br/>
*Applied Soft Computing* | [paper](../files/paper3.pdf)

<!-- <div class="paper-box">
  <div class="paper-image">
  <div class="badge">new
  </div>
    <img src="../images/paper3.png" alt="sym" width="100%" />
  </div>
  <div class='paper-text' markdown="1">
  <br> -->
  <div class='paper-box'><div class='paper-box-image'><div><div class="badge">new</div><img src='../images/paper3.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  **Abstract:** Predicting occult lymph node metastasis in non-small cell lung cancer (NSCLC) patients is pivotal for tailoring appropriate surgical and therapeutic interventions. This prognostic factor remains underexplored, largely due to the intricate variability of occult lymph node characteristics and the absence of a pathologically confirmed predictive dataset. Addressing this gap, we retrospectively assembled a dataset of occult lymph node metastases (TJ-OLNM) from NSCLC patients who underwent chest Computed Tomography (CT) scans at Tongji Hospital, Tongji University from 2016 to 2021. Utilizing this dataset, we developed a novel self-supervised learning model, the Occult Lymph Node Metastasis Network (OLNM-Net), which leverages hyperbolic metric few-shot learning to enhance the prediction accuracy of occult metastases. Our comprehensive evaluations demonstrate that OLNM-Net significantly outperforms existing models in predicting occult lymph node metastasis, offering new insights into the preoperative assessment of NSCLC and advancing the application of machine learning in medical diagnostics.
</div>
</div>


- MRP-Net: Seizure detection method based on modified recurrence plot and additive attention convolution neural network <br/>
Wenkai Huang*, **Haizhou Xu**, Yujia Yu <br/>
*Biomedical Signal Processing and Control* | [paper](../files/paper2.pdf)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">new</div><img src='../images/paper2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Abstract:** Electroencephalographic (EEG) signals play an important role in the detection of seizures in epilepsy, and accurate detection of seizures can buy patients valuable treatment time. However, most seizure detection methods ignore the nonlinear, implicit characteristics of EEG, which has some impact on the accuracy of detection. Therefore, in this paper, we propose an EEG epilepsy detection network (MRP-Net) based on modified recurrence plot (MRP) and additive attention convolution neural network. This network can fully take into account the nonlinear, occult characteristics of EEG which can be mapped to the two-dimensional plane and served as the input of additive attention convolution neural network to automatically learn, analyze, and extract the EEG characteristics of seizures. The performance of the proposed method was evaluated on the Bonn University dataset and the SWEC-ETHZ short-term dataset. Sensitivity, specificity and accuracy were 100\% in multiple detection tasks in the University of Bonn single-channel EEG dataset. The sensitivity, specificity and accuracy of SWEC's short-term, multi-channel EEG dataset were 99.77\%, 99.57\% and 99.69\%, respectively, higher than the latest methods (3.76\%, 4.73\% and 4.27\%). The results of the experiments show that the network in this paper is superior and universal in epilepsy detection.
</div>
</div>


- Hyperbolic Music Transformer for Structured Music Generation <br/>
Wenkai Huang, Yujia Yu, **Haizhou Xu**, Zhiwen Su, Yu Wu <br/>
*IEEE Access* | [paper](../files/paper1.pdf)


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">new</div><img src='../images/paper1.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


**Abstract:** In the field of music generation, generating structured music is a highly challenging research topic. Music generation methods are currently learned in Euclidean space and usually modeled as a time series without structural properties, but due to the limitations of the time series representation in Euclidean space, the hierarchical structure of music is difficult to learn, and the generated music is poorly structured. Therefore, based on hyperbolic theory, this paper proposes a Hyperbolic Music Transformer model, which considers the hierarchy in music and models the structured components of music in hyperbolic space. Meanwhile, in order for the network to have sufficient capacity to learn music data with hierarchical and power regular structure, a hyperbolic attention mechanism is proposed, which is an extension of the attention mechanism in hyperbolic space based on the definition of hyperboloid and Klein model. Subjective and objective experiments show that the model proposed in this paper is able to generate high-quality music with structure.
</div>
</div>



<!-- # 💻 Projects -->
# 💻 Blog
Notion 数学公式 [Link](../files/Blog/Notion%20mathematical%20formula/notion%20mathematical%20formula.html)

Ubuntu 深度学习服务器配置教程 [link](../files/Blog/Ubuntu/Ubuntu.html)

DDPM 公式推导 [Link](../files/Blog/DDPM%20Formula%20Derivation/DDPM%20Formula%20Derivation.html)

# 🎖 Honors and Awards

- *2023.10* The First Prize Scholarship. (TOP 5%)

# 📖 Educations

- *2020.09 - 2024.06 Robot Engineering(BE), Guangzhou University. 

# 🦄 Welcome to my website
<body>
<div style="width: 400px; margin: 0 auto">
<script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=FWcAvbJHBYyiUmF5Dy1peB6x7e_Go99fnOmyUDI7KA4&cl=ffffff&w=a"></script>
</div>
</body>
