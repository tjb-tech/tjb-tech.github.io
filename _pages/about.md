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

I am a first-year Ph.D. student majoring in Data Science at The University of Hong Kong (HKU), supervised by Prof. [Chao Huang](https://sites.google.com/view/chaoh) and [Kao, Benjamin C.M](https://www.cs.hku.hk/index.php/people/academic-staff/kao). 

My research interest includes **Graph Neural Networks**, **Large Language Models** and **deep learning applications**. I have published some papers <a href='https://scholar.google.com.hk/citations?user=GUXIfJgAAAAJ&hl=zh-CN'><img src="https://img.shields.io/endpoint?logo=Google%20Scholar&url=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2Ftjb-tech%2Ftjb-tech.github.io@google-scholar-stats%2Fgs_data_shieldsio.json&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a> at the top international AI conferences such as KDD, SIGIR, CIKM, WWW. 

# 🔥 News

* 🎯 *2024.03*: &nbsp;🎉🎉Our **HiGPT** is accepted by **KDD'24** in the Research Track (~20% acceptance rate), **UrbanGPT** is accepted by **KDD'24** in the Applied Data Science Track (~20% acceptance rate) and **LLM4Graph** is accepted by **KDD'24** in the Lecture-Style Track Tutorial. Check out more about **HiGPT**: 🏠https://higpt-hku.github.io/, **UrbanGPT**: 🏠https://urban-gpt.github.io/ and **LLM4Graph**: 🏠https://github.com/HKUDS/Awesome-LLM4Graph-Papers. Thanks to Zhonghang, Xubin and other co-authors as well as my supervisor!

- 🎯 *2024.03*: &nbsp;🎉🎉Our **GraphGPT** is accepted by **SIGIR'24** in the Full paper track (20.1% acceptance rate). Check out more about **GraphGPT**: 🏠[https://graphgpt.github.io/](https://graphgpt.github.io/). Thanks to all my co-authors and my supervisor!
- 🎯 *2024.03*: &nbsp;🎉🎉I gave a presentation titled "*Graph Language Models*" on **24rd** **March 2024** in [Talk on MLLM](https://www.mllm-ai.com/home) to introduce our **GraphGPT**, **HiGPT** and **UrbanGPT**. Please check out this **[[video](https://www.youtube.com/watch?v=AIEoaPkm-XI)]** ! 
- 🎯 *2024.02*: &nbsp;🎉🎉 We release our **Heterogeneous Graph Language Model** - **HiGPT** with pre-print [paper](https://arxiv.org/abs/2402.16024), [source code](https://github.com/HKUDS/HiGPT), [model](https://huggingface.co/Jiabin99/HiGPT). Goodbye, homogeneous graphs! Hi, heterogeneous graph!
- 🎯 *2023.10*: &nbsp;🎉🎉 We release our **Graph Large Language Models** - **GraphGPT** with pre-print [paper](https://arxiv.org/abs/2310.13023), [source code](https://github.com/HKUDS/GraphGPT), [model](https://huggingface.co/Jiabin99/GraphGPT-7B-mix-all) and [data](https://huggingface.co/datasets/Jiabin99/Arxiv-PubMed-mix-NC-LP). Let's step to **Graph Learning in the era of LLM**!
- 🎯 *2024.03*: &nbsp;🎉🎉 We release our **Spatio-Temporal Large Language Models** - **UrbanGPT** with pre-print [paper](https://arxiv.org/abs/2403.00813), [source code](https://github.com/HKUDS/UrbanGPT), [model](https://huggingface.co/datasets/bjdwh/checkpoints) and [data](https://huggingface.co/datasets/bjdwh/ST_data_urbangpt). Keep going towards smart city in the era of LLMs!
- *2024.02*: &nbsp;🎉🎉 Our paper **PromptMM** is accepted by **WWW'24**! Thanks to Wei Wei and other co-authors!
- *2023.10*: &nbsp;🎉🎉 Our paper **LLMRec** is accepted by **WSDM'24**! Thanks to Wei Wei and other co-authors!
- *2023.08*: &nbsp;🎉🎉 Two full papers about spatio-temporal data mining are accepted by **CIKM'23**. Thanks to all my co-authors and my supervisor!

<details>
<summary> <b>More News</b> </summary>
  <ul>
  <li><i>2023.06</i>: &nbsp;🎉🎉 I graduated from SWJTU. Nice memories with all my friends, teachers and family!</li>
  <li><i>2022.11</i>: &nbsp;🎉🎉 I am honored with <i>Cao Jianyou Student Award</i> <b>2022</b> (Selected from eight universities, including Southwest Jiaotong University, Tongji University, Central South University, etc. ).</li>
  <li><i>2022.11</i>: &nbsp;🎉🎉 I am nominated for <i>National Scholarship for Encouragement</i> and <i>Provincial Outstanding Graduates</i>.</li>
</ul>
</details>

# 📝 Publications 

$^{\dagger}$ indicates corresponding author, $^{*}$ indicates equal contribution

#### Survey

<img src='https://img.shields.io/badge/KDD2024[Tutorial+Survey]-orange' />[A Survey of Large Language Models for Graphs](https://arxiv.org/abs/2405.08011), **[[code](https://github.com/HKUDS/Awesome-LLM4Graph-Papers)]** <img src='https://img.shields.io/github/stars/hkuds/Awesome-LLM4Graph-Papers?color=green&style=social' />

Xubin Ren, **Jiabin Tang**, Dawei Yin, Nitesh Chawla, Chao Huang$^{\dagger}$

* in Proc. of ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD), 2024.

#### Tutorials

<img src='https://img.shields.io/badge/WWW2024[Tutorial]-orange' />&<img src='https://img.shields.io/badge/KDD2024[Tutorial+Survey]-orange' />[Large Language Models for Graphs: Progresses and Directions](https://dl.acm.org/doi/abs/10.1145/3589335.3641251), **[[code](https://github.com/HKUDS/Awesome-LLM4Graph-Papers)]**, **[[project](https://llm4graph-tutorial.github.io/)]** <img src='https://img.shields.io/github/stars/hkuds/Awesome-LLM4Graph-Papers?color=green&style=social' />

Chao Huang$^{\dagger}$, Xubin Ren, **Jiabin Tang**, Dawei Yin, Nitesh Chawla

* in Proc. of The Web Conference (WWW), 2024 and ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD), 2024.

#### Conference and Journal Publications

🎯<img src='https://img.shields.io/badge/SIGIR2024-orange' />[GraphGPT: Graph Instruction Tuning for Large Language Models](https://arxiv.org/abs/2310.13023), **[[code](https://github.com/HKUDS/GraphGPT)]**, **[[project](https://graphgpt.github.io/)]**, **[[Bilibili](https://www.bilibili.com/video/BV1YQ4y1E7jW/?spm_id_from=333.999.0.0&vd_source=e4217e0b912c93c99f59f1489308a356)]**, **[[Youtube](https://www.youtube.com/watch?v=AIEoaPkm-XI)]** <img src='https://img.shields.io/github/stars/hkuds/graphgpt?color=green&style=social' />&nbsp;

**Jiabin Tang**, Yuhao Yang, Wei Wei, Lei Shi, Lixin Su, Suqi Cheng, Dawei Yin, Chao Huang$^{\dagger}$

- in Proc. of Special Interest Group on Information Retrieval (SIGIR), 2024.

🌟 <font color=#008000>**(Top-2 Most Cited Paper: 2 / 159 Accepted Papers)**</font> 🌟

🎯<img src='https://img.shields.io/badge/KDD2024-orange' />[HiGPT: Heterogeneous Graph Language Model](https://arxiv.org/abs/2402.16024), **[[code](https://github.com/HKUDS/HiGPT)]**, **[[project](https://higpt-hku.github.io/)]** <img src='https://img.shields.io/github/stars/hkuds/higpt?color=green&style=social' />&nbsp;

**Jiabin Tang**, Yuhao Yang, Wei Wei, Lei Shi, Long Xia, Dawei Yin, Chao Huang$^{\dagger}$

- in Proc. of ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD), 2024.

🎯<img src='https://img.shields.io/badge/KDD2024-orange' />[UrbanGPT: Spatio-Temporal Large Language Models](https://arxiv.org/abs/2403.00813), **[[code](https://github.com/HKUDS/UrbanGPT)]**, **[[project](https://urban-gpt.github.io/)]**, **[[video](https://www.youtube.com/watch?v=4BIbQt-EIAM)]** <img src='https://img.shields.io/github/stars/hkuds/urbangpt?color=green&style=social' />

Zhonghang Li, Lianghao Xia, **Jiabin Tang**, Yong Xu, Lei Shi, Long Xia, Dawei Yin, Chao Huang$^{\dagger}$

- in Proc. of ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD), 2024.

<img src='https://img.shields.io/badge/WWW2024-orange' />[PromptMM: Multi-Modal Knowledge Distillation for Recommendation with Prompt-Tuning](https://arxiv.org/abs/2402.17188), **[[code](https://github.com/HKUDS/LLMRec)]** 

Wei Wei, **Jiabin Tang**, Yangqin Jiang, Lianghao Xia, Chao Huang$^{\dagger}$

- in Proc. of The Web Conference (WWW), 2024.

<img src='https://img.shields.io/badge/WSDM2024-orange' />[LLMRec: Large Language Models with Graph Augmentation for Recommendation](https://arxiv.org/abs/2311.00423), **[[code](https://github.com/HKUDS/LLMRec)]**, **[[project](https://llmrec.github.io/)]** <img src='https://img.shields.io/github/stars/hkuds/llmrec?color=green&style=social' />

Wei Wei, Xubin Ren, **Jiabin Tang**, Qinyong Wang, Lixin Su, Suqi Cheng, junfeng wang, Dawei Yin, Chao Huang$^{\dagger}$

- in Proc. of The ACM International Conference on Web Search and Data Mining (WSDM), 2024. (*Oral Presentation*)

🌟 <font color=#008000>**(Top-1 Most Cited Paper: 1 / 112 Accepted Papers)**</font> 🌟

<img src='https://img.shields.io/badge/CIKM2023-orange' />[Spatio-Temporal Meta Contrastive Learning](https://dl.acm.org/doi/abs/10.1145/3583780.3615065), **[[code](https://github.com/HKUDS/CL4ST)]** <img src='https://img.shields.io/github/stars/hkuds/cl4st?color=green&style=social' />&nbsp;

**Jiabin Tang**, Lianghao Xia, Jie Hu, Chao Huang$^{\dagger}$

- in Proc. of The ACM International Conference on Information and Knowledge Management (CIKM), 2023.

<img src='https://img.shields.io/badge/CIKM2023-orange' />[Explainable Spatio-Temporal Graph Neural Networks](https://dl.acm.org/doi/abs/10.1145/3583780.3614871), **[[code](https://github.com/HKUDS/STExplainer)]** <img src='https://img.shields.io/github/stars/hkuds/stexplainer?color=green&style=social' />&nbsp;

**Jiabin Tang**, Lianghao Xia, Chao Huang$^{\dagger}$

- in Proc. of The ACM International Conference on Information and Knowledge Management (CIKM), 2023.

<img src='https://img.shields.io/badge/IJCNN2022-orange' />[Spatio-Temporal Latent Graph Structure Learning for Traffic Forecasting](https://ieeexplore.ieee.org/document/9892191)

**Jiabin Tang**, Tang Qian, Shijing Liu, Shengdong Du$^{\dagger}$, Jie Hu, Tianrui Li

- in Proc. of The International Joint Conference on Neural Networks (IJCNN), 2022. (*Oral Presentation*)

# 🎖 Honors and Awards
* Scholarship(Selected)
  * National Scholarship (Two Times): **2020** and **2021**
  * Cao Jianyou Student Award: **2022**
  * National Scholarship for Encouragement: **2022**
  * Provincial Outstanding Graduates: **2023**



# 📖 Educations
- *2023.09 - 2027.06 (expected)*, Ph.D. in Data Science, The University of Hong Kong (HKU)

- *2019.09 - 2023.06*, B. Eng in Software Engineering, Southwest Jiaotong University (SWJTU)



# 💬 Invited Talks

- *2024.03*: Giving a presentation titled "*Graph Language Models*" on **24rd** **March 2024** in [Talk on MLLM](https://www.mllm-ai.com/home) to introduce our **GraphGPT**, **HiGPT** and **UrbanGPT**. [video](https://www.youtube.com/watch?v=AIEoaPkm-XI)
- *2023.12*, Sharing our '*GraphGPT: Graph Instruction Tuning for Large Language Models*' online in the Bilibili Channel **AITIME论道**, [video](https://www.bilibili.com/video/BV1YQ4y1E7jW/?spm_id_from=333.999.0.0&vd_source=e4217e0b912c93c99f59f1489308a356)
- *2023.10*, Oral presentation at CIKM 2023 about our paper: '*Spatio-Temporal Meta Contrastive Learning*' and '*Explainable Spatio-Temporal Graph Neural Networks*'. 
- *2022.08*, Oral presentation at IJCNN 2022 about our paper: '*Spatio-Temporal Latent Graph Structure Learning for Traffic Forecasting*'. 



# 🧑‍💻 Service

- As an organizer of [Talk on MLLM](https://www.mllm-ai.com/home) platform. 
- Conference Reviewers: 
  - KDD, CIKM: 2024
- Journal Reviewers: 
  - TNNLS
  

# 💻 Internships
- Research Intern
  - Company/Institution: Search Science Team, Baidu Inc.
  - Advisor: Dr. Lei Shi & Dr. Lixin Su
  - Employment period: From 06/2023 to the present
- Research Intern
  - Company/Institution: Data Intelligence Lab, The University of Hong Kong
  - Advisor: Prof. Chao Huang
  - Employment period: From 01/2022 to the present
- Research Intern
  - Company/Institution: CCIT Laboratory, Southwest Jiaotong University 
  - Advisor: Prof. Tianrui Li & Prof. Shengdong Du
  - Employment period: From 09/2021 to 04/2022