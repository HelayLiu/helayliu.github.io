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

Dr. Han Liu (刘晗 in Chinese) is now a postdoctoral scholar working with [Prof. Shuai Wang](https://home.cse.ust.hk/~shuaiw/) and [Prof. Daoyuan Wu](https://daoyuan14.github.io/), in Department of Computer Science and Engineering at the Hong Kong University of Science and Technology (HKUST). He obtained his Ph.D. degree in Software Engineering Institute at East China Normal University (ECNU), under the supervision of [Prof. Yixiang Chen](https://faculty.ecnu.edu.cn/_s43/cyx/main.psp). He is also a visiting student at Nanyang Technological University under the supervision of [Prof. Yang Liu](https://personal.ntu.edu.sg/yangliu/) during 2022-2024. His research interests include program analysis, vulnerability detection.He hopes to collaborate with more innovative researchers on various exciting topics in software engineering, program analysis, vulnerability detection, and program synthesis


<span style="color:red;">I will join Nankai University as an Associate Professor (100 Young Academic Leaders of Nankai University) in March 2026 ！</span>



💬 liuhan AT ust DOT hk
<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=KAWDTzsAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=KAWDTzsAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2026.01*: &nbsp;🎉🎉 Our paper "Revealing the Dark Side of Smart Accounts: An Empirical Study of EIP-7702 Incurred Risks in Blockchain Ecosystem." was accepted by Uesnix Security 2026.
- *2025.08*: &nbsp;🎉🎉 Our paper "Demystifying OpenZeppelin's Own Vulnerabilities and Analyzing Their Propagation in Smart Contracts" and "Have We Solved Access Control Vulnerability Detection in Smart Contracts? A Benchmark Study" were accepted by ASE 2025.
- *2025.03*: &nbsp;🎉🎉 Our paper "Doctor: Optimizing Container Rebuild Efficiency by Instruction Re-Orchestration" was accepted by ISSTA 2025.
- *2024.09*: &nbsp;🎉🎉 I joined the Hong Kong University of Science and Technology as a postdoctoral scholar.
- *2024.07*: &nbsp;🎉🎉 Our paper "PatchFinder: A Two-Phase Approach to Security Patch Tracing for Disclosed Vulnerabilities in Open-Source Software" was accepted by ISSTA 2024.
- *2024.07*: &nbsp;🎉🎉 Our paper "Static Application Security Testing (SAST) Tools for Smart Contracts: How Far Are We?" has won an ACM SIGSOFT Distinguished Paper award! 🏆
- *2024.05*: &nbsp;🎉🎉 Our paper "Using My Functions Should Follow My Checks: Understanding and Detecting Insecure OpenZeppelin Code in Smart Contracts" was accepted by Usenix Security 2024.
- *2024.05*: &nbsp;🎉🎉 I have passed my Ph.D thesis defense.
- *2024.04*: &nbsp;🎉🎉 Our paper “Static Application Security Testing (SAST) Tools for Smart Contracts: How Far Are We?” was accepted by FSE 2024.
- *2023.12*: &nbsp;🎉🎉 Our paper "GPTScan: Detecting Logic Vulnerabilities in Smart Contracts by Combining GPT with Program Analysis" was accepted by ICSE 2024.
- *2023.07*: &nbsp;🎉🎉 Our paper "Comparison and Evaluation on Static Application Security Testing (SAST) Tools for Java" was accepted by ESEC/FSE 2023.
- *2023.01*: &nbsp;🎉🎉 Our paper "A Comprehensive Study on Quality Assurance Tools for Java" was accepted by ISSTA 2023.
- *2022.02*: &nbsp;🎉🎉 I joined Nanyang Technological University as a visiting Ph.D. student. 

# 📝 Selected Publications [[Full List](/publication/)]
\* for the corresponding author.

- [Revealing the Dark Side of Smart Accounts: An Empirical Study of EIP-7702 Incurred Risks in Blockchain Ecosystem.](https://www.usenix.org/conference/usenixsecurity26/)
![](https://img.shields.io/badge/CCF-A-red?style=flat-square) [![](https://img.shields.io/badge/UsenixSecurity-2026-blue?style=flat-square)](https://www.usenix.org/conference/usenixsecurity26/) 
  - Mingyuan Huang, **Han Liu***, Shuo Yang, Daoyuan Wu, and Shuai Wang.
  - To appear in the Usenix Security 2026

- [Demystifying OpenZeppelin's Own Vulnerabilities and Analyzing Their Propagation in Smart Contracts](https://doi.org/xxxxxxxxx) 
![](https://img.shields.io/badge/CCF-A-red?style=flat-square) [![](https://img.shields.io/badge/ASE-2025-blue?style=flat-square)](https://conf.researchr.org/home/ase-2025) 
  - **Han Liu**, Daoyuan Wu, Yuqiang Sun, Shuai Wang, Yang Liu, Yixiang Chen 
  - The 40th IEEE/ACM International Conference on Automated Software Engineering (ASE 2025)

- [Have We Solved Access Control Vulnerability Detection in Smart Contracts? A Benchmark Study](https://doi.org/xxxxxxxxx) 
![](https://img.shields.io/badge/CCF-A-red?style=flat-square) [![](https://img.shields.io/badge/ASE-2025-blue?style=flat-square)](https://conf.researchr.org/home/ase-2025) 
  - **Han Liu**, Daoyuan Wu, Yuqiang Sun, Shuai Wang, Yang Liu
  - The 40th IEEE/ACM International Conference on Automated Software Engineering (ASE 2025)


- [Using My Functions Should Follow My Checks: Understanding and Detecting Insecure OpenZeppelin Code in Smart Contracts](https://www.usenix.org/conference/usenixsecurity24/presentation/liu-han)
![](https://img.shields.io/badge/CCF-A-red?style=flat-square) [![](https://img.shields.io/badge/UsenixSecurity-2024-blue?style=flat-square)](https://www.usenix.org/conference/usenixsecurity24)
  - **Han Liu**, Daoyuan Wu, Yuqiang Sun, Haijun Wang, Kaixuan Li, Yang Liu, Yixiang Chen
  - Usenix Security 2024 
  - [Slides for Usenix Security 2024](/assets/pdf/ZepScope.pdf)
  - ZepScope is now open-sourced. Find more at [this website](https://zepscope.github.io/).

- [Static Application Security Testing (SAST) Tools for Smart Contracts: How Far Are We?](https://doi.org/10.1145/3660772) 
![](https://img.shields.io/badge/CCF-A-red?style=flat-square) [![](https://img.shields.io/badge/FSE-2024-blue?style=flat-square)](https://conf.researchr.org/home/fse-2024) 
  - Kaixuan Li, Yue Xue, Sen Chen, **Han Liu**, Kairan Sun, Ming Hu, Haijun Wang, Yang Liu, Yixiang Chen
  - The ACM International Conference on the Foundations of Software Engineering (FSE 2024)
  - ACM SIGSOFT Distinguished Paper award 🏆

- [GPTScan: Detecting Logic Vulnerabilities in Smart Contracts by Combining GPT with Program Analysis](https://dl.acm.org/doi/abs/10.1145/3597503.3639117)
![](https://img.shields.io/badge/CCF-A-red?style=flat-square) [![](https://img.shields.io/badge/ICSE-2024-blue?style=flat-square)](https://conf.researchr.org/home/icse-2024) 
  - Yuqiang Sun, Daoyuan Wu, Yue Xue, **Han Liu**, Haijun Wang, Zhengzi Xu, Xiaofei Xie, Yang Liu
  - The 46th IEEE/ACM International Conference on Software Engineering (ICSE 2024)  
  - [Slides for ICSE 2024](/assets/pdf/GPTScanSlides.pdf)
  - GPTScan is now open-sourced. Find more at [this website](https://gptscan.github.io/).

- [A Comprehensive Study on Quality Assurance Tools for Java](https://doi.org/10.1145/3597926.3598056) 
![](https://img.shields.io/badge/CCF-A-red?style=flat-square) [![](https://img.shields.io/badge/ISSTA-2023-blue?style=flat-square)](https://conf.researchr.org/home/issta-2023) 
  - **Han Liu**, Sen Chen, Ruitao Feng, Chengwei Liu, Kaixuan Li, Zhengzi Xu, Liming Nie, Yang Liu, Yixiang Chen
  - The 32nd International Symposium on Software Testing and Analysis (ISSTA 2023)

- [Survey on Trustworthiness Measurement for Artificial Intelligence Systems](http://www.jos.org.cn/1000-9825/6592.htm) 
[![](https://img.shields.io/badge/RuanJianXueBao-blue?style=flat-square)]() 
  - **Han Liu**,Kaixuan Li, Yixiang Chen.
  - Ruan Jian Xue Bao/Journal of Software (in Chinese)


# 📖 Educations & Work Experience
- *2024.09 - Now*, Postdoctoral scholar at Department of Computer Science and Engineering, the Hong Kong University of Science and Technology, Hong Kong, China.
- *2022.02 - 2024.02*, Visiting Ph.D. student at school of computer science and engineering, Nanyang Technological University, Singapore.
- *2019.09 - 2024.06*, Ph.D student at Software Engineering Institute, East China Normal University, Shanghai, China. 


<!-- # 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->

# 📫 Services

- Junior PC: ICSE 2026, MSR 2025, MSR 2024
- Sub-reviewer: NDSS 2026, ASE 2025, CCS 2025, OOPSLA 2025, IEEE S&P 2025, ISSTA 2025, Usenix Security 2025, ICSE 2025, NDSS 2025, ASE 2024, CCS 2024, ISSTA 2024, AISACCS 2024, WWW 2024, ASE 2023, FSE 2023, AILA 2023, FSE 2022, AILA 2022, Frontiers of Computer Science
- Journal Reviewer: ACM Transactions on Software Engineering and Methodology, Cybersecurity.


# 🎖 Honors and Awards
- ACM SIGSOFT Distinguished Paper award, FSE 2024, 2024.
-	The distinguished Ph.D. thesis at the College of Information Technology, East China Normal University, 2024.  
- Shanghai Outstanding Graduate Student, Shanghai Municipal Education Commission, 2024.
- Publicly Funded Postgraduate Scholarships, China Scholarship Council, 2022.
- "HUAWEI CUP" 17th China Post-Graduate Mathematical Contest in Modeling 3rd Prize, 2020.
