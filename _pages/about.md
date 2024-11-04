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
{% assign gsDataBaseUrl = "<https://cdn.jsdelivr.net/gh/>" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "<https://raw.githubusercontent.com/>" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am pursuing a Ph.D. degree at the School of Cyber Science and Engineering, Huazhong University of Science and Technology, advised by [Assoc. Prof. Ming Wen](https://mingwen-cs.github.io/index.html). Before that, I received my B.S. degree from the School of Computer Science and Engineering at NJUPT in 2020. I am also a visiting Ph.D. student at [Nanyang Technological University](https://www.ntu.edu.sg/) under the supervision of [Prof. Yang Liu](https://personal.ntu.edu.sg/yangliu/) during 2024-2025.

My current research interests revolve around supply chain security, program analysis, and automated testing technologies for software.

# 🔥 News

- <span style="color:#FC4E2A">[*2024.10*]</span> &nbsp;🎉🎉 Our paper "How Does Code Optimization Impact Third-party Library Detection for Android Applications?" has won an [<span style="color:#FC4E2A">ACM SIGSOFT Distinguished Paper award!</span>](https://conf.researchr.org/info/ase-2024/awards) 🏆!
- <span style="color:#FC4E2A">[*2024.08*]</span> &nbsp;🎉🎉 Two paper were accepted by the **Research track of ASE 2024**!
- <span style="color:#FC4E2A">[*2024.07*]</span> &nbsp;🎉🎉 One paper was accepted by the **ACL 2024**!
- <span style="color:#FC4E2A">[*2024.06*]</span> &nbsp;🎉🎉 One paper was accepted by the **ASPLOS 2024**!

# 📝 Publications

- <span style="color:#337AB7">[**ASE'24**]</span> **Zifan Xie**, Ming Wen, Tinghan Li, Yiding Zhu, Qinsheng Hou, Hai Jin. **How Does Code Optimization Impact Third-party Library Detection for Android Applications?**  In *IEEE/ACM International Conference on Automated Software Engineering (ASE)*, 2024. (<span style="color:#FC4E2A">CCF-A</span>)  [[PDF](https://xzf1234.github.io/pdfs/ASE24_LibHunter.pdf)] [[DOI](https://dl.acm.org/doi/10.1145/3691620.3695554)][[CODE](https://github.com/CGCL-codes/LibHunter)] 
  [<span style="color:#FC4E2A">ACM SIGSOFT Distinguished Paper award 🏆</span>](https://conf.researchr.org/info/ase-2024/awards)

- <span style="color:#337AB7">[**ASE'24**]</span> **Zifan Xie**, Ming Wen, Zichao Wei, Hai Jin. **Unveiling Characteristics and Impact of Security Patch Evolution in OSS Projects.**  
  In *IEEE/ACM International Conference on Automated Software Engineering (ASE)*, 2024. (<span style="color:#FC4E2A">CCF-A</span>)  [[PDF](https://xzf1234.github.io/pdfs/ASE24_PatchEvolution.pdf)] [[DOI](https://dl.acm.org/doi/10.1145/3691620.3695488)] [[CODE](https://github.com/CGCL-codes/PatchEvolution)]

- <span style="color:#337AB7">[**ACL'24**]</span> Xiaohu Du, Ming Wen, Jiahao Zhu, **Zifan Xie**, Bin Ji, Huijun Liu, Xuanhua Shi, Hai Jin. **Generalization-Enhanced Code Vulnerability Detection via Multi-Task Instruction Fine-Tuning.** In *Annual Conference of the Association for Computational Linguistics (ACL)*, 2024. (<span style="color:#FC4E2A">CCF-A</span>)  [[PDF](https://xzf1234.github.io/pdfs/ACL24.pdf)] [[DOI](https://doi.org/10.48550/arXiv.2406.03718)]  [[CODE](https://github.com/CGCL-codes/VulLLM)]

- <span style="color:#337AB7">[**ASPLOS'24**]</span> **Zifan Xie**, Ming Wen, Shiyu Qiu, Hai Jin. **Validating JVM Compilers via Maximizing Optimization Interactions.**  In *ACM Conference on Architectural Support for Programming Languages and Operating Systems (ASPLOS)*, 2024. (<span style="color:#FC4E2A">CCF-A</span>)   [[preprint](https://xzf1234.github.io/pdfs/ASPLOS24fall-MopFuzzer.pdf)] <!-- [[DOI]()] --> [[CODE](https://github.com/CGCL-codes/MopFuzzer)]

- <span style="color:#337AB7">[**ISSTA'23**]</span> **Zifan Xie**, Ming Wen, Haoxiang Jia, Xiaochen Guo, Xiaotong Huang, Deqing Zou, Hai Jin. **Precise and Efficient Patch Presence Test for Android Applications against Code Obfuscation.**   In *ACM SIGSOFT International Symposium on Software Testing and Analysis (ISSTA)*, 2023. (<span style="color:#FC4E2A">CCF-A</span>)  [[PDF](https://xzf1234.github.io/pdfs/ISSTA23-PHunter.pdf)] [[DOI](https://doi.org/10.1145/3597926.3598061)]  [[CODE](https://github.com/CGCL-codes/PHunter)]

- <span style="color:#337AB7">[**ASE'23**]</span> Yintong Huo, Yichen Li, Yuxin Su, Pinjia He, **Zifan Xie**, Michael R. Lyu. **AutoLog: A Log Sequence Synthesis Framework for Anomaly Detection.**  In *IEEE/ACM International Conference on Automated Software Engineering (ASE)*, 2023. (<span style="color:#FC4E2A">CCF-A</span>)   [[PDF](https://xzf1234.github.io/pdfs/ASE23-AutoLog.pdf)] [[DOI](https://doi.org/10.1109/ASE56229.2023.00133)] [[CODE](https://github.com/logpai/AutoLog)]

- <span style="color:#337AB7">[**ICSE'23**]</span> Haoxiang Jia, Ming Wen, **Zifan Xie**, Xiaochen Guo, Rongxin Wu, Maolin Sun, Kang Chen, Hai Jin. **Detecting JVM JIT Compiler Bugs via Exploring Two-Dimensional Input Spaces.**    In *International Conference on Software Engineering (ICSE)*, 2023. (<span style="color:#FC4E2A">CCF-A</span>)   [[PDF](https://xzf1234.github.io/pdfs/ICSE23-JOpFuzzer.pdf)]  [[DOI](https://doi.org/10.1109/ICSE48619.2023.00016)]  [[CODE](https://github.com/CGCL-codes/JOpFuzzer)]

- <span style="color:#337AB7">[**TSE'23**]</span> Ming Wen, **Zifan Xie**, Kaixuan Luo, Xiao Chen, Yibiao Yang, Hai Jin. **Effective Isolation of Fault-Correlated Variables via Statistical and Mutation Analysis.**   In *IEEE Transactions on Software Engineering (TSE)*, 2023. (<span style="color:#FC4E2A">CCF-A</span>) [[PDF](https://xzf1234.github.io/pdfs/TSE23-IsoVar.pdf)]  [[DOI](https://doi.org/10.1109/TSE.2022.3209590)] [[CODE](https://github.com/MingWEN-CS/IsoVar)]

# 🎖 Honors and Awards

- *2021* National Scholarship.
- *2022* Second Place in the Software Security Track of the DataCon Big Data Security Analysis Competition.
