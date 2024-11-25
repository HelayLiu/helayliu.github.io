---
permalink: /
title: "Homepage"
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

Dr. Han Liu (刘晗 in Chinese) is now a postdoctoral scholar working with [Prof. Shuai Wang](https://home.cse.ust.hk/~shuaiw/) and [Prof. Daoyuan Wu](https://daoyuan14.github.io/), in Department of Computer Science and Engineering at the Hong Kong University of Science and Technology (HKUST). He obtained his Ph.D. dgree in Software Engineering Institute at East China Normal University (ECNU), under the supervision of [Prof. Yixiang Chen](https://faculty.ecnu.edu.cn/_s43/cyx/main.psp). He is also a visiting student at Nanyang Technologial University under the supervision of [Prof. Yang Liu](https://personal.ntu.edu.sg/yangliu/) during 2022-2024. His research interests include program analysis, vulnerability detection.
He hopes to collaborate with more innovative researchers on various exciting topics in software engineering, program analysis, vulnerability detection, and program synthesis.

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=KAWDTzsAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=KAWDTzsAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2024.09*: &nbsp;🎉🎉 I joined the Hong Kong University of Science and Technology as a postdoctoral scholar.
- *2024.07*: &nbsp;🎉🎉Our paper "PatchFinder: A Two-Phase Approach to Security Patch Tracing for Disclosed Vulnerabilities in Open-Source Software" was accepted by ISSTA 2024.
- *2024.07*: &nbsp;🎉🎉 Our paper "Static Application Security Testing (SAST) Tools for Smart Contracts: How Far Are We?" has won an ACM SIGSOFT Distinguished Paper award! 🏆
- *2024.05*: &nbsp;🎉🎉 Our paper "Using My Functions Should Follow My Checks: Understanding and Detecting Insecure OpenZeppelin Code in Smart Contracts" was accepted by Usenix Security 2024.
- *2024.05*: &nbsp;🎉🎉 I have passed my Ph.D thesis defense.
- *2024.04*: &nbsp;🎉🎉 Our paper “Static Application Security Testing (SAST) Tools for Smart Contracts: How Far Are We?” was accepted by FSE 2024.
- *2023.12*: &nbsp;🎉🎉 Our paper "GPTScan: Detecting Logic Vulnerabilities in Smart Contracts by Combining GPT with Program Analysis" was accepted by ICSE 2024.
- *2023.07*: &nbsp;🎉🎉 Our paper "Comparison and Evaluation on Static Application Security Testing (SAST) Tools for Java" was accepted by ESEC/FSE 2023.
- *2023.01*: &nbsp;🎉🎉 Our paper "A Comprehensive Study on Quality Assurance Tools for Java" was accepted by ISSTA 2023.
- *2022.02*: &nbsp;🎉🎉 I joined Nanyang Technological University as a visiting Ph.D. student. 

# 📝 Selected Publications [[Full List](/publication/)]

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1"> -->

<!-- </div>
</div> -->
- [PatchFinder: A Two-Phase Approach to Security Patch Tracing for Disclosed Vulnerabilities in Open-Source Software](https://doi.org/10.1145/3650212.3680305) 
![](https://img.shields.io/badge/CCF-A-red?style=flat-square) [![](https://img.shields.io/badge/ISSTA-2024-blue?style=flat-square)]() [![](https://img.shields.io/badge/arXiv-2407.17065-B31B1B?style=flat-square)](https://arxiv.org/pdf/2407.17065)
  - Kaixuan Li, Jian Zhang, Sen Chen, **Han Liu**, Yang Liu, Yixiang Chen
  - The 33rd ACM SIGSOFT International Symposium on Software Testing and Analysis (ISSTA 2024)

- [Using My Functions Should Follow My Checks: Understanding and Detecting Insecure OpenZeppelin Code in Smart Contracts](https://www.usenix.org/conference/usenixsecurity24/presentation/liu-han)
![](https://img.shields.io/badge/CCF-A-red?style=flat-square)[![](https://img.shields.io/badge/UsenixSecurity-2024-blue?style=flat-square)](https://www.usenix.org/conference/usenixsecurity24/presentation/liu-han)
  - **Han Liu**, Daoyuan Wu, Yuqiang Sun, Haijun Wang, Kaixuan Li, Yang Liu, Yixiang Chen
  - Usenix Security 2024 
  - [Slides for Usenix Security 2024](/assets/pdf/ZepScope.pdf)
  - ZepScope is now open-sourced. Find more at [this website](https://zepscope.github.io/).


- [Static Application Security Testing (SAST) Tools for Smart Contracts: How Far Are We?](https://doi.org/10.1145/3660772) 
![](https://img.shields.io/badge/CCF-A-red?style=flat-square) [![](https://img.shields.io/badge/FSE-2024-blue?style=flat-square)]() [![](https://img.shields.io/badge/arXiv-2404.18186-B31B1B?style=flat-square)](https://arxiv.org/pdf/2404.18186)
  - Kaixuan Li, Yue Xue, Sen Chen, **Han Liu**, Kairan Sun, Ming Hu, Haijun Wang, Yang Liu, Yixiang Chen
  - The ACM International Conference on the Foundations of Software Engineering (FSE 2024)
  - ACM SIGSOFT Distinguished Paper award 🏆

- [FineWAVE: Fine-Grained Warning Verification of Bugs for Automated Static Analysis Tools.](https://arxiv.org/abs/2403.16032) 
[![](https://img.shields.io/badge/arXiv-2401.16185-B31B1B?style=flat-square)](https://arxiv.org/pdf/2403.16032)
  - Han Liu, Jian Zhang, Cen Zhang, Xiaohan Zhang, Kaixuan Li, Sen Chen, Shang-Wei Lin, Yixiang Chen, Xinhua Li, Yang Liu.
  - Preprint 


- [LLM4Vuln: A Unified Evaluation Framework for Decoupling and Enhancing LLMs' Vulnerability Reasoning](https://arxiv.org/abs/2401.16185) 
[![](https://img.shields.io/badge/arXiv-2401.16185-B31B1B?style=flat-square)](https://arxiv.org/abs/2401.16185)
  - Yuqiang Sun, Daoyuan Wu, Yue Xue, **Han Liu**, Wei Ma, Lyuye Zhang, Miaolei Shi, Yang Liu
  - Preprint 

- [GPTScan: Detecting Logic Vulnerabilities in Smart Contracts by Combining GPT with Program Analysis](https://dl.acm.org/doi/abs/10.1145/3597503.3639117)
![](https://img.shields.io/badge/CCF-A-red?style=flat-square) [![](https://img.shields.io/badge/ICSE-2024-blue?style=flat-square)]() [![](https://img.shields.io/badge/arXiv-2308.03314-B31B1B?style=flat-square)](https://arxiv.org/abs/2308.03314)
  - Yuqiang Sun, Daoyuan Wu, Yue Xue, **Han Liu**, Haijun Wang, Zhengzi Xu, Xiaofei Xie, Yang Liu
  - The 46th IEEE/ACM International Conference on Software Engineering (ICSE 2024)  
  - [Slides for ICSE 2024](/assets/pdf/GPTScanSlides.pdf)
  - GPTScan is now open-sourced. Find more at [this website](https://gptscan.github.io/).



- [Comparison and Evaluation on Static Application Security Testing (SAST) Tools for Java](https://doi.org/10.1145/3611643.3616262.) 
![](https://img.shields.io/badge/CCF-A-red?style=flat-square) [![](https://img.shields.io/badge/ESEC/FSE-2023-blue?style=flat-square)]()
  - Kaixuan Li, Sen Chen, Lingling Fan, Ruitao Feng, **Han Liu**, Chengwei Liu, Yang Liu, Yixiang Chen
  - The 31st ACM Joint European Software Engineering Conference and Symposium on the Foundations of Software Engineering (ESEC/FSE 2023)

- [A Comprehensive Study on Quality Assurance Tools for Java](https://doi.org/10.1145/3597926.3598056) 
![](https://img.shields.io/badge/CCF-A-red?style=flat-square) [![](https://img.shields.io/badge/ISSTA-2023-blue?style=flat-square)]() [![](https://img.shields.io/badge/arXiv-2305.16812-B31B1B?style=flat-square)](https://arxiv.org/abs/2305.16812)
  - **Han Liu**, Sen Chen, Ruitao Feng, Chengwei Liu, Kaixuan Li, Zhengzi Xu, Liming Nie, Yang Liu, Yixiang Chen.
  - The 32nd International Symposium on Software Testing and Analysis (ISSTA 2023)

- [Survey on Trustworthiness Measurement for Artificial Intelligence Systems](http://www.jos.org.cn/1000-9825/6592.htm) 
[![](https://img.shields.io/badge/RuanJianXueBao-blue?style=flat-square)]() 
  - **Han Liu**,Kaixuan Li, Yixiang Chen.
  - Ruan Jian Xue Bao/Journal of Software (in Chinese)


# 📖 Educations & Work Experience
- *2024.09 - Now*, Postdoctoral scholar at Department of Computer Science and Engineering, the Hong Kong University of Science and Technology, Hong Kong, China.
- *2022.02 - 2024.02, visiting Ph.D. student at school of computer science and engineering, Nanyang Technological University, Singapore.
- *2019.09 - 2024.06*, Ph.D student at Software Engineering Institute, East China Normal University, Shanghai, China. 


<!-- # 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->

# 📫 Services

- Junior PC: MSR 2025, MSR 2024
- Sub-reviewer: IEEE S&P, ISSTA-2025, Usenix Security 2025, ICSE-2025, NDSS-2025, ASE-2024, CCS-2024, ISSTA-2024, AISACCS-2024, WWW-2024, ASE-2023, FSE-2023, AILA 2023, FSE-2022, AILA 2022, Frontiers of Computer Science



# 🎖 Honors and Awards
- ACM SIGSOFT Distinguished Paper award, FSE 2024, 2024.
- Shanghai Outstanding Graduate Student, Shanghai Municipal Education Commission, 2024.
- Publicly Funded Postgraduate Scholarships, China Scholarship Council, 2022
- "HUAWEI CUP" 17th China Post-Graduate Mathematical Contest in Modeling 3rd Prize, 2020
