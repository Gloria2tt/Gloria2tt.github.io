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

I am currently working at **WeChat AI Foundation Model Center, Tencent**, focusing on the development and research of [**WeLM**](https://welm.weixin.qq.com/), with emphasis on **Reinforcement Learning for LLMs** and the **integration of RL with model architecture**. Prior to this, I worked at **Baidu** on LLM post-training for [ERNIE / Wenxin Yiyan (文心一言)](https://yiyan.baidu.com/). Before that, I graduated from the Department of Electronic Engineering, Tsinghua University. During my graduate studies, I primarily worked on communication-related research. I later transitioned to machine learning, with a focus on vision-language foundation models and multimodal learning. 


# 🔥 News
- *2026.09*: &nbsp;🎉 One paper on long-horizon interactive world modeling accepted by **NeurIPS 2026**.
- *2026.07*: &nbsp;🎉 Two co-authored papers accepted: WildWorld by **ECCV 2026** and GraphWalker by **COLM 2026**.
- *2026.05*: &nbsp;🎉 One paper on agentic vision models via RL (PyVision-RL) accepted by **ICML 2026**.
- *2026.02*: &nbsp;🎉 One paper on video generation evaluation (SVBench) accepted by **CVPR 2026**.
- *2026.01*: &nbsp;🎉 One paper on video-guided audio generation (HarmoniDPO) accepted by **IJCV**.



# 📄 Technical Report
- [Sekai2: From World Exploration to Interactive World Modeling](https://arxiv.org/abs/2608.09449), Kang He, **Wenshuo Peng**, Zihui Gao, Jiaming Tan, Kaipeng Zhang, Yongtao Ge, *2026*
- [Hidden Decoding at Scale: Latent Computation Scaling for Large Language Models](https://arxiv.org/abs/2607.08186), WeChat AI Team, Tencent, *2026*
- [ERNIE 4.5 Technical Report](https://yiyan.baidu.com/blog/publication/ERNIE_Technical_Report.pdf), Baidu ERNIE Team, *2025*

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2026</div><img src='images/500x300.png' alt="GameVerse" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

GameVerse: A Minute-Scale Gameplay Dataset for Long-Horizon Interactive World Modeling

Kang He\*, **Wenshuo Peng**\*, Chuanhao Li, Zihui Gao, Xiaojie Xu, Zhengyuan Lin, Yuzhe Ding, Donghong Ji, Kaipeng Zhang, Yongtao Ge (\* equal contribution)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2026</div><img src='images/500x300.png' alt="PyVision-RL" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[PyVision-RL: Forging Open Agentic Vision Models via RL](https://arxiv.org/abs/2602.20739)

Shitian Zhao, Shaoheng Lin, Ming Li, Haoquan Zhang, **Wenshuo Peng**, Kaipeng Zhang, Chen Wei

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/svbench.png' alt="SVBench" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SVBench: Evaluation of Video Generation Models on Social Reasoning](https://arxiv.org/abs/2512.21507)

**Wenshuo Peng**, Gongxuan Wang, Tianmeng Yang, Chuanhao Li, Xiaojie Xu, Hui He, Kaipeng Zhang

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCV 2026</div><img src='images/ijcv.png' alt="HarmoniDPO" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[HarmoniDPO: Video-guided Audio Generation via Preference-Optimized Diffusion](https://link.springer.com/article/10.1007/s11263-025-02636-8)

**Wenshuo Peng**, Kaipeng Zhang

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2024</div><img src='images/aaai.png' alt="DAT" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Data Adaptive Traceback for Vision-Language Foundation Models in Image Classification](https://arxiv.org/abs/2407.08787)

**Wenshuo Peng**, Kaipeng Zhang, Yue Yang, Hao Zhang, Yu Qiao

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Findings of NAACL 2024</div><img src='images/t3m.png' alt="T3M" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[T3M: Text Guided 3D Human Motion Synthesis from Speech](https://arxiv.org/abs/2408.12885)

**Wenshuo Peng**, Kaipeng Zhang, SAI QIAN Zhang

</div>
</div>

- [WildWorld: A Large-Scale Dataset for Action-Conditioned World Modeling with Explicit State Annotations](https://arxiv.org/abs/2603.23497), Zhen Li, Zian Meng, Chuanhao Li, Shuwei Shi, **Wenshuo Peng**, Yuwei Wu, Bo Zheng, Yunde Jia, Kaipeng Zhang, **ECCV 2026**

- [GraphWalker: Agentic Knowledge Graph Question Answering via Synthetic Trajectory Curriculum](https://arxiv.org/abs/2603.28533), Shuwen Xu, Yao Xu, Jiaxiang Liu, Chenhao Yuan, **Wenshuo Peng**, Jun Zhao, Kang Liu, **COLM 2026**

- [Yume: An Interactive World Generation Model](https://arxiv.org/abs/2507.17744), Xiangyu Mao, Shaoheng Lin, Zhen Li, Chuanhao Li, **Wenshuo Peng**, Tong He, Jiangmiao Pang, Mingming Chi, Yu Qiao, Kaipeng Zhang, *arXiv 2025*

- [Multi-relational Pedestrian Trajectory Prediction in Complex Scenes](https://ieeexplore.ieee.org/document/10012858), **Wenshuo Peng**, Zhoujuan Cui, Yiping Duan, Xiaoming Tao, **IEEE VTC 2022**

# 📖 Educations
- *2021.09 - 2024.06*, M.S., Tsinghua University, Beijing, China. 

# 💻 Work Experience
- *2026 - Present*, WeChat AI, Tencent, Beijing, China.
- *2024 - 2025*, Baidu, Beijing, China. LLM post-training for ERNIE / Wenxin Yiyan (文心一言).
