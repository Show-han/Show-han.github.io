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

I'm an incoming PhD student at [Khoury College of Computer Sciences, Northeastern University](https://www.khoury.northeastern.edu/) (2024 fall) advised by [Huaizu Jiang](https://jianghz.me/). Before that, I received my Bachelor's degree in 2024 from Sichuan University, advised by [Yan Wang](https://cs.scu.edu.cn/info/1359/16745.htm). I also worked with [Sai Qian Zhang](https://saiqianzhang.com/) at New York University. 

## Research Interests

I'm interested in generated models (e.g., diffusion models, multimodal LLMs), 3D vision (e.g., 3D generation), model acceleration, practical applications of large foundation models, etc.


# 🔥 News
- *2024.02.27*: &nbsp;[One first-authored paper](https://arxiv.org/pdf/2311.17048.pdf) accepted by CVPR 2024!
- *2023.10.03*: &nbsp;[One paper](https://arxiv.org/pdf/2308.04030.pdf) accepted by EMNLP 2023 System Demonstration!
- *2023.08.05*: &nbsp;🎉🎉 My first personal website is established! I eagerly anticipate further research opportunities and publications will enrich its content!

# 📝 Publications 

(<sup>*</sup> indicates equal contribution;  <sup>#</sup> indicates corresponding authorship.) 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2024</div><img src='images/peft_survey.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Parameter-Efficient Fine-Tuning for Large Models: A Comprehensive Survey](https://arxiv.org/pdf/2403.14608.pdf) 

**Zeyu Han**, Chao Gao, Jinyang Liu, [Jeff (Jun) Zhang](https://scholar.harvard.edu/jeff-jun-zhang/home), [Sai Qian Zhang](https://saiqianzhang.com/)

- <span style="font-size: 0.8em; line-height: 0.7;">We conduct a comprehensive survey for PEFT methods in the context of large models. This survey includes basic taxonomy of PEFT methods, efficient PEFT design, applications on various models and downstream tasks, and real-world system design challenges. We hope this survey can enable readers of various levels and disciplines to swiftly grasp the core concepts of PEFT. <a href="https://mp.weixin.qq.com/s/b16EPZ3z-LpGapGy2Q7ZUg" style="color: darkred;">[公众号“机器之心”中文宣传]</a>
</span>
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/cvpr24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Zero-shot Referring Expression Comprehension via Structural Similarity Between Images and Captions](https://arxiv.org/pdf/2311.17048.pdf) (CVPR 2024)

**Zeyu Han**, [Fangrui Zhu](https://fangruizhu.github.io/), [Qianru Lao](https://estherbear.github.io/), [Huaizu Jiang](https://jianghz.me/)

[**code**](https://github.com/Show-han/Zeroshot_REC)
- <span style="font-size: 0.8em; line-height: 0.7;">This paper presents a zero-shot referring expression comprehension method using several large foundation models, i.e., ChatGPT and Vision-Language Alignment models. We build a two-stage grounding pipeline that explicitly model the relationship between entities to refer visual objects.</span>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2023</div><img src='images/Gentopia.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Gentopia.AI: A Collaborative Platform for Tool-Augmented LLMs](https://arxiv.org/pdf/2308.04030.pdf) (EMNLP 2023 System Demo)

[Binfeng Xu](https://billxbf.github.io/), [Xukun Liu](https://www.emigroup.tech/index.php/member/xukun-liu/), [Hua Shen](https://hua-shen.org/), **Zeyu Han**, [Yuhan Li](https://twifor.github.io/), [Murong Yue](https://nlp.cs.gmu.edu/author/murong-yue/), [Zhiyuan Peng](https://jerrypeng21cuhk.github.io/), [Yuchen Liu](https://www.csc.ncsu.edu/people/yliu322), [Ziyu Yao](https://ziyuyao.org/), [Dongkuan Xu](https://dongkuanx27.github.io/)

[**project page**](https://gentopia-ai.github.io/Gentopia-AI-Homepage/)
- <span style="font-size: 0.8em; line-height: 0.7;">This paper presents Gentopia, a lightweight and extensible framework for LLM-driven Agents and ALM research. It also maintains GentPool, a platform engineered to facilitate the registration and sharing of specialized agents, which seamlessly integrates GentBench, an ALM benchmark devised specifically for the comprehensive performance evaluation of agents.</span>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MICCAI 2023</div><img src='images/MICCAI2023.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Contrastive Diffusion Model with Auxiliary Guidance for Coarse-to-Fine PET Reconstruction](https://arxiv.org/abs/2308.10157) (MICCAI 2023)

**Zeyu Han<sup>*</sup>**, [Yuhan Wang<sup>*</sup>](https://wyhlovecpp.github.io/), [Luping Zhou](https://sites.google.com/view/lupingzhou/home?authuser=0), Peng Wang, Binyu Yan, Jiliu Zhou, [Yan Wang<sup>#</sup>](https://cs.scu.edu.cn/info/1359/16745.htm), and [Dinggang Shen<sup>#</sup>](https://idea.bme.shanghaitech.edu.cn/)

[**code**](https://github.com/Show-han/PET-Reconstruction)
- <span style="font-size: 0.8em; line-height: 0.7;">This paper presents a coarse-to-fine PET reconstruction framework using diffusion models. The coarse-to-fine design can significantly improve the overall sampling speed of our method. Furthermore, two additional strategies, i.e., an auxiliary guidance strategy and a contrastive diffusion strategy, are proposed and integrated into the reconstruction process, which can enhance the correspondence between the LPET image and the RPET image, further improving clinical reliability.</span>
</div>
</div>

<!-- 
# 🎖 Honors and Awards
- *2022.12, 2021.12, 2020.12*, National Scholarship for Encouragement, Sichuan University -->

# 📖 Educations
- *2024.09 - present*, PhD, Northeastern University
- *2019.09 - 2024.06*, Undergraduate, Sichuan University

# 🐝 Academic Services
Reviewer
- NeurIPS 2024
- ACM MM 2024
- KDD 2023 workshop


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
        <img src='images/cat2.png' alt="Cat 2" style="max-height: 200px; display: block; width: auto; box-shadow: 4px 4px 8px rgba(0, 0, 0, 0.2); border: 1px solid #e0e0e0; box-sizing: border-box;">
    </figure>

    <figure style="display: inline-block;">
        <img src='images/cat4.jpg' alt="Cat 4" style="max-height: 200px; display: block; width: auto; box-shadow: 4px 4px 8px rgba(0, 0, 0, 0.2); border: 1px solid #e0e0e0; box-sizing: border-box;">
    </figure>

    <figure style="display: inline-block;">
        <img src='images/cat5.jpg' alt="Cat 5" style="max-height: 200px; display: block; width: auto; box-shadow: 4px 4px 8px rgba(0, 0, 0, 0.2); border: 1px solid #e0e0e0; box-sizing: border-box;">
    </figure>

    <figure style="display: inline-block;">
        <img src='images/cat6.jpg' alt="Cat 6" style="max-height: 200px; display: block; width: auto; box-shadow: 4px 4px 8px rgba(0, 0, 0, 0.2); border: 1px solid #e0e0e0; box-sizing: border-box;">
    </figure>


</div>
