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

# 👨🏻‍🎓 Biography
I am a Ph.D. candidate at the School of Artificial Intelligence and Data Science, University of Science and Technology of China (USTC), and a member of State Key Laboratory of Cognitive Intelligence. My supervisor is Prof. [Enhong Chen](http://staff.ustc.edu.cn/~cheneh/). Previously, I interned at _ByteDance - AI LAB_, as an algorithm intern. I received my Bachelor degree from USTC in July, 2019, and majored in Electronic Information Engineering.

Currently, I am a visiting Ph.D. student with Prof. [Xiaofang Zhou](https://sites.google.com/view/xiaofang-zhou) at The Hong Kong University of Science and Technology (HKUST).

**I am on the job market the next year!** I will graduate with my Ph.D. degree in summer 2025. I am open to faculty/postdoctoral positions or related industry roles. Please get in touch!

Here is my [Curriculum Vitae](../personal_cv/CV_YeLiu.pdf) (August 2024).

# 👨🏻‍💻 Research Interest
My research interests encompass a wide range of subjects within the ﬁelds of **Knowledge-aware Natural Language Processing (NLP)**, focusing on two main areas: (1) Knowledge Acquisition and (2) Knowledge Application. Recently, I am exploring a focused research direction of Knowledge-enhanced Large Language Models (LLMs). I have published more than 20 papers at the top international conferences/journals.

- **Knowledge Acquisition**: Acquisition of knowledge concept, knowledge relation, knowledge linking and alignment using information extraction, crowd-sourcing, and LLM In-Context Learning (ICL) techniques.
- **Knowledge Application**: Application of extracted knowledge in various NLP downstream tasks, including but not limited to: Hierarchical Text Classiﬁcation (HTC), Multimodal Summarization with Multimodal Output (MSMO), Question Answering (QA), etc.
- **Knowledge-enhanced LLMs**: Mitigate the hallucination problem and elicit complex reasoning ability of LLMs with the integration of internal/external knowledge, mainly through the approaches such as pre-training and Retrieval-Augmented Generation (RAG).


# 🔥 News
- *2024.07*: &nbsp;🎉🎉 One paper accepted to CIKM conference! 
- *2024.05*: &nbsp;🎉🎉 One paper accepted to ACL conference!

# 📝 Publications 
†: Equal Contribution

## Preprint
- **_Ye Liu_**, Jiajun Zhu, Kai Zhang, Haoyu Tang, Yanghai Zhang, Xukai Liu, Qi Liu, Enhong Chen.\
  Detect, Investigate, Judge and Determine: A Novel LLM-based Framework for Few-shot Fake News Detection.[[arxiv]](https://arxiv.org/pdf/2407.08952) [[code]](https://anonymous.4open.science/r/DAFND-CE5D).
- Haoyu Tang†, **_Ye Liu_**†, Xukai Liu, Kai Zhang, Yanghai Zhang, Qi Liu, Enhong Chen.\
  Learn while Unlearn: An Iterative Unlearning Framework for Generative Language Models. [[arxiv]](https://arxiv.org/pdf/2407.20271) [[code]](https://github.com/himalalps/ICU).
- Xukai Liu, **_Ye Liu_**, Kai Zhang, Kehang Wang, Qi Liu, Enhong Chen.\
  OneNet: A Fine-Tuning Free Framework for Few-Shot Entity Linking via Large Language Model Prompting. [[paper]](https://openreview.net/pdf?id=GCxvf6qxeW) [[code]](https://anonymous.4open.science/r/LLM4EL/)
- Aoran Gan, **_Ye Liu_**, Hongbo Gang, Kai Zhang, Qi Liu, Guoping Hu.\
  Discover rather than Memorize: A Novel Benchmark for Relational Triple Extraction. [[paper]](https://openreview.net/pdf?id=E8r0jBzfoH)
- Feng Hu, Kai Zhang, **_Ye Liu_**, Meikai Bao, Xukai Liu, Junyu Lu, Linbo Zhu, Qi Liu.\
  Learnable Relational Knowledge Distillation Through Orthogonal Projection.

## 2024
- **_Ye Liu_**, Kai Zhang*, Aoran Gan, Linan Yue, Feng Hu, Qi Liu, Enhong Chen.\
  Empowering Few-Shot Relation Extraction with The Integration of Traditional RE Methods and Large Language Models. [[arxiv]](https://arxiv.org/pdf/2407.08967) [[code]](https://github.com/liuyeah/DSARE)\
  The 29th International Conference on Database Systems for Advanced Applications (**_DASFAA_**), 2024.
- Yanghai Zhang, **_Ye Liu_**, Shiwei Wu, Kai Zhang*, Xukai Liu, Qi Liu, Enhong Chen.\
  Leveraging Entity Information for Cross-Modality Correlation Learning: The Entity-Guided Multimodal Summarization. [[paper]](https://aclanthology.org/2024.findings-acl.587.pdf) [[code]](https://github.com/ApocalypseH/EGMS)\
  Findings of the 62nd annual meeting of the Association for Computational Linguistics (**_ACL-Findings_**), 2024.
- Linan Yue, Qi Liu, **_Ye Liu_**, Weibo Gao, et al.\
  Cooperative Classification and Rationalization for Graph Generalization. [[arxiv]](https://arxiv.org/pdf/2403.06239) [[code]](https://github.com/yuelinan/Codes-of-C2R)\
  The ACM Web Conference, 2024 (**_WWW_**), 2024.
- Linan Yue, Qi Liu, Weibo Gao, **_Ye Liu_**, Kai Zhang, Yichao Du, Li Wang, et al.\
  Federated Self-Explaining GNNs with Anti-shortcut Augmentations. [[paper]](https://openreview.net/pdf?id=ZxDqSBgFSM) [[code]](https://github.com/yuelinan/Codes-of-FedGR)\
  The 41st International Conference on Machine Learning (**_ICML_**), 2024.
- Kehang Wang, **_Ye Liu_**, Kai Zhang, Qi Liu, Yankun Ren, Xinxing Yang, Longfei Li, Jun Zhou.\
  QoMRC: Query-oriented Machine Reading Comprehension Framework for Aspect Sentiment Triplet Extraction. [[paper]](../publications/QoMRC_DASFAA2024.pdf)\
  The 29th International Conference on Database Systems for Advanced Applications (**_DASFAA_**), 2024.
- Zhijun Dong, Likang Wu, Kai Zhang, **_Ye Liu_**, Yanghai Zhang, Zhi Li, Hongke Zhao and Enhong Chen.\
  FZR: Enhancing Knowledge Transfer via Shared Factors Composition in Zero-Shot Relational Learning.\
  The 33rd ACM International Conference on Information and Knowledge Management (**_CIKM_**), 2024.
- Linan Yue, Qi Liu, Yichao Du, Weibo Gao, Ye Liu, et al.\
  FedJudge: Federated Legal Large Language Model. [[arxiv]](https://arxiv.org/pdf/2309.08173) [[code]](https://github.com/yuelinan/FedJudge)\
  The 29th International Conference on Database Systems for Advanced Applications (**_DASFAA_**), 2024.

## 2023
- **_Ye Liu_**, Kai Zhang*, Zhenya Huang, Kehang Wang, Yanghai Zhang, Qi Liu, Enhong Chen*.\
  Enhancing Hierarchical Text Classification through Knowledge Graph Integration. [[paper]](https://aclanthology.org/2023.findings-acl.358.pdf) [[code]](https://github.com/liuyeah/K-HTC)\
  Findings of the 61st annual meeting of the Association for Computational Linguistics (**_ACL-Findings_**), 2023.
- **_Ye Liu_**, Han Wu, Zhenya Huang, Hao Wang, Yuting Ning, Jianhui Ma, Qi Liu, Enhong Chen*.\
  TechPat: Technical Phrase Extraction for Patent Mining. [[paper]](https://dl.acm.org/doi/pdf/10.1145/3596603) [[code]](https://github.com/liuyeah/TechPat)\
  ACM Transactions on Knowledge Discovery from Data (**_ACM TKDD_**), 2023.
- Xukai Liu, Kai Zhang*, **_Ye Liu_**, Enhong Chen, Zhenya Huang, Linan Yue, Jiaxian Yan.\
  RHGH: Relation-gated Heterogeneous Graph Network for Entity Alignment in Knowledge Graphs. [[paper]](https://aclanthology.org/2023.findings-acl.553.pdf) [[code]](https://github.com/laquabe/RGHN)\
  Findings of the 61st annual meeting of the Association for Computational Linguistics (**_ACL-Findings_**), 2023.
- Meikai Bao, Qi Liu*, Kai Zhang, **_Ye Liu_**, Linan Yue, Longfei Li, Jun Zhou.\
  Keep Skills in Mind: Understanding and Implementing Skills in Commonsense Question Answering. [[paper]](https://www.ijcai.org/proceedings/2023/0557.pdf) [[code]](https://github.com/BAOOOOOM/DSCQA)\
  The 32nd International Joint Conference on Artificial Intelligence (**_IJCAI_**), 2023.
- Kehang Wang, Qi Liu*, Kai Zhang, **_Ye Liu_**, Hanqin Tao, Zhenya Huang, Enhong Chen.\
  Class-Dynamic and Hierarchy-Constrained Network for Entity Linking. [[paper]](../publications/WangKH_DASFAA2023.pdf) [[code]](https://github.com/bigdata-ustc/CDHCN)\
  The 28th International Conference on Database Systems for Advanced Applications (**_DASFAA_**), 2023.
- Xin Jin, Qi Liu*, Linan Yue, Ye Liu, Lili Zhao, Weibo Gao, Zheng Gong, Kai Zhang, Haoyang Bi.\
  Diagnosis then Aggregation: An Adaptive Ensemble strategy for Keyphrase Extraction. [[paper]](../publications/XinJin_CICAI.pdf) [[code]](https://github.com/kingiv4/AEKE)\
  CAAI International Conference on Artificial Intelligence (**_CICAI_**), 2023. [<font color="red">(Finalist of Best Paper Award!)</font>](../publications/cicai_best_paper.pdf)

## 2022
- Huijie Liu, Han Wu, Le Zhang, Runlong Yu, **_Ye Liu_**, Chunli Liu, Minglei Li, Qi Liu, Enhong Chen.\
  A Hierarchical Interactive Multi-channel Graph Neural Network for Technological Knowledge Flow Forecasting. [[paper]](https://drive.google.com/file/d/12jCF2eYIgVhrZKBkGtjNYRH0JUhaZGkv/view)\
  Knowledge and Information Systems (**_KAIS_**), 2022.
- Guanqi Zhu, Hanqing Tao, Han Wu, Liyi Chen, **_Ye Liu_**, Qi Liu, Enhong Chen*.\
  Text Classification via Learning Semantic Dependency and Association. [[paper]](https://ieeexplore.ieee.org/abstract/document/9892656) \
  The 2022 IEEE World Congress on Computational Intelligence - IJCNN (**_IJCNN_**), 2022.

## 2021
- Yixiao Ma, Shiwei Tong, **_Ye Liu_**, Likang Wu, Qi Liu, Enhong Chen*, Wei Tong, Zi Yan.\
  Enhanced Representation Learning for Examination Papers with Hierarchical Document Structure. [[paper]](../publications/YiXiao-Ma-SIGIR21.pdf)\
  The 44th International ACM SIGIR Conference on Research and Development in Information Retrieval (**_SIGIR_**), 2021.
- Songtao Fang, Zhenya Huang*, Ming He, Shiwei Tong, Xiaoqing Huang, **_Ye Liu_**, Jie Huang, Qi Liu.\
  Guided Attention Network for Concept Extraction. [[paper]](../publications/SongtaoFang-IJCAI2021.pdf)\
  The 30th International Joint Conference on Artificial Intelligence (**_IJCAI_**), 2021.
- Huijie Liu, Han Wu, Le Zhang, Runlong Yu, **_Ye Liu_**, Chunli Liu, Qi Liu, Enhong Chen.\
  Technological Knowledge Flow Forecasting through A Hierarchical Interactive Graph Neural Network. [[paper]](https://drive.google.com/file/d/137kcXZecKWdlhB7BxaJyvACpMtzFRvPH/view)\
  IEEE International Conference on Data Mining (**_ICDM_**), 2021.
- Yuting Ning, **_Ye Liu_**, Zhenya Huang, Haoyang Bi, Qi Liu, Enhong Chen*, Dan Zhang.\
  Stable and Diverse: A Unified Approach for Computerized Adaptive Testing. [[paper]](https://ieeexplore.ieee.org/document/9754532)\
  The 7th IEEE International Conference on Cloud Computing and Intelligence Systems (**_CCIS_**), 2021.
- Lili Zhao, Linan Yue, Yanqing An, **_Ye Liu_**, Kai Zhang, Weidong He, Yanmin Chen, Qi Liu*.\
  Legal Judgment Prediction with Multiple Perspectives on Civil Cases. [[paper]](https://link.springer.com/chapter/10.1007/978-3-030-93046-2_60)\
  The 1st CAAI International Conference on Artificial Intelligence (**_CICAI_**), 2021.

## 2020
- **_Ye Liu_**, Han Wu, Zhenya Huang, Hao Wang, Jianhui Ma, Qi Liu, Enhong Chen*, Hanqing Tao and Ke Rui.\
  Technical Phrase Extraction for Patent Mining: A Multi-level Approach. [[paper]](../publications/Ye-Liu-ICDM.pdf) [[code]](https://github.com/liuyeah/UMTPE)\
  The 2020 IEEE International Conference on Data Mining (**_ICDM_**), 2020.

# 🎖 Honors and Awards
- *2023*: &nbsp;🏅 CICAI Finalist of Best Paper Award (Top-3). 
- *2019, 2020, 2022, 2023*: &nbsp;🏅 Graduate Student First-class Academic Scholarship.
- *2020*: &nbsp;🏅 Graduate Student Second-class Academic Scholarship.
- *2016*: &nbsp;🏅 <em><b><font color="red">National Scholarship</font></b></em>.

# 📖 Educations
- *2024.05 - now*, Visiting Ph.D. Student, Hong Kong University of Science and Technology (HKUST), Supervisor: Prof. [Xiaofang Zhou](https://sites.google.com/view/xiaofang-zhou). 
- *2019.09 - now*, Ph.D. Candidate, University of Science and Technology of China (USTC), Supervisor: Prof. [Enhong Chen](http://staff.ustc.edu.cn/~cheneh/).
- *2015.09 - 2019.09*, B.E., University of Science and Technology of China (USTC). 

# 💻 Internships
- *2023.02 - 2023.08*, ByteDance - AI LAB, Beijing, China.
- *2019.02 - 2019.08*, Huawei - Cloud & AI, Hangzhou, China.

# 👨🏻‍🏫 Teaching
- *COMP6110P.02*: Machine Learning and Knowledge Discovery (Fall 2021).
- *CS1001A.13*: Computer Programming A (Fall 2020).
- *011X3001*: Introduction to Data Science (Fall 2019).
- *011164.01*: Computer Programming I (Fall 2018).

# 🔖 Academic Service
- *Conference Reviewer*: ACL Rolling Review, ICLR.
- *Journal Reviewer*: IEEE TKDE, IEEE TBD.
