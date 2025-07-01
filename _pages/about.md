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

# About Me

I am a third-year Ph.D. student at the School of Computer Science and Engineering in Sun Yat-sen University (SYSU), where I am advised by <a href="https://chenliang.tech/">Prof. Liang Chen</a>. I received a Master's and a Bachelor’s degree from South China Agricultural University (SCAU), respectively in 2021 and 2019. My research interests include:
<ul>
<li><p>Large Language Models</p>
</li>
<li><p>Graph Learning</p>
</li>
<li><p>Trustworthy AI (e.g., Fairness, Reliability, etc.)</p>
</li>
</ul>
<p><b>🔥🔥🔥 I am in the 2026 fall job market and actively seeking postdoctoral and industry opportunities. Feel free to reach out to me via email (zhuych27@mail2.sysu.edu.cn) or WeChat (13416486396).</b></p>

# 💻 Internships
- *2024.03 - 2025.05*, [Tencent AI Lab](https://ailab.tencent.com/ailab/zh/index), Machine Intelligence Group, Shenzhen, China.

# 🔥 News
- *2025.05*: &nbsp;🎉🎉 One paper on diversity evaluation of LLM-generated data was accepted by **ICML 2025**.  

# 📝 Publications 
## Published
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2025</div><img src='images/dcscore_icml25.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Measuring Diversity in Synthetic Datasets](https://arxiv.org/pdf/2502.08512)

**Yuchang Zhu**, Huizhe Zhang, Bingzhe Wu, Jintang Li, Zibin Zheng, Peilin Zhao, Liang Chen, Yatao Bian

[**Project**](https://github.com/BlueWhaleLab/DCScore) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- A novel diversity evaluation method from the classification perspective for LLM-generated data. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">KDD 2024</div><img src='images/fairinv_kdd24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[One Fits All: Learning Fair Graph Neural Networks for Various Sensitive Attributes](https://arxiv.org/pdf/2406.13544)

**Yuchang Zhu**, Jintang Li, Yatao Bian, Zibin Zheng, Liang Chen

[**Project**](https://github.com/ZzoomD/FairINV/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- A graph group fairness method from the causal perspective for multiple sensitive attributes. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">WWW 2024</div><img src='images/fairsad_www24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Fair Graph Representation Learning via Sensitive Attribute Disentanglement](https://arxiv.org/pdf/2405.07011)

**Yuchang Zhu**, Jintang Li, Zibin Zheng, Liang Chen

[**Project**](https://github.com/ZzoomD/FairSAD) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- A disentangled-based method to improve the fairness of GNNs while preserving utility. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">WSDM 2024</div><img src='images/fairgkd_wsdm24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[The devil is in the data: Learning fair graph neural networks via partial knowledge distillation](https://arxiv.org/pdf/2311.17373)

**Yuchang Zhu**, Jintang Li, Liang Chen, Zibin Zheng

[**Project**](https://github.com/ZzoomD/FairGKD/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- A graph group fairness method based on knowledge distillation for unknown sensitive attributes. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TCSS 2024</div><img src='images/fairagg_tcss24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Fairagg: Toward fair graph neural networks via fair aggregation](https://ieeexplore.ieee.org/abstract/document/10516580)

**Yuchang Zhu**, Jintang Li, Liang Chen, Zibin Zheng

[**Project**]() <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- A graph group fairness method to achieve fair aggregation. 
</div>
</div>

- [A smartphone-based six-dof measurement method with marker detector](https://ieeexplore.ieee.org/abstract/document/9869710); Yuchang Zhu, Yuan Huang, Yuanhong Li, Zhi Qiu, Zuoxi Zhao; IEEE Transactions on Instrumentation and Measurement (TIM), 2022.

## Preprints
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2025</div><img src='images/sagif_arxiv25.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SaGIF: Improving Individual Fairness in Graph Neural Networks via Similarity Encoding](https://arxiv.org/pdf/2506.18696)

**Yuchang Zhu**, Jintang Li, Huizhe Zhang, Liang Chen, Zibin Zheng

[**Project**](https://github.com/ZzoomD/SaGIF) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- A graph individual fairness method based on similarity encoding. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2025</div><img src='images/diversity_arxiv25.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[What Matters in LLM-generated Data: Diversity and Its Effect on Model Fine-Tuning](https://arxiv.org/pdf/2506.19262)

**Yuchang Zhu**\*, Qunshu Lin\*, Haotong Wei\*, Xiaolong Sun, Zixuan Yu, Minghao Liu, Zibin Zheng, Liang Chen

[**Project**]() <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Investigate the impact of LLm-generated data from a diversity perspective. 
</div>
</div>


# 🎖 Honors and Awards
- *2024.11* National Scholarship (Top 0.4% nationwide).
- *2021.06* Excellent Master’s Thesis Award, SCAU
- *2019.06* Excellent Bachelor’s Thesis Award, SCAU
- *2019.06* Excellent Undergraduate Graduate of SCAU (10/550)
- *2016.09* National Endeavor Scholarship. 

# 📄 Curriculum Vitae
<div class="cv-container">
  <p class="cv-update-date">Last updated: 2025-07-01</p>
  <div class="download-container">
    <div class="download-item">
      <div class="download-content">
        <h3>English CV</h3>
        <p>You can download a PDF copy of my English CV <a href="/files/(250630) AcademicCV_YuchangZhu.pdf" target="_blank">here</a>.</p>
      </div>
    </div>

<div class="download-item">
  <div class="download-content">
    <h3>中文简历</h3>
    <p>您可以在<a href="/files/朱裕昌-个人简历-0623.pdf" target="_blank">这里</a>下载我的中文简历PDF版本。</p>
  </div>
</div>
