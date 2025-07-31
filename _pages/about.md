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

I'm a first-year Ph.D. student at [University of California, Santa Cruz](https://www.ucsc.edu/), where I am fortunate to be advised by [Prof. Cihang Xie](https://cihangxie.github.io). I received my B.S. degree in Computer Science from [Zhejiang University](https://www.zju.edu.cn/english/) in 2023. Previously, I spent wonderful time at National University of Singapore, Shanghai AI Lab and PhiGent Robotics.

My research focuses on **multimodal learning**, **vision-language pretraining**, and **vision foundation models**.  
I'm particularly interested in developing **vision-centric models** that serve as general-purpose backbones in multimodal systems. I aim to build scalable and adaptable vision encoders that deeply understand visual inputs and interface naturally with language, enabling broader reasoning and interaction.

I am currently a Student Researcher at Google, working on generative AI for video creation.

<!-- I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2025.05*: &nbsp;🖼️ We release [**OpenVision**](https://ucsc-vlaa.github.io/OpenVision), a fully-open and cost-effective family of vision encoders that match or outperform proprietary models like OpenAI's CLIP and Google’s SigLIP in multimodal tasks!
- *2025.04*: &nbsp; ✨ I will join Google as a Student Researcher in the Sunnyvale office!
- *2024.11*: &nbsp;🚀 We release [CLIPS](https://ucsc-vlaa.github.io/CLIPS/), which achieves SOTA results in zero-shot image-text retrieval on MSCOCO and Flickr30K and enhances the visual capability of LLaVA.
- *2024.09*: &nbsp;🚀 I join VLAA Lab at UCSC as a Ph.D. student!

# 📝 Publications 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src='images/openvision_teaser_v1.3.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[OpenVision: A Fully-Open, Cost-Effective Family of Advanced Vision Encoders for Multimodal Learning](https://arxiv.org/abs/2505.04601)

Xianhang Li<sup>*</sup>, **Yanqing Liu**<sup>*</sup>, Haoqin Tu, Hongru Zhu, Cihang Xie  
<sup>*</sup>Equal contribution

[**Github**](https://github.com/UCSC-VLAA/OpenVision) <strong><span class='show_paper_citations' data='2obvvPoAAAAJ:u-x6o8ySG0sC'></span></strong>
- TL;DR: OpenVision is a fully-open and cost-effective vision encoder family that matches or surpasses proprietary models like OpenAI's CLIP and Google's SigLIP in multimodal tasks, offering over 25 models from 5.9M to 632M parameters for flexible deployment.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv</div><img src='images/clips.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CLIPS: An Enhanced CLIP Framework for Learning with Synthetic Captions](https://arxiv.org/pdf/2411.16828)

**Yanqing Liu**, Xianhang Li, Zeyu Wang, Bingchen Zhao, Cihang Xie

[**Github**](https://github.com/UCSC-VLAA/CLIPS) <strong><span class='show_paper_citations' data='2obvvPoAAAAJ:u-x6o8ySG0sC'></span></strong>
- This work introduces two simple yet effective designs to better leverage richly described synthetic captions, achieving state-of-the-art (SOTA) results in zero-shot image-text retrieval on MSCOCO and Flickr30K and enhancing the visual capability of LLaVA.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv</div><img src='images/mllms.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MLLMs-augmented Visual-language Representation Learning](https://arxiv.org/pdf/2311.18765)

**Yanqing Liu**, Kai Wang, Wenqi Shao, Ping Luo, Yu Qiao, Mike Zheng Shou, Kaipeng Zhang, Yang You

[**Github**](https://github.com/Yanqing0327/MLLMs-Augmented) <strong><span class='show_paper_citations' data='2obvvPoAAAAJ:9yKSN-GCB0IC'></span></strong>
- This work demonstrates the potential of Multimodal Large Language Models (MLLMs) to significantly enhance vision-language pre-training.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv</div><img src='images/pipeline_new.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DREAM+: Efficient Dataset Distillation by Bidirectional Representative Matching](https://arxiv.org/pdf/2310.15052)

**Yanqing Liu**, Jianyang Gu, Kai Wang, Zheng Zhu, Kaipeng Zhang, Wei Jiang, Yang You

[**Github**](https://github.com/Yanqing0327/DREAM) <strong><span class='show_paper_citations' data='2obvvPoAAAAJ:d1gkVwhDpl0C'></span></strong>
- This work presents the extended version of DREAM, achieving a remarkable **15x acceleration** in dataset distillation.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2023</div><img src='images/DREAM_ICCV_2023.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DREAM: Efficient Dataset Distillation by Representative Matching](https://openaccess.thecvf.com/content/ICCV2023/papers/Liu_DREAM_Efficient_Dataset_Distillation_by_Representative_Matching_ICCV_2023_paper.pdf)

**Yanqing Liu**, Jianyang Gu, Kai Wang, Zheng Zhu, Wei Jiang, Yang You

[**Github**](https://github.com/Yanqing0327/DREAM) <strong><span class='show_paper_citations' data='2obvvPoAAAAJ:u-x6o8ySG0sC'></span></strong>
- This work accelerates dataset distillation by over **8x**, significantly improving efficiency.
</div>
</div>
<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📖 Educations
- *2024.09 - now*,     Ph.D. student, University of California, Santa Cruz. 
- *2019.09 - 2023.06*, Undergraduate, College of Computer Science and Technology, Zhejiang Univeristy, Hangzhou.

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- *2023.08 - 2024.06*, [National University of Singapore](https://nus.edu.sg/), Singapore.
- *2023.05 - 2024.06*, [Shanghai AI Lab](https://www.shlab.org.cn/), China.
- *2023.01 - 2023.04*, [PhiGent Robotics](https://www.phigent.ai/en/), China.

# 📂 Activities
- Reviewer of CVPR 2024-2025, ICCV 2025, Neurips 2024, AAAI 2025, AISTATS 2025