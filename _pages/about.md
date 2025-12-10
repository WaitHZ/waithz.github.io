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

I am an incoming MPhil of HKUST CSE, supervised by [Prof. Junxian He](https://jxhe.github.io/). I received my B.S. degree in the CKC honor college at [Zhejiang University](https://www.zju.edu.cn/english/) in 2025, majoring in computer science. During my undergraduate years, I collaborated with [Dr. Jie Fu](https://bigaidream.github.io/) and [Prof. Ningyu Zhang](https://person.zju.edu.cn/en/ningyu).


# Publications 

(* denotes co-first authors)

<div class='paper-box-text' markdown="1">
<font color="CornFlowerBlue">The Tool Decathlon: Benchmarking Language Agents for Diverse, Realistic, and Long-Horizon Task Execution</font>
Junlong Li\*, Wenshuo Zhao\*, Jian Zhao\*, Weihao Zeng\*, **Haoze Wu**\*, Xiaochen Wang, Rui Ge, Yuxuan Cao, Yuzhen Huang, Wei Liu, Junteng Liu, Zhaochen Su, Yiyang Guo, Fan Zhou, Lueyang Zhang, Juan Michelini, Xingyao Wang, Xiang Yue, Shuyan Zhou, Graham Neubig, Junxian He\\
**Arxiv, 2025** |  [PDF](https://arxiv.org/abs/2510.25726) | [Code](https://github.com/hkust-nlp/Toolathlon) | [Page](https://toolathlon.xyz/) | [Dataset](https://huggingface.co/datasets/hkust-nlp/Toolathlon-Trajectories)
</div>

<div class='paper-box-text' markdown="1">
<font color="CornFlowerBlue">Mirage or Method? How Model-Task Alignment Induces Divergent RL Conclusions</font>
**Haoze Wu**\*, Cheng Wang\*, Wenshuo Zhao,, Junxian He\\
**MATH-AI@NeruIPS 2025** |  [PDF](https://arxiv.org/abs/2508.21188) | [Code](https://github.com/hkust-nlp/model-task-align-rl)
</div>


<div class='paper-box-text' markdown="1">
<font color="CornFlowerBlue">Recode: Updating code api knowledge with reinforcement learning</font>
**Haoze Wu**, Yunzhi Yao, Wenhao Yu, Ningyu Zhang\\
**AAAI 2026** |  [PDF](https://arxiv.org/abs/2506.20495) | [Code](https://github.com/zjunlp/ReCode) | [Dataset](https://huggingface.co/datasets/zjunlp/ReCode-Train-Data)
</div>

<div class='paper-box-text' markdown="1">
<font color="CornFlowerBlue">GW-MoE: Resolving Uncertainty in MoE Router with Global Workspace Theory</font>
**Haoze Wu**\*, Zihan Qiu\*, Zili Wang, Hang Zhao, Jie Fu\\
**Arxiv, 2024** |  [PDF](https://arxiv.org/abs/2406.12375) | [Code](https://github.com/WaitHZ/GW-MoE)
</div>


# Educations
- *2021.09 - 2025.06*, B.S.@ZJU, Compter Science

# Internships
- *2025.10 - present*, [Huawei Noah’s Ark Lab](http://dev3.noahlab.com.hk/), Shenzhen.
- *2024.10 - 2025.01*, [Shanghai AI Lab](https://www.shlab.org.cn/), Shanghai.

# Service
- Reviewer: NeruIPS