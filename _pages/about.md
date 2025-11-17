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

# 👀 About me
I am Zhenyu Yang (杨振宇), a fourth-year Ph.D. student (2022-2027) at the State Key Laboratory of Multimodal Artificial Intelligence Systems ([MAIS](https://mais.ia.ac.cn/)), Institute of Automation, Chinese Academy of Sciences, advised by [Prof. Changsheng Xu](https://scholar.google.com/citations?user=hI9NRDkAAAAJ&hl=zh-CN). Previously, I earned my Bachelor's degree from Beijing University of Posts and Telecommunications in 2022. 

My research interests include 1. **Streaming Video Understanding**, 2. Multimodal Large Language Models, 3. Multimodal Retrieval. I have previously worked as a research intern with the Tencent Hunyuan team, the Kuaishou Keye team, and the 360 AI Department. I welcome collaboration and am always open to discussing research opportunities—feel free to reach out via email!!!

<!-- <span style="color:red; font-weight:bold;">**Actively seeking industry research/HC positions and PhD opportunities. I am open to discussing potential collaborations and roles!**</span> -->

# 🔥 News
- *2025.11*: &nbsp;🏆🏆 Congratulations to our "[Multi-View Captioning with Semantic Delta Re-Ranking for Zero-Shot Composed Video Retrieval](https://link.springer.com/chapter/10.1007/978-981-95-3393-0_7)" for winning the **Best Paper Award** at ICIG 2025! 
- *2025.09*: &nbsp;🎉🎉 Our paper "[LiveStar: Live Streaming Assistant for Real-World Online Video Understanding](https://openreview.net/forum?id=4n7IifN7yr)" about streaming  Video-LLMs has been accepted to **NeurIPS 2025**!
- *2025.08*: &nbsp;🎉🎉 Our paper "[StreamingCoT: A Dataset for Temporal Dynamics and Multimodal Chain-of-Thought Reasoning in Streaming VideoQA](https://arxiv.org/abs/2510.25332)" has been accepted to ACM MM 2025 Datasets!
- *2025.07*: &nbsp;🎉🎉 I was supported the **CIE-Tencent Doctoral Research Incentive Project**, a competitive grant awarded to **only 23 recipients nationwide**, along with a research fund of **100,000 RMB**.

# 📝 Publications 

<div class='paper-box'>
  <div class='paper-box-image'>
    <div class="badge">NeurIPS 2025</div>
    <img src='images/NeurIPS2025.png' alt="sym" width="100%">
  </div>
  <div class='paper-box-text' markdown="1">


🔥 [NeurIPS'2025] Poster

[LiveStar: Live Streaming Assistant for Real-World Online Video Understanding](https://openreview.net/forum?id=4n7IifN7yr)

**Zhenyu Yang**, Kairui Zhang, Yuhang Hu, Bing Wang, Shengsheng Qian, Bin Wen, Fan Yang, Tingting Gao, Weiming Dong, Changsheng Xu

[[Code]](https://github.com/sotayang/LiveStar) [[Project]](https://sotayang.github.io/LiveStar) [[Paper]](https://openreview.net/forum?id=4n7IifN7yr) [[中文解读]](https://mp.weixin.qq.com/s/GdkpgCxrAlbVrN6AAQn74A)
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div class="badge">ICLR 2025</div>
    <img src='images/ICLR2025.png' alt="sym" width="100%">
  </div>
  <div class='paper-box-text' markdown="1">


🚀 [ICLR'2025] Spotlight

[SVBench: A Benchmark with Temporal Multi-Turn Dialogues for Streaming Video Understanding](https://arxiv.org/abs/2502.10810)

**Zhenyu Yang**, Yuhang Hu, Zemin Du, Dizhan Xue, Shengsheng Qian, Jiahong Wu, Fan Yang, Weiming Dong, Changsheng Xu

[[Code]](https://github.com/sotayang/SVBench) [[Project]](https://sotayang.github.io/SVBench/) [[Paper]](https://arxiv.org/abs/2502.10810) [[Dataset]](https://huggingface.co/datasets/yzy666/SVBench) [[Model]](https://huggingface.co/yzy666/StreamingChat_8B) [[Leaderboard]](https://huggingface.co/spaces/yzy666/SVBench) [[Submission]](https://forms.gle/tmY8PmM5KWSvTGcn7) [[中文解读]](https://mp.weixin.qq.com/s/zFj6Wpy8ePR-2r0iWBghqA) 

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div class="badge">SIGIR 2024</div>
    <img src='images/SIGIR2024.png' alt="sym" width="100%">
  </div>
  <div class='paper-box-text' markdown="1">


🏆 [SIGIR'2024] Best Paper Honorable Mention

[LDRE: LLM-based Divergent Reasoning and Ensemble for Zero-Shot Composed Image Retrieval](https://dl.acm.org/doi/10.1145/3626772.3657740)

**Zhenyu Yang**, Dizhan Xue, Shengsheng Qian, Weiming Dong, Changsheng Xu

[[Code]](https://github.com/sotayang/LDRE) [[Paper]](https://dl.acm.org/doi/10.1145/3626772.3657740) [[Video]](https://www.youtube.com/watch?v=GZ2fv5No4Xc)

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div class="badge">ACM MM 2024</div>
    <img src='images/MM2024.png' alt="sym" width="100%">
  </div>
  <div class='paper-box-text' markdown="1">


🎉 [ACM MM'2024] Poster

[Semantic Editing Increment Benefits Zero-Shot Composed Image Retrieval](https://dl.acm.org/doi/pdf/10.1145/3664647.3681649)

**Zhenyu Yang**, Shengsheng Qian, Dizhan Xue, Jiahong Wu, Fan Yang, Weiming Dong, Changsheng Xu

[[Code]](https://github.com/sotayang/SEIZE) [[Paper]](https://dl.acm.org/doi/pdf/10.1145/3664647.3681649)

  </div>
</div>



<div class='paper-box'>
  <div class='paper-box-image'>
    <div class="badge">ACM MM 2025</div>
    <img src='images/MM2025.png' alt="sym" width="100%">
  </div>
  <div class='paper-box-text' markdown="1">


🎉 [ACM MM'2025] Poster

[StreamingCoT: A Dataset for Temporal Dynamics and Multimodal Chain-of-Thought Reasoning in Streaming VideoQA](https://arxiv.org/abs/2510.25332)

Yuhang Hu, **Zhenyu Yang**, Shihan Wang, Shengsheng Qian, Bin Wen, Fan Yang, Tingting Gao, Changsheng Xu

[[Code]](https://github.com/Fleeting-hyh/StreamingCoT) [[Paper]](https://arxiv.org/abs/2510.25332)

  </div>
</div>



<div class='paper-box'>
  <div class='paper-box-image'>
    <div class="badge">ICIG 2025</div>
    <img src='images/ICIG2025.png' alt="sym" width="100%">
  </div>
  <div class='paper-box-text' markdown="1">


🏆 [ICIG'2025] Best Paper Award

[Multi-View Captioning with Semantic Delta Re-Ranking for Zero-Shot Composed Video Retrieval](https://link.springer.com/chapter/10.1007/978-981-95-3393-0_7)

Zhixiang Ding, Lilong Liu, **Zhenyu Yang**, Shengsheng Qian

[[Code]](https://github.com/sotayang/MCSD) [[Project]](https://sotayang.github.io/MCSD/) [[Paper]](https://link.springer.com/chapter/10.1007/978-981-95-3393-0_7)

  </div>
</div>


# 🎖 Honors and Awards
- Best Paper Honorable Mention (5/791), SIGIR, 2024
- Best Paper Award, ICIG, 2025
- Spotlight Paper (~3.27%), ICLR, 2025
- CIE-Tencent Doctoral Research Incentive Project / 混元学者 (中国电子学会-腾讯博士生科研激励计划), 2025
- National Scholarship, Ministry of Education, China, 2024
- Outstanding Graduate, Beijing, 2022
- Outstanding Graduate, Beijing University of Posts and Telecommunications, 2022
- First-Class Scholarship, Beijing University of Posts and Telecommunications, 2020/2021
- First Prize in American Mathematical Contest in Modeling (MCM), Top 6.7% Globally, 2020

<!-- *2020.03* First Prize in American Mathematical Contest in Modeling (MCM), Top 6.7% Globally -->

# 📖 Educations
- **2022.09 - 2027.06:** Ph.D, State Key Laboratory of Multimodal Artificial Intelligence Systems, Institute of Automation, Chinese Academy of Sciences, Beijing. *Major:* Computer Applied Technology.
- **2018.09 - 2022.06:** Undergraduate, School of Computer Science (National Pilot Software Engineering School), Beijing University of Posts and Telecommunications, Beijing. *Major:* Intelligent Science and Technology.


# 🙋 Services
- **Conference Reviewer:** CVPR 2026, ICLR 2026, AAAI 2026, NeurIPS 2025, ICCV 2025, ACML 2025, etc.
- **Journal Reviewer:** IEEE Transactions on Image Processing (TIP), Transactions on Multimedia Computing Communications and Applications (TOMM), Neurocomputing, Pattern Recognition.


<br><br><br><br><br>