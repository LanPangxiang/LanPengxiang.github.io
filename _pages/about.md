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

Hello! I am **Pengxiang Lan (兰鹏翔)**, a Ph.D. student in Computer Technology at the **School of Computer Science and Engineering, Northeastern University**, Shenyang, China. I am advised by **Prof. Hai Zhao** and **Prof. Guibing Guo**. Before joining Northeastern University, I received my M.S. degree in Computer Application Technology from Chongqing University of Technology and my B.E. degree in Software Engineering from Hefei Normal University.

My research interests include **recommender systems, large language models (LLMs), parameter-efficient fine-tuning (PEFT), data mining, and knowledge editing**. In particular, I am interested in next point-of-interest (POI) recommendation, user mobility modeling, LLM-enhanced recommendation, efficient adaptation of large language models, and reliable knowledge updating.

I am always happy to discuss research ideas and potential collaborations. Please feel free to contact me via email.

# 🔥 News

- *2026*: 🎉 Our paper **Multi-Perspective Driven Expected Location Preferences for Next POI Recommendations** was accepted by **SIGIR 2026** as an **Oral Paper**.
- *2026*: 🎉 Our paper **LLM-Driven Location Completion and Test-Time Training for Next Location Prediction** was published in **Expert Systems with Applications (ESWA)**.
- *2026*: 🎉 Our paper **LLM-Driven Multi-Perspective Location Completion for Next Location Prediction** was accepted by **Findings of ACL 2026**.
- *2026.02*: 🎉 Our patent on **LLM-driven multi-perspective POI completion** was granted.
- *2025*: 🎉 Our paper **EPT: Efficient Prompt Tuning by Multi-Space Projection and Prompt Fusion** was accepted by **AAAI 2025** as an **Oral Paper**.
- *2025*: 🎉 Our paper **Efficient and Effective Prompt Tuning via Prompt Decomposition and Compressed Outer Product** was accepted by **NAACL 2025** as an **Oral Paper**.
- *2025*: 🏆 I was selected as an **Outstanding Graduate Student of Northeastern University**.

# 📝 Selected Publications

