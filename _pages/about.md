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

I have graduated with a Bachelor’s degree in Robotics Engineering from [Guangzhou University](https://www.gzhu.edu.cn/). I worked on "AI for Social Good" and my research interest includes：
-  **Hyperbolic Theory**
-  **AI for Healthcare**
-  **Medical Image Processing**
-  **Computer Vision**
-  **Natural Language Processing**


I am very fortunate to be advised by [Prof. Huang](https://jd.gzhu.edu.cn/info/1150/3954.htm) from Guangzhou University.

You can find my CV here:[Haizhou Xu’s Curriculum Vitae](../files/CV.pdf).

# 🔥 News
- *2024.06*: &nbsp;🎉🎉 ‘Occult lymph node metastasis prediction in non-small cell lung cancer based self-supervised pretrained and hyperbolic theory’ have been accepted by **Applied Soft Computing**. [Link](https://www.sciencedirect.com/science/article/abs/pii/S1568494624007233) (Top Journal Q1 IF=7.2)
- *2023.10*: &nbsp;🎉🎉 I received a first prize scholarship.
- *2023.05*: &nbsp;🎉🎉 ‘MRP-Net: Seizure detection method based on modified recurrence plot and additive attention convolution neural network’ have been accepted by **Biomedical Signal Processing and Control**. [Link](https://www.sciencedirect.com/science/article/abs/pii/S1746809423005980) (First Student Author) (Q1 IF=4.9)
- *2023.03*: &nbsp;🎉🎉 ‘Hyperbolic Music Transformer for Structured Music Generation’ have been accepted by **IEEE Access**. [Link](https://ieeexplore.ieee.org/document/10070602) (Q2 IF=3.4)

# 📝 Publications

- Occult lymph node metastasis prediction in non-small cell lung cancer based self-supervised pretrained and hyperbolic theory <br/>
**Haizhou Xu**, Jiaqi Wu, Yujia Yu, Wenkai Huang<sup>†</sup>, Jiong Ni<sup>†</sup> <br/>
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
Wenkai Huang<sup>†</sup>, **Haizhou Xu**, Yujia Yu <br/>
*Biomedical Signal Processing and Control* | [paper](../files/paper2.pdf)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">new</div><img src='../images/paper2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Abstract:** Electroencephalographic (EEG) signals play an important role in the detection of seizures in epilepsy, and accurate detection of seizures can buy patients valuable treatment time. However, most seizure detection methods ignore the nonlinear, implicit characteristics of EEG, which has some impact on the accuracy of detection. Therefore, in this paper, we propose an EEG epilepsy detection network (MRP-Net) based on modified recurrence plot (MRP) and additive attention convolution neural network. This network can fully take into account the nonlinear, occult characteristics of EEG which can be mapped to the two-dimensional plane and served as the input of additive attention convolution neural network to automatically learn, analyze, and extract the EEG characteristics of seizures. The performance of the proposed method was evaluated on the Bonn University dataset and the SWEC-ETHZ short-term dataset. Sensitivity, specificity and accuracy were 100\% in multiple detection tasks in the University of Bonn single-channel EEG dataset. The sensitivity, specificity and accuracy of SWEC's short-term, multi-channel EEG dataset were 99.77\%, 99.57\% and 99.69\%, respectively, higher than the latest methods (3.76\%, 4.73\% and 4.27\%). The results of the experiments show that the network in this paper is superior and universal in epilepsy detection.
</div>
</div>


- Hyperbolic Music Transformer for Structured Music Generation <br/>
Wenkai Huang, Yujia Yu, **Haizhou Xu**, Zhiwen Su, Yu Wu<sup>†</sup> <br/>
*IEEE Access* | [paper](../files/paper1.pdf)


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">new</div><img src='../images/paper1.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


**Abstract:** In the field of music generation, generating structured music is a highly challenging research topic. Music generation methods are currently learned in Euclidean space and usually modeled as a time series without structural properties, but due to the limitations of the time series representation in Euclidean space, the hierarchical structure of music is difficult to learn, and the generated music is poorly structured. Therefore, based on hyperbolic theory, this paper proposes a Hyperbolic Music Transformer model, which considers the hierarchy in music and models the structured components of music in hyperbolic space. Meanwhile, in order for the network to have sufficient capacity to learn music data with hierarchical and power regular structure, a hyperbolic attention mechanism is proposed, which is an extension of the attention mechanism in hyperbolic space based on the definition of hyperboloid and Klein model. Subjective and objective experiments show that the model proposed in this paper is able to generate high-quality music with structure.
</div>
</div>



<!-- # 💻 Projects -->
# 💻 Blog

<!-- <div class="paper-card">

  <div class="paper-left">
    <img src="../images/paper2.png" alt="Sample Image" class="paper-image">
  </div>


  <div class="paper-right">
    <h3>Depth Pro: Sharp Monocular Metric Depth in Less Than a Second</h3>
    <div class="paper-meta">
      <span class="meta-item">apple/ml-depth-pro</span>
      <span class="meta-item">• PyTorch</span>
      <span class="meta-item">• 2 Oct 2024</span>
    </div>
    <p>We present a foundation model for zero-shot metric monocular depth estimation.</p>

    <div class="tags">
      <span class="tag">Monocular Depth Estimation</span>
      <span class="tag">Test</span>
    </div>
  </div>


  <div class="paper-actions">

    <div class="stars-box">
      <span class="stars">⭐ 2,730</span>
    </div>
    <span class="rate">3.06 stars/hour</span>


    <div class="button-group">
      <a href="#" class="paper">Paper</a>
      <a href="#" class="code">Code</a>
    </div>
  </div>
</div>
<br/>
<br/> -->

<!-- 第一篇博客 -->
<div class="paper-card">
  <div class="paper-left">
    <img src="../images/ST-SSL.jpg" alt="Sample Image" class="paper-image">
  </div>

  <div class="paper-right">
    <h3>ST-SSL paper and code notes</h3>
    <div class="paper-meta">
      <span class="meta-item">• Traffic prediction</span>
      <span class="meta-item">• 10 Oct 2024</span>
    </div>
    <p>This blog provides an overview of ST-SSL (Spatial-Temporal Self-Supervised Learning), a framework designed for learning from spatial-temporal graph data. It introduces the key components of ST-SSL, including adaptive graph augmentation, spatial-temporal encoding, and self-supervised learning techniques. </p>

    <div class="tags">
      <span class="tag">Paper notes</span>
      <span class="tag">Deep Learning</span>
      <span class="tag">GNN</span>
      <span class="tag">Mathematical Derivation</span>
    </div>
  </div>

  <div class="paper-actions">
    <div class="stars-box">
      <span class="views">🔍 <span id="totalViews4">0</span> views</span> <!-- 修改ID -->
    </div>

    <div class="button-group">
      <a href="../files/Blog/ST-SSL/ST-SSL.html" class="paper" onclick="updateViewCount('blog-004', 'totalViews4')">Link</a> <!-- 修改onclick函数 -->
    </div>
  </div>
</div>
<br/>
<br/>

<!-- 第二篇博客 -->
<div class="paper-card">
  <div class="paper-left">
    <img src="../images/blog3.png" alt="Sample Image" class="paper-image">
  </div>

  <div class="paper-right">
    <h3>DDPM Formula Derivation</h3>
    <div class="paper-meta">
      <span class="meta-item">• Diffusion Models</span>
      <span class="meta-item">• 8 Dec 2023</span>
    </div>
    <p>This blog offers a detailed derivation of Denoising Diffusion Probabilistic Model (DDPM) formulas, explaining key concepts like forward/reverse diffusion and noise scheduling. It helps readers understand DDPM’s core equations and its application in generative modeling.</p>

    <div class="tags">
      <span class="tag">Generative Models</span>
      <span class="tag">Deep Learning</span>
      <span class="tag">Mathematical Derivation</span>
    </div>
  </div>

  <div class="paper-actions">
    <div class="stars-box">
      <span class="views">🔍 <span id="totalViews3">0</span> views</span> <!-- 修改ID -->
    </div>

    <div class="button-group">
      <a href="../files/Blog/DDPM%20Formula%20Derivation/DDPM%20Formula%20Derivation.html" class="paper" onclick="updateViewCount('blog-003', 'totalViews3')">Link</a> <!-- 修改onclick函数 -->
    </div>
  </div>
</div>
<br/>
<br/>

<!-- 第三篇博客 -->
<div class="paper-card">
  <div class="paper-left">
    <img src="../images/blog2.jpg" alt="Sample Image" class="paper-image">
  </div>

  <div class="paper-right">
    <h3>4090x2 Linux Deep Learning Server Configuration Tutorial</h3>
    <div class="paper-meta">
      <span class="meta-item">• GPU Server Configuration</span>
      <span class="meta-item">• 15 Jan 2023</span>
    </div>
    <p>This blog is a tutorial on configuring an Ubuntu 4090 deep learning server, detailing steps for installing drivers, software, and frameworks. It helps users optimize their server for efficient deep learning performance with the 4090 GPU.</p>

    <div class="tags">
      <span class="tag">Ubuntu</span>
      <span class="tag">Linux Configuration</span>
      <span class="tag">Deep Learning</span>
    </div>
  </div>

  <div class="paper-actions">
    <div class="stars-box">
      <span class="views">🔍 <span id="totalViews2">0</span> views</span> <!-- 修改ID -->
    </div>

    <div class="button-group">
      <a href="../files/Blog/Ubuntu/Ubuntu.html" class="paper" onclick="updateViewCount('blog-002', 'totalViews2')">Link</a> <!-- 修改onclick函数 -->
    </div>
  </div>
</div>
<br/>
<br/>

<!-- 第四篇博客 -->
<div class="paper-card">
  <div class="paper-left">
    <img src="../images/blog1.jpg" alt="Sample Image" class="paper-image">
  </div>

  <div class="paper-right">
    <h3>Notion Mathematical Formula</h3>
    <div class="paper-meta">
      <span class="meta-item">• Notion</span>
      <span class="meta-item">• 1 Jun 2022</span>
    </div>
    <p>The blog provides detailed instructions on using KaTeX to write mathematical formulas in Notion, covering expressions like fractions, roots, matrices, subscripts, and superscripts. It explains how to insert and display these formulas effectively, with code examples and results for easy reference and application.</p>

    <div class="tags">
      <span class="tag">KaTeX</span>
      <span class="tag">Markdown</span>
    </div>
  </div>

  <div class="paper-actions">
    <div class="stars-box">
      <span class="views">🔍 <span id="totalViews1">0</span> views</span> <!-- 修改ID -->
    </div>

    <div class="button-group">
      <a href="../files/Blog/Notion%20mathematical%20formula/notion%20mathematical%20formula.html" class="paper" onclick="updateViewCount('blog-001', 'totalViews1')">Link</a> <!-- 修改onclick函数 -->
    </div>
  </div>
</div>
<br/>
<br/>

<!-- JavaScript -->
<script>
  function updateViewCount(blogId, viewId) {
    // 从 localStorage 获取当前博客页面的总阅读量
    let totalViews = localStorage.getItem(`${blogId}-totalViews`) || 0;
    totalViews++;

    // 将新的阅读量存储到 localStorage
    localStorage.setItem(`${blogId}-totalViews`, totalViews);

    // 更新对应页面中的阅读量
    document.getElementById(viewId).innerText = totalViews;
  }

  // 初始化函数，加载时显示当前阅读量
  function initViewCount(blogId, viewId) {
    let totalViews = localStorage.getItem(`${blogId}-totalViews`) || 0;
    document.getElementById(viewId).innerText = totalViews;
  }

  // 调用初始化函数分别为每个博客页面设置
  initViewCount('blog-001', 'totalViews1');
  initViewCount('blog-002', 'totalViews2');
  initViewCount('blog-003', 'totalViews3');
  initViewCount('blog-004', 'totalViews4');
</script>

# 🎖 Honors and Awards

- *2023.10* The First Prize Scholarship. (TOP 5%)

# 📖 Educations

- *2020.09 - 2024.06* Robot Engineering(BE), Guangzhou University. 

# 🦄 Welcome to my website
<body>
<div style="width: 400px; margin: 0 auto">
<script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=FWcAvbJHBYyiUmF5Dy1peB6x7e_Go99fnOmyUDI7KA4&cl=ffffff&w=a"></script>
</div>
</body>
