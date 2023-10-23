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

- *2023.10*: &nbsp;🎉🎉 I received a first prize scholarship.
- *2023.05*: &nbsp;🎉🎉 ‘MRP-Net: Seizure detection method based on modified recurrence plot and additive attention convolution neural network’ have been accepted by Biomedical Signal Processing and Control.
- *2023.03*: &nbsp;🎉🎉 ‘Hyperbolic Music Transformer for Structured Music Generation’ have been accepted by IEEE Access.

# 📝 Publications

- Self-Supervised Hyperbolic Metric Few-Shot Learning for Occult Lymph Node Metastasis Prediction in NSCLC <br/>
**Haizhou Xu**, Jiaqi Wu, Yujia Yu, Wenkai Huang, Jiong Ni <br/>
*IEEE TRANSACTIONS ON MEDICAL IMAGING(under review)* | [paper](../files/paper3.pdf)


<div class='paper-box'><div><div class="paper-image"><img src='../images/paper3.png' alt="sym" width="100%"></div></div>

<br/>
**Abstract:** Predicting occult lymph node metastasis in non-small cell lung cancer (NSCLC) patients before surgery is crucial for determining appropriate treatment plans. However, predicted occult lymph node metastases in NSCLC patients have been under-studied due to various challenges, such as the complexity and variability of lymph node characteristics. In addition, there is no publicly available pathologically confirmed predictive dataset of occult lymph node metastases in NSCLC patients for training and testing predictive algorithms. To address this challenge we retrospectively collect occult lymph node metastasis dataset (TJ-OLNM) that meet the criteria from NSCLC patients who undergo chest CT scans at Tongji Hospital of Tongji University between 2016 and 2021. Additionally, we introduce a novel self-supervised hyperbolic metric few-shot learning method, named Occult Lymph Node Metastasis Network (OLNM-Net), for accurate prediction of occult lymph node metastasis. In OLNM-Net, a self-supervised pretrained module is proposed to learn preliminary lymph node imaging features, and then a hyperbolic theory-based few-shot metric learning module is constructed to predict occult lymph node metastasis in NSCLC. We performed a comprehensive evaluation of the state-of-the-art prediction model and our OLNM-Net on the constructed TJ-OLNM dataset. The experimental results show that our OLNM-Net yields better performance in predicting occult lymph node metastasis in TJ-OLNM than traditional and other deep learning methods. This explores the possibility of preoperative prediction of occult lymph node metastasis in NSCLC from CT imaging features, providing a new scheme for the study of NSCLC disease.
</div>



- MRP-Net: Seizure detection method based on modified recurrence plot and additive attention convolution neural network <br/>
Wenkai Huang, **Haizhou Xu**, Yujia Yu <br/>
*Biomedical Signal Processing and Control* | [paper](../files/paper2.pdf)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">new</div><img src='../images/paper2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Abstract:** Electroencephalographic (EEG) signals play an important role in the detection of seizures in epilepsy, and accurate detection of seizures can buy patients valuable treatment time. However, most seizure detection methods ignore the nonlinear, implicit characteristics of EEG, which has some impact on the accuracy of detection. Therefore, in this paper, we propose an EEG epilepsy detection network (MRP-Net) based on modified recurrence plot (MRP) and additive attention convolution neural network. This network can fully take into account the nonlinear, occult characteristics of EEG which can be mapped to the two-dimensional plane and served as the input of additive attention convolution neural network to automatically learn, analyze, and extract the EEG characteristics of seizures. The performance of the proposed method was evaluated on the Bonn University dataset and the SWEC-ETHZ short-term dataset. Sensitivity, specificity and accuracy were 100\% in multiple detection tasks in the University of Bonn single-channel EEG dataset. The sensitivity, specificity and accuracy of SWEC's short-term, multi-channel EEG dataset were 99.77\%, 99.57\% and 99.69\%, respectively, higher than the latest methods (3.76\%, 4.73\% and 4.27\%). The results of the experiments show that the network in this paper is superior and universal in epilepsy detection.
</div>
</div>


- Hyperbolic Music Transformer for Structured Music Generation <br/>
Wenkai Huang, Yujia Yu, **Haizhou Xu** <br/>
*IEEE Access* | [paper](../files/paper1.pdf)


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">new</div><img src='../images/paper1.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


**Abstract:** In the field of music generation, generating structured music is a highly challenging research topic. Music generation methods are currently learned in Euclidean space and usually modeled as a time series without structural properties, but due to the limitations of the time series representation in Euclidean space, the hierarchical structure of music is difficult to learn, and the generated music is poorly structured. Therefore, based on hyperbolic theory, this paper proposes a Hyperbolic Music Transformer model, which considers the hierarchy in music and models the structured components of music in hyperbolic space. Meanwhile, in order for the network to have sufficient capacity to learn music data with hierarchical and power regular structure, a hyperbolic attention mechanism is proposed, which is an extension of the attention mechanism in hyperbolic space based on the definition of hyperboloid and Klein model. Subjective and objective experiments show that the model proposed in this paper is able to generate high-quality music with structure.
</div>
</div>



# 💻 Projects


# 🎖 Honors and Awards

- *2023.10* The First Prize Scholarship.

# 📖 Educations

- *2020.09 - 2023.10 (now)*, Robot Engineering(BE), Guangzhou University. 

# 🦄 Welcome to my website
<body>
<div style="width: 400px; margin: 0 auto">
<script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=FWcAvbJHBYyiUmF5Dy1peB6x7e_Go99fnOmyUDI7KA4&cl=ffffff&w=a"></script>
</div>
</body>