**Pengxiang Lan** is highlighted in bold. For a more complete publication list, please visit my [DBLP](https://dblp.org/pid/329/5834.html) or [Google Scholar](https://scholar.google.com/citations?user=ULw0mF0AAAAJ).

### First-author / Major-contribution Papers

- **[SIGIR 2026, Oral]** [Multi-Perspective Driven Expected Location Preferences for Next POI Recommendations](https://doi.org/10.1145/3805712.3809685)  
  **Pengxiang Lan**, Enneng Yang, Yuliang Liang, Jianzhe Zhao, Guibing Guo, Hai Zhao.

- **[ESWA 2026]** LLM-Driven Location Completion and Test-Time Training for Next Location Prediction.  
  **Pengxiang Lan**, Enneng Yang, Yuliang Liang, Jianzhe Zhao, Guibing Guo, Hai Zhao.

- **[Findings of ACL 2026]** [LLM-Driven Multi-Perspective Location Completion for Next Location Prediction](https://aclanthology.org/2026.findings-acl.267/)  
  **Pengxiang Lan**, Enneng Yang, Yuliang Liang, Jianzhe Zhao, Linying Jiang, Guibing Guo.

- **[AAAI 2025, Oral]** [EPT: Efficient Prompt Tuning by Multi-Space Projection and Prompt Fusion](https://ojs.aaai.org/index.php/AAAI/article/view/34614)  
  **Pengxiang Lan**, Enneng Yang, Yuting Liu, Guibing Guo, Jianzhe Zhao, Xingwei Wang.

- **[NAACL 2025, Oral]** [Efficient and Effective Prompt Tuning via Prompt Decomposition and Compressed Outer Product](https://aclanthology.org/2025.naacl-long.225/)  
  **Pengxiang Lan**, Haoyu Xu, Enneng Yang, Yuliang Liang, Guibing Guo, Jianzhe Zhao, Xingwei Wang.

- **[DASFAA 2023, Oral]** [Spatio-Temporal Position-Extended and Gated-Deep Network for Next POI Recommendation](https://doi.org/10.1007/978-3-031-30672-3_34)  
  **Pengxiang Lan**, Yihao Zhang, Haoran Xiang, Yuhao Wang, Wei Zhou.

- **[ICWS 2022, Oral]** [Spatio-Temporal Mogrifier LSTM and Attention Network for Next POI Recommendation](https://doi.org/10.1109/ICWS55610.2022.00019)  
  Yihao Zhang, **Pengxiang Lan**, Yuhao Wang, Haoran Xiang.

### Co-authored Papers

- **[ACL 2025]** [Knowledge Decoupling via Orthogonal Projection for Lifelong Editing of Large Language Models](https://aclanthology.org/2025.acl-long.646/)  
  Haoyu Xu, **Pengxiang Lan**, Enneng Yang, Guibing Guo, Jianzhe Zhao, Linying Jiang, Xingwei Wang.

- **[WWW 2025]** [Graph Representation Learning via Causal Diffusion for Out-of-Distribution Recommendation](https://arxiv.org/abs/2408.00490)  
  Chu Zhao, Enneng Yang, Yuliang Liang, **Pengxiang Lan**, Yuting Liu, Jianzhe Zhao, Guibing Guo, Xingwei Wang.

# 📖 Education

- **2023.09 - 2027.06 (Expected)**, Ph.D. in Computer Technology, School of Computer Science and Engineering, **Northeastern University**, Shenyang, China.  
  Advisors: Prof. Hai Zhao and Prof. Guibing Guo.

- **2020.09 - 2023.07**, M.S. in Computer Application Technology, Liangjiang International College / School of Artificial Intelligence, **Chongqing University of Technology**, Chongqing, China.  
  Advisor: Prof. Yihao Zhang.

- **2016.09 - 2020.07**, B.E. in Software Engineering, School of Computer Science, **Hefei Normal University**, Hefei, China.

# 🚀 Research Experience & Projects

### Personalized and Efficient Fine-Tuning for On-Device Large Language Models
**Project Lead** · *2024.07 - 2025.07*

- Led the overall technical roadmap and research development for efficient personalization of on-device LLMs.
- Developed parameter-efficient prompt tuning techniques combining model quantization and truncated singular value decomposition.
- Investigated LLM-based heterogeneous user data modeling and an edge-cloud collaborative framework integrating Byzantine-robust federated learning, two-stage client filtering, and adaptive differential privacy.

### Next POI Recommendation with Multi-Context Information
**Project Lead** · *2021.05 - 2022.04*

- Designed next-POI recommendation models that jointly capture long-term and short-term user preferences using spatio-temporal contexts.
- Combined Mogrifier LSTM, multi-head self-attention, location-salient modeling, temporal weighting, and geographical non-local networks to better model dynamic mobility preferences.

# 🧩 Industry Experience

- **2022.05 - 2022.07**, Recommendation Algorithm Intern, **NetEase Cloud Music**, Hangzhou, China.

# 📜 Patents

- **Pengxiang Lan**, Guibing Guo. *LLM-Driven Multi-Perspective POI Completion Method and System*. Granted Patent **CN121278193B**, 2026.02.10.
- **Pengxiang Lan**, Guibing Guo. *Multi-Factor Driven Ideal Location Preference Method for POI Recommendation*. Granted Patent **CN120632180B**, 2025.11.04.
- Yihao Zhang, **Pengxiang Lan**. *Next POI Recommendation Method Based on Improved LSTM and Location Jump*. Granted Patent **CN114896481B**, 2024.11.26.

# 💻 Academic Service

### Conference Reviewers

- **NeurIPS 2026**
- **SIGIR 2026**, **SIGIR 2025**
- **AAAI 2026**
- **ACL 2026**
- **ECAI 2025**

### Journal Reviewers

- **IEEE Transactions on Computational Social Systems (TCSS)**, 2026
- **ACM Transactions on Knowledge Discovery from Data (TKDD)**, 2026

# 🎖 Honors and Awards

- *2025 - 2026*: Outstanding Graduate Student, **Northeastern University**.
- *2022 - 2023*: Outstanding Graduate Student, **Chongqing University of Technology**.
- *2021 - 2022*: First-Class Academic Scholarship, **Chongqing University of Technology**.
- *2019 - 2020*: Outstanding Graduate of **Anhui Province**.
- *2018 - 2019*: National Encouragement Scholarship.
- *2016 - 2017*: National Encouragement Scholarship.

# 🔬 Research Interests

- Recommender Systems and Next POI Recommendation
- Large Language Models for Recommendation
- Parameter-Efficient Fine-Tuning (PEFT)
- Knowledge Editing and Lifelong Model Updating
- Data Mining and User Behavior Modeling
