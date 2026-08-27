---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<span class='anchor' id='about-me'></span>

Hello! I am **Pengxiang Lan (兰鹏翔)**, a Ph.D. student in Computer Technology at the **School of Computer Science and Engineering, Northeastern University**, Shenyang, China. I am advised by **Prof. Hai Zhao** and **Prof. Guibing Guo**.

My research interests lie at the intersection of **recommender systems, large language models, and spatio-temporal intelligence**. In particular, I work on **next POI / next location recommendation, parameter-efficient fine-tuning (PEFT), knowledge editing, diffusion-based recommendation, and test-time adaptation**. My recent research explores how LLMs and generative models can better understand user mobility, recover incomplete behavioral signals, and model dynamic preferences under distribution shifts.

<div style="margin: 10px 0 18px 0; line-height: 2.0;">
<a href="https://scholar.google.com/citations?user=ULw0mF0AAAAJ" target="_blank"><img src="https://img.shields.io/badge/Google%20Scholar-Profile-4285F4?logo=googlescholar&logoColor=white" alt="Google Scholar"></a>
<a href="https://dblp.org/pid/329/5834.html" target="_blank"><img src="https://img.shields.io/badge/DBLP-Profile-004F9F" alt="DBLP"></a>
<a href="https://github.com/LanPangxiang" target="_blank"><img src="https://img.shields.io/badge/GitHub-LanPangxiang-181717?logo=github&logoColor=white" alt="GitHub"></a>
<a href="mailto:pengxianglan@stumail.neu.edu.cn"><img src="https://img.shields.io/badge/Email-Contact-EA4335?logo=gmail&logoColor=white" alt="Email"></a>
</div>

I am always happy to discuss research ideas and potential collaborations. Please feel free to contact me by email.

# 🔥 News

- *2026.08*: 🎉 Our work on **LLM-Driven Location Completion and Test-Time Training for Next Location Prediction**  was accepted by **ESWA 2026**.
- *2025–2026*: 🏆 Awarded **Outstanding Graduate Student of Northeastern University**.
- *2026.04*: 🎉 Our paper **LLM-Driven Multi-Perspective Location Completion for Next Location Prediction** was accepted by **Findings of ACL 2026**.
- *2026.04*: 🎉 Our paper **Multi-Perspective Driven Expected Location Preferences for Next POI Recommendations** was accepted by **SIGIR 2026** (**Oral / Full Paper**).
- *2025.05*: 🎉 Our lifelong knowledge editing work **Knowledge Decoupling via Orthogonal Projection for Lifelong Editing of Large Language Models.** was accepted by **ACL 2025**.
- *2025.04*: 🎉 Our paper **Efficient and Effective Prompt Tuning via Prompt Decomposition and Compressed Outer Product.** was published at **NAACL 2025** (**Oral**).
- *2025.04*: 🎉 Our OOD recommendation work **Graph Representation Learning via Causal Diffusion for Out-of-Distribution Recommendation.** was published at **WWW 2025**.
- *2025.02*: 🎉 Our paper **EPT: Efficient Prompt Tuning by Multi-Space Projection and Prompt Fusion.**  was published at **AAAI 2025** (**Oral**).

# 📝 Publications

Selected first-author and major-contribution publications are listed first.

### Selected First-Author Publications

<div class='paper-box'><div class='paper-box-image'><div>
<div class="badge">SIGIR 2026</div>
<div style="height:170px; display:flex; flex-direction:column; justify-content:center; align-items:center; text-align:center; background:linear-gradient(135deg,#eef4ff,#dbe8ff); border-radius:4px; padding:18px; box-sizing:border-box;">
<div style="font-size:30px; font-weight:700; letter-spacing:1px;">MPDC</div>
<div style="font-size:13px; margin-top:8px;">Expected Location Preference<br/>for Next POI Recommendation</div>
</div>
</div></div>
<div class='paper-box-text' markdown="1">

