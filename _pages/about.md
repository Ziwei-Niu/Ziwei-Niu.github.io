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

I am currently a Research Fellow at the Department of Biomedical Engineering, National University of Singapore (NUS), working with Prof. [Yueming Jin](https://cde.nus.edu.sg/bme/staff/jin-yueming/). I received my Ph.D. degree in Computer Science and Technology from the College of Computer Science and Technology, Zhejiang University (浙江大学计算机科学与技术学院), advised by Prof. [Lanfen Lin (林兰芬)](http://give.zju.edu.cn/en/memberHomepage/LinLanfen.html). Before that, I received my bachelor's degree from the College of Information and Computer Science, Anhui Agricultural University (安徽农业大学信息与计算机学院).

My research interests include medical image analysis, domain adaptation, domain generalization, foundation models for medical image analysis, and multi-modal learning.

To help researchers quickly start in domain generalization, we set up a [repository](https://github.com/Ziwei-Niu/Domain-generalization) for organizing papers, codes, datasets, and related resources on domain generalization. If you find it helpful, feel free to give it a star 🌟!

<!--
My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).
-->

# 🔥 News

- *2026.08*: &nbsp;🎉 I joined the National University of Singapore as a Research Fellow.
- *2026*: &nbsp;🎉 One paper is accepted by ICASSP 2026 Oral.
- *2025*: &nbsp;🎉 One paper is accepted by ACM MM 2025.
- *2025*: &nbsp;🎉 One paper is accepted by ICCV 2025.
- *2025*: &nbsp;🎉 One paper is accepted by IEEE TMI 2025.
- *2025*: &nbsp;🎉 One paper is accepted by IEEE TAC.
- *2024*: &nbsp;🎉 One paper is accepted by ICASSP 2024 Oral.
- *2024*: &nbsp;🎉 One paper is accepted by IEEE TMM.
- *2023*: &nbsp;🎉 Two papers are accepted by ACM MM 2023.
- *2023*: &nbsp;🎉 One paper is accepted by IJCAI 2023.
- *2023*: &nbsp;🎉 One paper is accepted by ICASSP 2023 Oral.
- *2022.07*: &nbsp;🎉 I released a [Domain Generalization Repository](https://github.com/Ziwei-Niu/Domain-generalization) for organizing papers, codes, datasets, and related resources. Welcome to STAR!

# 📝 Publications 

- <span style="background-color: #003366; color: white; padding: 1px 4px; font-size: 12px;">``ICASSP 2026``</span> <span style="color:red">(Oral)</span> CG-DMER: Hybrid Contrastive-Generative Framework for Disentangled Multimodal ECG Representation Learning. **Ziwei Niu**, Hao Sun, Shijie Bian, Xuhui Yang, Lanfen Lin, Yuxin Liu, Yueming Jin.

- <span style="background-color: #003366; color: white; padding: 1px 4px; font-size: 12px;">``ACM MM 2025``</span> EIR-SDG: Explore Invariant Representation for Single-source Domain Generalization in Medical Image Segmentation. **Ziwei Niu**, Shijie Bian, Zhan Wang, Yawen Chen, Yueming Jin, Lanfen Lin.

- <span style="background-color: #003366; color: white; padding: 1px 4px; font-size: 12px;">``ICCV 2025``</span> Region-aware Anchoring Mechanism for Efficient Referring Visual Grounding. Shuyi Ouyang *, **Ziwei Niu** *, Hongyi Wang, Yen-Wei Chen, Lanfen Lin.

- <span style="background-color: #003366; color: white; padding: 1px 4px; font-size: 12px;">``TMI 2025``</span> EICSeg: Universal Medical Image Segmentation via Explicit In-Context Learning. Shiao Xie, Liang Zhang, **Ziwei Niu**, Fan Ye, Qian Zhong, Dajiang Xie, Yen-Wei Chen, Lanfen Lin.

- <span style="background-color: #003366; color: white; padding: 1px 4px; font-size: 12px;">``TAC 2025``</span> Multimodal Sentiment Analysis with Mutual Information-based Disentangled Representation Learning. Hao Sun *, **Ziwei Niu** *, Hongyi Wang, Yawen Chen, Lanfen Lin.

- <span style="background-color: #003366; color: white; padding: 1px 4px; font-size: 12px;">``ICASSP 2024``</span> <span style="color:red">(Oral)</span> IRLSG: Invariant Representation Learning for Single-domain Generalization in Medical Image Segmentation. **Ziwei Niu**, Hao Sun, Shuyi Ouyang, Shiao Xie, Yen-Wei Chen, Lanfen Lin.

- <span style="background-color: #003366; color: white; padding: 1px 4px; font-size: 12px;">``TMM 2024``</span> Knowledge Distillation-based Domain-invariant Representation Learning for Domain Generalization. **Ziwei Niu**, Junkun Yuan, Xu Ma, Yingying Xu, Jing Liu, Yen-Wei Chen, Ruofeng Tong, Lanfen Lin.

- <span style="background-color: #003366; color: white; padding: 1px 4px; font-size: 12px;">``ICASSP 2023``</span> <span style="color:red">(Oral)</span> MCKD: Mutually Collaborative Knowledge Distillation for Federated Domain Adaptation and Generalization. **Ziwei Niu**, Hongyi Wang, Hao Sun, Shuyi Ouyang, Yawen Chen, Lanfen Lin.

- <span style="background-color: #003366; color: white; padding: 1px 4px; font-size: 12px;">``ACM MM 2023``</span> IS2Net: Intra-domain Semantic and Inter-domain Style Enhancement for Semi-supervised Domain Generalization. Shiao Xie *, **Ziwei Niu** *, Huimin Huang, Hao Sun, Rui Qin, Yen-Wei Chen, Lanfen Lin.

- <span style="background-color: #003366; color: white; padding: 1px 4px; font-size: 12px;">``ACM MM 2023``</span> HSVLT: Hierarchical Scale-Aware Vision-Language Transformer for Multi-Label Image Classification. Shuyi Ouyang, Hongyi Wang, **Ziwei Niu**, Zhenjia Bai, Shiao Xie, Yingying Xu, Ruofeng Tong, Yen-Wei Chen, Lanfen Lin.

- <span style="background-color: #003366; color: white; padding: 1px 4px; font-size: 12px;">``IJCAI 2023``</span> SLViT: Scale-wise Language-guided Vision Transformer for Referring Image Segmentation. Shuyi Ouyang, Hongyi Wang, Shiao Xie, **Ziwei Niu**, Ruofeng Tong, Yen-Wei Chen, Lanfen Lin.


# 🎖 Honors and Awards

- *2022, 2023, 2024, 2025* Outstanding Graduate Student Award of Zhejiang University.
- *2021.06* Provincial Outstanding Undergraduate Award.
- *2020.10* National Scholarship, the highest scholarship from the Ministry of Education of China.
- *2020.03* Provincial Hundred-excellent College Student Award.
- *2019.11* Gold Award in Anhui Province “Internet Plus” Undergraduate Innovation and Entrepreneurship Competition.
- *2019.08* First Award in the HUAWEI CUP National Undergraduate IoT Design Contest.

# 📖 Education

- *2026.08 - present*, Research Fellow, National University of Singapore, Singapore.
- *2021.09 - 2026.06*, Ph.D. in Computer Science and Technology, Zhejiang University, Hangzhou, China.
- *2024.09 - 2026.08*, Visiting Ph.D. Student, National University of Singapore, Singapore.
- *2017.09 - 2021.06*, B.Eng. in Internet of Things Engineering, Anhui Agricultural University, Hefei, China.

<!--
# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
-->
