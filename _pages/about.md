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

My research focuses on Brain-inspired Computing, specifically enhancing the performance of Spiking Neural Networks (SNNs) to tackle increasingly complex tasks. I am passionate about bridging the gap between biological efficiency and artificial intelligence.

I am always open to collaborations or discussions regarding SNNs and neuromorphic computing. Feel free to reach out—let’s connect!


# Educations
- *2019.09 - 2023.06*, B.E. in Computer Science and Technology (East China University of Science and Technology)
- *2023.09 - 2024.06*, M.S. in Computer Science and Technology (East China University of Science and Technology, Withdrawn)
- *2024.09 - 2029.06 (Expected)*, Ph.D. Student in Computer Science and Technology (School of Computer Science, Zhejiang University).


# News

- *2026.07*: &nbsp;🎉🎉 One paper on temporal modeling in Spiking Transformers was accepted for publication in **Neural Networks**!

- *2026.07*: &nbsp;🎉🎉 One review paper on attention mechanisms in SNNs was accepted for publication in **Journal of Automation and Intelligence**!

- *2026.05*: &nbsp;🎉🎉 One paper on mitigating visual hallucinations in MLLMs was accepted to **ICML 2026**!

- *2025.06*: &nbsp;🎉🎉 One paper on SNNs for Image Classification was accepted by **ICCV-2025**!

# Publications

## Brain-Inspired Computing
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv(2608.08541)</div><img src='../images/retinking_attention_locality.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Rethinking Attention Locality in Spiking Transformers \\
**Zeqi Zheng**, Zizheng Zhu, Yuping Yan, et al.
- Rethinks attention locality in Spiking Transformers, revealing that computational locality does not necessarily translate into spatial locality and that uniform locality enhancement overlooks architectural differences, motivating an architecture-aware locality design.
- [![](https://img.shields.io/badge/Paper-fff?logo=readthedocs&logoColor=000)](https://arxiv.org/pdf/2608.08541)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Neural Networks</div><img src='../images/nn_enhancing.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Enhancing Spiking Transformers with Temporal Feedback Coding and Global-Local Dynamic Neurons \\
**Zeqi Zheng**, Zizheng Zhu, Yingchao Yu, et al.
- TFC and GLD-LIF jointly enhance spike pattern diversity and temporal modeling in Spiking Transformers, achieving consistent performance gains with limited computational overhead.
- [![](https://img.shields.io/badge/Paper-fff?logo=readthedocs&logoColor=000)](https://doi.org/10.1016/j.neunet.2026.109338)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Journal of Automation and Intelligence</div><img src='../images/joa_spike_attention.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
Attention mechanisms in Spiking Neural Networks: From neural encoding to hardware implementation \\
Doudou Wu\*, **Zeqi Zheng\***, Yaochu Jin†
- This survey systematically reviews attention mechanisms in SNNs, spanning neural encoding, algorithmic design, and neuromorphic hardware implementation, while highlighting key challenges and future directions.
- [![](https://img.shields.io/badge/Paper-fff?logo=readthedocs&logoColor=000)](https://doi.org/10.1016/j.jai.2026.07.003)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV-2025 (Poster)</div><img src='../images/spiliformer.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
SpiLiFormer: Enhancing Spiking Transformers with Lateral Inhibition \\
**Zeqi Zheng**\*, Yancheng Huang\*, Yingchao Yu, et al.
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

- ![](https://img.shields.io/badge/-Nature_Communications-darkblue) Spinal-inspired Artificial Tactile Interneuron with High-order Burst Spiking for Intelligent Edge Interfaces
<br> Fanfan Li, Zhanglu Yan, Jiayi Mao, Guolei Liu, Huihui Ren, Bangbang Qin, Zhongfang Zhang, Haiyue Zhang, Yiyang Shen, **Zeqi Zheng**, Weilong Feng, Dingwei Li, Yingjie Tang, Saisai Wang, Yaochu Jin, Tao Luo, Weng-fai Wong, Hong Wang, Bowen Zhu
<br> [![](https://img.shields.io/badge/Paper-fff?logo=readthedocs&logoColor=000)](https://www.nature.com/articles/s41467-026-76185-0)

- ![](https://img.shields.io/badge/-ICML--2026-darkblue) Mitigating Visual Hallucinations via Semantic Curriculum Preference Optimization in MLLMs
<br> Yuanshuai Li, Yuping Yan, Junfeng Tang, Yunxuan Li, **Zeqi Zheng**, Yaochu Jin
<br> [![](https://img.shields.io/badge/Paper-fff?logo=readthedocs&logoColor=000)](https://openreview.net/forum?id=VbQg7jQnpL)

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

# Academic Services
- **Conference Reviewer:** AAAI 2026, ACM-MM 2026, AAAI 2027
- **Journal Reviewer:** Complex & Intelligent Systems, IEEE Transactions on Cognitive and Developmental Systems

# Honors and Awards
- *2023* Best Student Paper Award (DOCS 2023)
- *2019-2023* School Academic Scholarship (First & Second Prize)

# Welcome
<script type="text/javascript" id="mapmyvisitors" src="//mapmyvisitors.com/map.js?d=JVw5S4Jsj4wixdpcVE6JzlZMpvHPgFnfz076Ub8nrJU&cl=ffffff&w=200"></script>
