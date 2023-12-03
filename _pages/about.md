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

# 🫠 About Me

Hi, I'm Zeyu Han, an undergraduate student at Sichuan University, majoring in software engineering. Recently I'm serving as a research intern under the guidance of [Saiqian Zhang](https://saiqianzhang.com/) at New York University. Before that, I also worked with [Huaizu Jiang](https://jianghz.me/) at Northeastern University, [Dongkuan Xu](https://dongkuanx27.github.io/) at NC State University, and [Yan Wang](https://cs.scu.edu.cn/info/1359/16745.htm) at Sichuan University.

## Ph.D. Aspirations

<span style="color: darkred;">I'm looking for a Ph.D. position for Fall 2024. Wishing for good fortune on this academic journey!</span>


## Research Interests

My research focuses on the emerging paradigm of foundation models (large language models (LLMs), diffusion models, vision-language models, etc.). These models represent a shift towards larger, more capable, and general-purpose AI interfaces. My specific interests include:

1. **Grounded Application with Foundation Models**: Exploring ways to utilize existing foundation models to create innovative, valuable, and practical applications, which can democratize to serve a broader range of people.

2. **Acceleration of Foundation Models**: Enhancing the computational efficiency of foundation models during both training stage (parameter-efficient fine-tuning (PEFT), training data efficiency, etc.) and inference stage (efficient architecture design, algorithm/hardware co-design, etc.). 

The general goal is to maximize the potential of foundation models, making them more accessible and efficient for various domain-specific applications.

Currently, I am focusing on but not limited to these research topics:

- DNN acceleration (PEFT methods)
- Visual grounding
- Tool-augmented LLMs ([Gentopia](https://gentopia-ai.github.io/Gentopia-AI-Homepage/))
- Practical applications of generative models (image reconstruction, AI healthcare, etc.)

# 🔥 News
- *2023.11.29*: &nbsp;Feel free to check our new paper [Zero-shot REC](https://arxiv.org/pdf/2311.17048.pdf)
- *2023.10.03*: &nbsp;Gentopia accepted by EMNLP 2023 system demo!
- *2023.08.05*: &nbsp;🎉🎉 My first personal website is established! I eagerly anticipate further research opportunities and publications will enrich its content!

# 📘 Preprints

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv preprints</div><img src='images/cvpr24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Zero-shot Referring Expression Comprehension via Structural Similarity Between Images and Captions](https://arxiv.org/pdf/2311.17048.pdf)

**Zeyu Han**, Fangrui Zhu, Qianru Lao, Huaizu Jiang

[**code** (coming soon)]
- <span style="font-size: 0.8em; line-height: 0.7;">This paper presents a zero-shot referring expression comprehension method using several large foundation models, i.e., ChatGPT and Vision-Language Alignment models. We build a two-stage grounding pipeline that explicitly model the relationship between entities to refer visual objects.</span>
</div>
</div>

# 📝 Publications 

(<sup>*</sup> indicates equal contribution;  <sup>#</sup> indicates corresponding authorship.) 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2023</div><img src='images/Gentopia.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Gentopia.AI: A Collaborative Platform for Tool-Augmented LLMs](https://arxiv.org/pdf/2308.04030.pdf)

Binfeng Xu, Xukun Liu, Hua Shen, **Zeyu Han**, Yuhan Li, Murong Yue, Zhiyuan Peng, Yuchen Liu, Ziyu Yao, Dongkuan Xu

[**project page**](https://gentopia-ai.github.io/Gentopia-AI-Homepage/)
- <span style="font-size: 0.8em; line-height: 0.7;">This paper presents Gentopia, a lightweight and extensible framework for LLM-driven Agents and ALM research. It also maintains GentPool, a platform engineered to facilitate the registration and sharing of specialized agents, which seamlessly integrates GentBench, an ALM benchmark devised specifically for the comprehensive performance evaluation of agents.</span>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MICCAI 2023</div><img src='images/MICCAI2023.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Contrastive Diffusion Model with Auxiliary Guidance for Coarse-to-Fine PET Reconstruction](https://arxiv.org/abs/2308.10157) (MICCAI 2023)

**Zeyu Han<sup>*</sup>**, Yuhan Wang<sup>*</sup>, Luping Zhou, Peng Wang, Binyu Yan, Jiliu Zhou, Yan Wang<sup>#</sup>, and Dinggang Shen<sup>#</sup>

[**code**](https://github.com/Show-han/PET-Reconstruction)
- <span style="font-size: 0.8em; line-height: 0.7;">This paper presents a coarse-to-fine PET reconstruction framework using diffusion models. The coarse-to-fine design can significantly improve the overall sampling speed of our method. Furthermore, two additional strategies, i.e., an auxiliary guidance strategy and a contrastive diffusion strategy, are proposed and integrated into the reconstruction process, which can enhance the correspondence between the LPET image and the RPET image, further improving clinical reliability.</span>
</div>
</div>

- [Polymerized Feature-based Domain Adaptation for Cervical Cancer Dose Map Prediction](https://arxiv.org/abs/2308.10142), 
Jie Zeng<sup>*</sup>, **Zeyu Han<sup>*</sup>**, Xingchen Peng, Jianghong Xiao, Peng Wang, Yan Wang<sup>#</sup> (ISBI 2023)

# 🎖 Honors and Awards
- *2022.12, 2021.12, 2020.12*, National Scholarship for Encouragement, Sichuan University

# 📖 Educations
- *2019.09 - 2024.06*, Undergraduate, Sichuan University

# 🐝 Academic Services
Reviewer
- International Workshop on Resource-Efficient Learning for Knowledge Discovery (KDD 2023 workshop)
- International Conference on Medical Image Computing and Computer Assisted Intervention (MICCAI 2023)

# 🐾 Miscellaneous

## Piano

I enjoy playing piano in my spare time and upload some of my plays to [Bilibili](https://space.bilibili.com/36980576). Give me some likes and coins please! 😊😊

## Cat

I feed a lovely cat named Crescent. She is a American Shorthair and is very cute. Her mbti is infj (same as mine). I love her very much! 🥰🥰

Some photos of her:
<div style="display: flex; align-items: flex-start; gap: 20px;">

    <figure style="display: inline-block;">
        <img src='images/cat1.png' alt="Cat" style="max-height: 200px; display: block; width: auto; box-shadow: 4px 4px 8px rgba(0, 0, 0, 0.2); border: 1px solid #e0e0e0; box-sizing: border-box;">
    </figure>

      <figure style="display: inline-block;">
        <img src='images/cat3.png' alt="Cat 3" style="max-height: 200px; display: block; width: auto; box-shadow: 4px 4px 8px rgba(0, 0, 0, 0.2); border: 1px solid #e0e0e0; box-sizing: border-box;">
    </figure>

    <figure style="display: inline-block;">
        <img src='images/cat2.png' alt="Cat 2" style="max-height: 200px; display: block; width: auto; box-shadow: 4px 4px 8px rgba(0, 0, 0, 0.2); border: 1px solid #e0e0e0; box-sizing: border-box;">
    </figure>


</div>