**Multi-Perspective Driven Expected Location Preferences for Next POI Recommendations**  
**Pengxiang Lan**, Enneng Yang, Yuliang Liang, Jianzhe Zhao, Guibing Guo, Hai Zhao  
*The 49th International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR 2026), pp. 869–880.* **Oral / Full Paper**  
[[DOI]](https://doi.org/10.1145/3805712.3809685) [[SIGIR]](https://sigir2026.org/en-AU/pages/program/accepted-papers) [[Code]](https://github.com/LanPangxiang/LaMDA2026)

We model authentic user mobility preferences from both behavioral and spatial perspectives, and further infer latent expected location preferences via diffusion-based contrastive learning.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div>
<div class="badge">ACL Findings 2026</div>
<div style="height:170px; display:flex; flex-direction:column; justify-content:center; align-items:center; text-align:center; background:linear-gradient(135deg,#f3f1ff,#e7e2ff); border-radius:4px; padding:18px; box-sizing:border-box;">
<div style="font-size:30px; font-weight:700; letter-spacing:1px;">LaMDA</div>
<div style="font-size:13px; margin-top:8px;">LLM-Driven Multi-Perspective<br/>Location Completion</div>
</div>
</div></div>
<div class='paper-box-text' markdown="1">

**LLM-Driven Multi-Perspective Location Completion for Next Location Prediction**  
**Pengxiang Lan**, Enneng Yang, Yuliang Liang, Jianzhe Zhao, Linying Jiang, Guibing Guo  
*Findings of the Association for Computational Linguistics: ACL 2026, pp. 5406–5428.*  
[[Paper]](https://aclanthology.org/2026.findings-acl.267/) [[PDF]](https://aclanthology.org/2026.findings-acl.267.pdf) [[DOI]](https://doi.org/10.18653/v1/2026.findings-acl.267)

We introduce an LLM-driven multi-perspective data augmentation framework that converts coordinates into textual geographic descriptions and uses micro- and macro-level agents to complete incomplete mobility trajectories.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div>
<div class="badge">ESWA 2026</div>
<div style="height:170px; display:flex; flex-direction:column; justify-content:center; align-items:center; text-align:center; background:linear-gradient(135deg,#edf8f3,#dcefe7); border-radius:4px; padding:18px; box-sizing:border-box;">
<div style="font-size:30px; font-weight:700; letter-spacing:1px;">LCT³</div>
<div style="font-size:13px; margin-top:8px;">Location Completion +<br/>Test-Time Training</div>
</div>
</div></div>
<div class='paper-box-text' markdown="1">

**LLM-Driven Location Completion and Test-Time Training for Next Location Prediction**  
**Pengxiang Lan**, Enneng Yang, Yuliang Liang, Jianzhe Zhao, Guibing Guo, Hai Zhao  
*Expert Systems with Applications (ESWA), 2026.*  

This work extends LLM-based location completion with collaborative test-time training to improve robustness under incomplete check-in records and distribution shifts.
</div>
</div>

- **[AAAI 2025, Oral]** **EPT: Efficient Prompt Tuning by Multi-Space Projection and Prompt Fusion.**  
  **Pengxiang Lan**, Enneng Yang, Yuting Liu, Guibing Guo, Jianzhe Zhao, Xingwei Wang.  
  [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/34614) [[DOI]](https://doi.org/10.1609/aaai.v39i23.34614) [[arXiv]](https://arxiv.org/abs/2405.11464)

- **[NAACL 2025, Oral]** **Efficient and Effective Prompt Tuning via Prompt Decomposition and Compressed Outer Product.**  
  **Pengxiang Lan**, Haoyu Xu, Enneng Yang, Yuliang Liang, Guibing Guo, Jianzhe Zhao, Xingwei Wang.  
  [[Paper]](https://aclanthology.org/2025.naacl-long.225/) [[PDF]](https://aclanthology.org/2025.naacl-long.225.pdf) [[arXiv]](https://arxiv.org/abs/2502.12200)

- **[DASFAA 2023, Oral]** **Spatio-Temporal Position-Extended and Gated-Deep Network for Next POI Recommendation.**  
  **Pengxiang Lan**, Yihao Zhang, Haoran Xiang, Yuhao Wang, Wei Zhou.  
  [[DOI]](https://doi.org/10.1007/978-3-031-30672-3_34)

- **[ICWS 2022, Oral]** **Spatio-Temporal Mogrifier LSTM and Attention Network for Next POI Recommendation.**  
  Yihao Zhang, **Pengxiang Lan**, Yuhao Wang, Haoran Xiang.  
  [[DOI]](https://doi.org/10.1109/ICWS55610.2022.00019)

### Other Publications

- **[ACL 2025]** **Knowledge Decoupling via Orthogonal Projection for Lifelong Editing of Large Language Models.**  
  Haoyu Xu, **Pengxiang Lan**, Enneng Yang, Guibing Guo, Jianzhe Zhao, Linying Jiang, Xingwei Wang.  
  [[Paper]](https://aclanthology.org/2025.acl-long.646/) [[PDF]](https://aclanthology.org/2025.acl-long.646.pdf) [[DOI]](https://doi.org/10.18653/v1/2025.acl-long.646)

- **[WWW 2025]** **Graph Representation Learning via Causal Diffusion for Out-of-Distribution Recommendation.**  
  Chu Zhao, Enneng Yang, Yuliang Liang, **Pengxiang Lan**, Yuting Liu, Jianzhe Zhao, Guibing Guo, Xingwei Wang.  
  [[DOI]](https://doi.org/10.1145/3696410.3714849) [[arXiv]](https://arxiv.org/abs/2408.00490)

# 🔬 Research Interests

- **Next POI / Next Location Recommendation** — user mobility modeling, incomplete check-in recovery, spatio-temporal preference learning.
- **Large Language Models for Recommendation** — LLM agents, semantic spatial reasoning, personalized behavior modeling.
- **Parameter-Efficient Fine-Tuning** — prompt tuning, low-rank parameterization, efficient adaptation of large models.
- **Knowledge Editing** — lifelong editing, interference mitigation, continual knowledge updates.
- **Generative Recommendation & Test-Time Adaptation** — diffusion models, deterministic preference evolution, OOD robustness.

# 📖 Education

- **2023.09 – Present**, Ph.D. in Computer Technology, **Northeastern University**, School of Computer Science and Engineering, Shenyang, China.  
  Advisors: Prof. Hai Zhao and Prof. Guibing Guo.
- **2020.09 – 2023.07**, M.S. in Computer Application Technology, **Chongqing University of Technology**, Liangjiang Artificial Intelligence College, Chongqing, China.  
  Advisor: Assoc. Prof. Yihao Zhang.
- **2016.09 – 2020.07**, B.E. in Software Engineering, **Hefei Normal University**, School of Computer Science, Hefei, China.

# 🚀 Research & Project Experience

### Personalized and Efficient Fine-Tuning for On-Device Large Language Models
**Project Lead** · *2024.07 – 2025.07*

Led the overall technical roadmap and R&D execution for efficient personalization of on-device LLMs. Designed parameter-efficient prompt tuning methods combining model quantization and truncated singular value decomposition, developed LLM-based modeling for heterogeneous user data, and explored robust federated learning with client filtering and adaptive differential privacy to balance personalization, generalization, computational efficiency, and privacy.

### Multi-Context Next POI Recommendation
**Project Lead** · *2021.05 – 2022.04*

Led the design of next-POI recommendation models integrating multi-source spatio-temporal context. Combined Mogrifier LSTM and multi-head self-attention for long- and short-term preference modeling, introduced location-salient and time-weighting mechanisms to reduce non-subjective visit noise, and developed geographic non-local modeling for spatial dependency learning.

# 🏢 Industry Experience

- **2022.05 – 2022.07**, Recommendation Algorithm Intern, **NetEase Cloud Music**, Hangzhou, China.

# 📜 Patents

- **Pengxiang Lan**, Guibing Guo. *LLM-driven multi-perspective POI completion method and system.* Granted patent **CN121278193B**, Feb. 10, 2026.
- **Pengxiang Lan**, Guibing Guo. *Multi-factor-driven expected location preference modeling for POI recommendation.* Granted patent **CN120632180B**, Nov. 4, 2025.
- Yihao Zhang, **Pengxiang Lan**. *Next POI recommendation method based on improved LSTM and location jumping.* Granted patent **CN114896481B**, Nov. 26, 2024.

# 💻 Academic Service

### Conference Reviewer

- **NeurIPS 2026**
- **SIGIR 2026**, **SIGIR 2025**
- **AAAI 2026**
- **ACL 2026**
- **ECAI 2025**

### Journal Reviewer

- **IEEE Transactions on Computational Social Systems (TCSS)**, 2026
- **ACM Transactions on Knowledge Discovery from Data (TKDD)**, 2026

# 🎖 Honors and Awards

- **2025–2026**, Outstanding Graduate Student, Northeastern University
- **2022–2023**, Outstanding Graduate Student, Chongqing University of Technology
- **2021–2022**, First-Class Academic Scholarship, Chongqing University of Technology
- **2019–2020**, Outstanding Graduate of Anhui Province
- **2018–2019**, National Encouragement Scholarship
- **2016–2017**, National Encouragement Scholarship
