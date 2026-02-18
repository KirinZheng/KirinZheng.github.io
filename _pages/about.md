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

I am currently a Ph.D. student in the Joint Ph.D. Program between Zhejiang University and Westlake University (enrolled in the Fall of 2024). I conduct my research at the [School of Engineering](https://en-soe.westlake.edu.cn/), [Westlake University](https://en.westlake.edu.cn/), where I am privileged to be supervised by Prof. [Yaochu Jin](https://scholar.google.com/citations?user=B5WAkz4AAAAJ&hl=en).

My research primarily focuses on Brain-inspired Computing, with a specific emphasis on Spiking Neural Networks (SNNs). Driven by a passion for exploring the intersection of biological intelligence and artificial systems, I have also been expanding my research horizons into: i) investigating hallucinations in MLLMs; ii) exploring LLM-based planning and decision-making for robotics.

# Educations
- *2019.09 - 2023.06*, B.E. in Computer Science and Technology (East China University of Science and Technology)
- *2023.09 - 2024.06*, M.S. in Computer Science and Technology (East China University of Science and Technology, Withdrawn)
- *2024.09 - 2029.06 (Expected)*, Ph.D. Student in Computer Science and Technology (School of Computer Science, Zhejiang University).





# News

- *2025.06*: &nbsp;🎉🎉 One paper on SNNs for Image Classification was accepted by **ICCV-2025**!

# Publications

## Brain-Inspired Computing
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv(2508.00387)</div><img src='../images/stf.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
STF: Shallow-Level Temporal Feedback to Enhance Spiking Transformers \\
**Zeqi Zheng\***, Zizheng Zhu\*, Yingchao Yu, et al.
- STF introduces shallow-level temporal feedback into spiking Transformers, significantly enhancing spike pattern diversity and performance with minimal computational overhead.
- [![](https://img.shields.io/badge/Paper-fff?logo=readthedocs&logoColor=000)](https://arxiv.org/pdf/2508.00387)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV-2025 (Poster)</div><img src='../images/spiliformer.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
SpiLiFormer: Enhancing Spiking Transformers with Lateral Inhibition \\
**ZeqiZheng**\*, Yancheng Huang\*, Yingchao Yu, et al.
- SpiLiFormer incorporates brain-inspired lateral inhibition to mitigate attention distraction in Spiking Transformers, achieving SOTA performance.
- [![](https://img.shields.io/badge/Paper-fff?logo=readthedocs&logoColor=000)](https://openaccess.thecvf.com/content/ICCV2025/papers/Zheng_SpiLiFormer_Enhancing_Spiking_Transformers_with_Lateral_Inhibition_ICCV_2025_paper.pdf) \| [![](https://img.shields.io/badge/Code-fff?logo=github&logoColor=000)](https://github.com/KirinZheng/SpiLiFormer)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv(2505.15840)</div><img src='../images/tdformer.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
TDFormer: A Top-Down Attention-Controlled Spiking Transformer \\
Zizheng Zhu\*, Yingchao Yu\*, **Zeqi Zheng\***, et al.
- TDFormer introduces top-down attention to Spiking Transformers, enhancing temporal information integration with SOTA performance.
- [![](https://img.shields.io/badge/Paper-fff?logo=readthedocs&logoColor=000)](https://arxiv.org/pdf/2505.15840)
</div>
</div>



## Others

- ![](https://img.shields.io/badge/Arxiv--yellow) Mitigating Visual Hallucinations via Semantic Curriculum Preference Optimization in MLLMs
<br> Yuanshuai Li, Yuping Yan, Junfeng Tang, Yunxuan Li, **Zeqi Zheng**, Yaochu Jin
<br> [![](https://img.shields.io/badge/Paper-fff?logo=readthedocs&logoColor=000)](https://arxiv.org/pdf/2509.24491)

- ![](https://img.shields.io/badge/Arxiv--yellow) Sparse Autoencoders Bridge The Deep Learning Model and The Brain
<br> Ziming Mao, Jia Xu, **Zeqi Zheng**, Haofang Zheng, Dabing Sheng, Yaochu Jin, Guoyuan Yang
<br> [![](https://img.shields.io/badge/Paper-fff?logo=readthedocs&logoColor=000)](https://arxiv.org/pdf/2506.11123)

- ![](https://img.shields.io/badge/Arxiv--yellow) Think Small, Plan Smart: Minimalist Symbolic Abstraction and Heuristic Subspace Search for LLM-Guided Task Planning
<br> Junfeng Tang, Yuping Yan, Zihan Ye, Zhenshou, Song, **Zeqi Zheng**, Yaochu Jin
<br> [![](https://img.shields.io/badge/Paper-fff?logo=readthedocs&logoColor=000)](https://arxiv.org/pdf/2501.15214)

- ![](https://img.shields.io/badge/DOCS--2024-darkblue) A Personalized Federated Framework for Document-Level Biomedical Relation Extraction
<br> Yan Xiao, Yaochu Jin, Haoyu Zhang, Xu Huo, Qiqi Liu, **Zeqi Zheng**
<br> [![](https://img.shields.io/badge/Paper-fff?logo=readthedocs&logoColor=000)](https://ieeexplore.ieee.org/abstract/document/10704513)

- ![](https://img.shields.io/badge/DOCS--2023-darkblue) Federated Graph Neural Networks with Bipartite Embedding for Multi-objective Facility Location
<br> **Zeqi Zheng**, Ziqi Wang, Xueming Yan, Yaochu Jin, Shiqing Liu, Qiqi Liu
<br> [![](https://img.shields.io/badge/Paper-fff?logo=readthedocs&logoColor=000)](https://ieeexplore.ieee.org/abstract/document/10294834)

- ![](https://img.shields.io/badge/BIBM--2022-darkblue) Multi-medvit: A Deep Learning Approach for the Diagnosis of COVID-19 with the CT Images
<br> Yunjie Cai, **Zeqi Zheng**, Shanling Nie, Yue Guo, Ruijie Zhang, Hai Yang
<br> [![](https://img.shields.io/badge/Paper-fff?logo=readthedocs&logoColor=000)](https://ieeexplore.ieee.org/abstract/document/9994860)




# Honors and Awards
- *2023* Best Student Paper Award (DOCS 2023)
- *2019-2023* School Academic Scholarship (First & Second Prize)

# Welcome
<script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=O4LrMvOh7XJcTIi4ltzemELMhVYeIlYvQ0lf2mittHg&cl=ffffff&w=300"></script>