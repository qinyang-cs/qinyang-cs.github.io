---
permalink: /
title: "" 
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

My name is Yang Qin (秦阳). I'm a Ph.D. candidate (since 2021) at the College of Computer Science, Sichuan University, fortunately advised by Prof. [Dezhong Peng](https://cs.scu.edu.cn/info/1182/7307.htm) and Prof. [Peng Hu](https://penghu-cs.github.io/). 

My research interests mainly focus on multimodal learning and [noisy correspondence](https://github.com/QinYang79/Noisy-Correspondence-Summary) (NC). Recently, I've been conducting research related to ***LLMs***.

- Multimodal Learning: Multimodal Fusion & Cross-modal Learning
- Robust Machine Learning: Noisy Correspondence & Label in Multimodal Learning
- Large Language Models: [Code LLMs  & Application of MLLMs/LLMs](https://qinyang-cs.github.io/projects/LLMs).
- [**This**](https://docs.google.com/document/d/16XxH3dl3Oq7t8mDBrEaAHKykmLstVLi-MbfouroMYvY/edit?usp=sharing) is a Chinese brief to help MT recruit Research Interns (RI) about LLMs. If you are interested, please get in touch with me.

# 🔥 News

- *2025.2.27*, one paper about LLM was accepted by CVPR 2025 (CCF-A). Thanks to all coauthors! 🎉 
- *2025.1.23*, one paper about LLM was accepted by ICLR 2025. Thanks to all coauthors! 🎉 
- *2025.1.19*, one paper was accepted by TMM (中科院1区). Congrats to Yanglin and coauthors! 🎉
- *2025.1.16*, one paper was accepted by TIFS (中科院1区, CCF-A). Congrats to Yongxiang and coauthors! 🎉
- *2024.12.10*, one paper was accepted by AAAI 2025 (CCF-A). Congrats to Ruitao and coauthors! 🎉
- *2024.10.28*, one paper was accepted by TMM (中科院1区). Thanks to all coauthors! 🎉
- *2024.7.16*, one paper was accepted by ACM MM 2024 (CCF-A). Congrats to Longan (Undergrad) and coauthors! 🎉
- *2024.6.26*, one paper was accepted by TIP  (中科院1区, CCF-A). Congrats to Yongxiang and coauthors! 🎉
- *2024.6.23*, one paper was accepted by TKDE (中科院1区, CCF-A). Congrats to Yuan and coauthors! 🎉
- *2024.4.20*, one paper was accepted by TMM (中科院1区). Congrats to Yuan and the coauthors! 🎉
- *2024.2.27*, one paper was accepted by CVPR 2024 (CCF-A). Thanks to all coauthors! 🎉 
- *2023.9.22*, one paper was accepted by NeurIPS 2023 (CCF-A). Thanks to all coauthors! 🎉 
- *2022.6.30*, one paper was accepted by ACM MM 2022 (CCF-A). Thanks to all coauthors! 🎉


# 📝 Publications (selected)
- <font color="blue">[*CVPR'25*]</font> **Yang Qin**, Chao Chen, Zhihang Fu, Dezhong Peng, Xi Peng, Peng Hu#, [Human-centered Interactive Learning via MLLMs for Text-to-Image Person Re-identification](https://github.com/QinYang79/ICL/blob/main/ICL_paper.pdf), IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2025. [code](https://github.com/QinYang79/ICL)
- <font color="blue">[*ICLR'25*]</font> **Yang Qin**, Chao Chen, Zhihang Fu, Ze Chen, Dezhong Peng#, Peng Hu#, Jieping Ye, [ROUTE: Robust Multitask Tuning and Collaboration for Text-to-SQL](https://openreview.net/pdf?id=BAglD6NGy0), International Conference on Learning Representations (ICLR), 2025. [code](https://github.com/alibaba/Route)
- <font color="blue">[*TMM'24*]</font> Ruitao Pu*, **Yang Qin\***, Dezhong Peng#, Xiaoming Song, Huiming Zheng, [Deep Reversible Consistency Learning for Cross-modal Retrieval](https://arxiv.org/pdf/2501.05686), IEEE Transactions on Multimedia (TMM), 2024. [code](https://github.com/perquisite/DRCL)
- <font color="blue">[*CVPR'24*]</font> **Yang Qin**, Yingke Chen, Dezhong Peng, Xi Peng, Joey Tianyi Zhou, Peng Hu#, [Noisy-Correspondence Learning for Text-to-Image Person Re-identification](https://arxiv.org/pdf/2308.09911.pdf), IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2024.  [code](https://github.com/QinYang79/RDE)
- <font color="blue">[*NeurIPS'23*]</font> **Yang Qin**, Yuan Sun, Dezhong Peng, Joey Tianyi Zhou, Xi Peng, Peng Hu#, [Cross-modal Active Complementary Learning with Self-refining Correspondence](https://openreview.net/pdf?id=UBBeUjTja8), Neural Information Processing Systems (NeurIPS), 2023.  [code](https://github.com/QinYang79/CRCL)
- <font color="blue">[*ACM MM'22*]</font> **Yang Qin**, Dezhong Peng, Xi Peng, Xu Wang, Peng Hu#, [Deep Evidential Learning with Noisy Correspondence for Cross-modal Retrieval](https://drive.google.com/file/d/1YVXD2ki5txBY6khG62EHwCi6cnQVRE4I/view), Proceedings of the 30th ACM International Conference on Multimedia, 10-14 October 2022. [code](https://github.com/QinYang79/DECL)

- <font color="blue">[*TIP'24*]</font> Yongxiang Li, **Yang Qin**, Yuan Sun, Dezhong Peng, Xi Peng, Peng Hu#, [RoMo: Robust Unsupervised Multimodal Learning With Noisy Pseudo Labels](https://ieeexplore.ieee.org/abstract/document/10653726), Proceedings of the 30th ACM International Conference on Multimedia, 10-14 October 2022. [code](https://github.com/sunyuan-cs/2024-TKDE-RMCNC)
- <font color="blue">[*TKDE'24*]</font> Yuan Sun, **Yang Qin**, Yongxiang Li, Dezhong Peng, Xi Peng, Peng Hu#, [Robust Multi-View Clustering With Noisy Correspondence](https://ieeexplore.ieee.org/abstract/document/10595464), Proceedings of the 30th ACM International Conference on Multimedia, 10-14 October 2022. [code](https://github.com/sunyuan-cs/2024-TKDE-RMCNC)



- For others, see [Google Scholar](https://scholar.google.com/citations?user=Ci4FBHoAAAAJ&hl=zh-CN&authuser=1). # and * indicate the corresponding author and equal contribution.

# 📖 Educations and Experiences

- *2021.09 -  now*, PhD, the College of Computer Science, Sichuan University, Chengdu China.
- *2024.05 -  2024.12*, the Research Internship at Alibaba Cloud (Apsara Lab led by [Jieping Ye](https://scholar.google.com/citations?hl=zh-CN&authuser=1&user=T9AzhwcAAAAJ)), Hangzhou China.
- *2017.09 - 2021.06*, Undergraduate,  the College of Software Engineering, Sichuan University, Chengdu China.

# 🎖 Honors and Awards
- *2024.11*, PhD student National Scholarship.
- *2024.10*, Outstanding Graduate Student of Sichuan University.
- *2023.10*, Tencent Scholarship.
- *2023.10*, Outstanding Graduate Student of Sichuan University.
- *2022.10*, PhD student Innovation Scholarship.

# 🙋 Services 
- *Conference Reviewer*: NeurIPS, ICLR, ICML, CVPR, ICCV, ECCV, ACMMM, IJCAI, AAAI, AISTATS, etc.
- *Journal Reviewer*: TIP, TNNLS, TVCJ, etc.
