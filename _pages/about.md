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

Hello, I am Zihan Luo, a CS Ph.D. candidate at [Huazhong University of Science and Technology](https://english.hust.edu.cn/) (HUST). I am fortunate to be supervised by Professor [Hong Huang](https://faculty.hust.edu.cn/honghuang/en/index.htm) and Senior Researcher [Jianxun Lian](https://www.microsoft.com/en-us/research/people/jialia/). Before that, I received my Bachelor degree in Electronic Engineering from HUST in 2020, and was fortunate to be advised by Professor [Rui Yin](https://rayin-saber.github.io/yinrui.github.io/) from 2019-2020.

My research interests include graph representation learning and Large Language Models (LLM), especially on topics like fairness and bias. I have published several papers at the top international AI conferences and journals with total Google Scholar citations 20+.


# 🔥 News
- *2024.03*: &nbsp;🎉🎉 Our paper on empowering LLMs with graph reasoning capability [GraphInstruct](https://arxiv.org/abs/2403.04483) is released on Arxiv.
- *2023.11*: &nbsp;🎉🎉 I am invited to give a spotlight sharing for our NeurIPS 2023 paper at [MLA 2023 conference](https://www.lamda.nju.edu.cn/conf/mla23/index.html). 
- *2023.09*: &nbsp;🎉🎉 Our paper on GNN debias is accepted by [NeurIPS 2023](https://neurips.cc/), accept rate 26.1%. 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv</div><img src='images/graphinstruct.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[GraphInstruct: Empowering Large Language Models with Graph Understanding and Reasoning Capability](https://arxiv.org/abs/2403.04483)

**Zihan Luo**, Xiran Song, Hong Huang, Jianxun Lian, Chenhao Zhang, Jinqi Jiang, Xing Xie, Hai Jin

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=JWUJkawAAAAJ&citation_for_view=JWUJkawAAAAJ:IjCSPb-OGe4C) <strong><span class='show_paper_citations' data='JWUJkawAAAAJ:IjCSPb-OGe4C'></span></strong>
- A comprehensive benchmark GraphInstruct on enhancing and improving the graph understanding and reasoning capability.
- [Code](https://github.com/CGCL-codes/GraphInstruct).
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2023</div><img src='images/neurips2023.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Cross-links Matter for Link Prediction: Rethinking the Debiased GNN from a Data Perspective](https://openreview.net/pdf?id=sJDkwMVqb9)

**Zihan Luo**, Hong Huang, Jianxun Lian, Xiran Song, Xing Xie, Hai Jin

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=JWUJkawAAAAJ&citation_for_view=JWUJkawAAAAJ:IjCSPb-OGe4C) <strong><span class='show_paper_citations' data='JWUJkawAAAAJ:IjCSPb-OGe4C'></span></strong>
- A framework on investigating and mitigating the bias on Cross-links from a data augmentation perspective.
- [Code](https://github.com/CGCL-codes/Cross-links-Bias).
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">WWW 2023</div><img src='images/xGCN.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[xGCN: An Extreme Graph Convolutional Network for Large-scale Social Link Prediction](https://dl.acm.org/doi/10.1145/3543507.3583340)

Xiran Song, Jianxun Lian, Hong Huang, **Zihan Luo**, Wei Zhou, Xue Lin, Mingqi Wu, Chaozhuo Li, Xing Xie, Hai Jin

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=JWUJkawAAAAJ&citation_for_view=JWUJkawAAAAJ:UeHWp8X0CEIC) <strong><span class='show_paper_citations' data='JWUJkawAAAAJ:UeHWp8X0CEIC'></span></strong>
- A novel GNN paradigm for large-scale social recommendation.
- [Code](https://github.com/CGCL-codes/XGCN_library).
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">WSDM 2022</div><img src='images/ada-GNN.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Ada-GNN: Adapting to Local Patterns for Improving Graph Neural Networks](https://dl.acm.org/doi/abs/10.1145/3488560.3498460)

**Zihan Luo**, Jianxun Lian, Hong Huang, Xing Xie, Hai Jin

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=JWUJkawAAAAJ&citation_for_view=JWUJkawAAAAJ:qjMakFHDy7sC) <strong><span class='show_paper_citations' data='JWUJkawAAAAJ:qjMakFHDy7sC'></span></strong>
- A novel GNN training framework for capturing graph local patterns while preserving global information.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Journal of Biomedical Informatics</div><img src='images/vipal.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ViPal: A Framework for Virulence Prediction of Influenza Viruses with Prior Viral Knowledge Using Genomic Sequences](https://www.biorxiv.org/content/biorxiv/early/2022/03/27/2022.03.24.485635.full.pdf)

Rui Yin\*, **Zihan Luo**\*, Pei Zhuang, Chee Keong Kwoh, Zhuoyi Lin

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=JWUJkawAAAAJ&citation_for_view=JWUJkawAAAAJ:u-x6o8ySG0sC) <strong><span class='show_paper_citations' data='JWUJkawAAAAJ:u-x6o8ySG0sC'></span></strong>
- Utilizing human prior knowledge for virulence prediction with posterior regularization.
- [Code](https://github.com/Rayin-saber/ViPal).
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Current Genomics</div><img src='images/current_genomics.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Exploring the lethality of human-adapted coronavirus through alignment-free machine learning approaches using genomic sequences](https://www.biorxiv.org/content/biorxiv/early/2020/07/31/2020.07.31.230904.full.pdf)

Rui Yin, **Zihan Luo**, Chee Keong Kwoh

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=JWUJkawAAAAJ&citation_for_view=JWUJkawAAAAJ:d1gkVwhDpl0C) <strong><span class='show_paper_citations' data='JWUJkawAAAAJ:d1gkVwhDpl0C'></span></strong>
- A simple framework for utilizing deep neural networks for coronavirus lethality prediction.
- [Code](https://github.com/Rayin-saber/Alignment-free-lethality-prediction-of-coronavirus).
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Bioinformatics</div><img src='images/virprenet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[VirPreNet: a weighted ensemble convolutional neural network for the virulence prediction of influenza A virus using all eight segments](https://www.biorxiv.org/content/biorxiv/early/2020/07/31/2020.07.31.230904.full.pdf)

Rui Yin, **Zihan Luo**, Pei Zhuang, Zhuoyi Lin, Chee Keong Kwoh

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=JWUJkawAAAAJ&citation_for_view=JWUJkawAAAAJ:2osOgNQ5qMEC) <strong><span class='show_paper_citations' data='JWUJkawAAAAJ:2osOgNQ5qMEC'></span></strong>
- A framework for utilizing deep neural networks for virulence prediction of influenza A virus.
- [Code](https://github.com/Rayin-saber/VirPreNet).
</div>
</div>

# 🎖 Honors and Awards
- Academic Scholarship, *2020.09*, *2021.09*, *2022.09*, *2023.09*.  
- Huawei Scholarship, *2022.06*. 
- Tencent Scholarship, *2022.03*.
- Finalist Award (Top 1%) at The Mathematical Contest in Modeling *2019*.

# 📖 Educations
- *2022.09 - 2026.06 (Expected)*, [School of Computer Science and Technology](https://cs.hust.edu.cn/), [Huazhong University of Science and Technology](https://www.hust.edu.cn/), Ph.D. Candidate.
- *2020.09 - 2022.06*, [School of Computer Science and Technology](https://cs.hust.edu.cn/), [Huazhong University of Science and Technology](https://www.hust.edu.cn/), Master. 
- *2016.09 - 2020.06*, [School of Electronic Information and Communication](https://ei.hust.edu.cn/), [Huazhong University of Science and Technology](https://www.hust.edu.cn/), Bachelor. 

# 💬 Invited Talks
- *2023.11*, Paper Spotlight Sharing at [MLA 2023 Conference](https://www.lamda.nju.edu.cn/conf/mla23/index.html) in Nanjing, China.

<div style="width: 25%">
<script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=abE_g9Z_jUhmkdimTMzMNVbaYRqEl2VF7OykTZVgvKc"></script>
<div>
