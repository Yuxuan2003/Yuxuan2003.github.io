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

Hello! I'm Yuxuan Zhou (周愈轩), a second-year Ph.D. student at the <a href="https://www.sigs.tsinghua.edu.cn/" target="_blank">Shenzhen International Graduate School, Tsinghua University</a>, advised by Professor <a href="https://scholar.google.com/citations?user=koAXTXgAAAAJ&hl=zh-CN" target="_blank">Shu-Tao Xia</a> and Professor <a href="https://scholar.google.com/citations?user=MqJNdaAAAAAJ&hl=zh-CN" target="_blank">Tao Dai</a>. I received my B.Eng. in Cybersecurity (Qiming Honor Class) from <a href="https://www.hust.edu.cn/" target="_blank">Huazhong University of Science and Technology</a> in 2025.

**My research focuses on the safety and alignment of foundation models, and the detection of AI-generated content.** I believe both will matter for a long time to come. Reinforcement learning runs through both lines — as the way to align models, and as the way to train detectors that generalize.

I have worked on these problems at <a href="https://www.bytedance.com/" target="_blank">ByteDance</a> and <a href="https://hunyuan.tencent.com/" target="_blank">Tencent Hunyuan</a>. I'm always happy to talk about research, collaborations, or internship opportunities — feel free to reach out.

<p style="margin-top: 1em;">
<a href="https://scholar.google.com/citations?user=3r8slUEAAAAJ" target="_blank">Google Scholar</a> &nbsp;·&nbsp; <a href="https://github.com/Yuxuan2003" target="_blank">GitHub</a> &nbsp;·&nbsp; <a href="mailto:zhouyuxuan25@mails.tsinghua.edu.cn">Email</a>
</p>

# 🔬 Research

**Safety & Alignment of Foundation Models.** As models gain tools and autonomy, the cost of misalignment grows with them. I probe where alignment fails — through automated red-teaming and jailbreaking of multimodal models — and repair it with RL-based post-training that treats safety and capability as a joint objective rather than a trade-off.

**AI-Generated Content Detection.** Detectors that hold up against unseen forgeries in the real world. To close the benchmark-to-deployment gap, we use generative models to synthesize forgery types and corruptions missing from public data, so detectors learn artifacts that transfer rather than dataset-specific shortcuts. I lead a team building a deployed platform with <a href="https://www.km-e.cn/imagedetection" target="_blank">KME</a>, serving insurance and forensic clients.

# 🔥 News
- *2026.08*: &nbsp;🎉 Four papers were accepted by **EMNLP 2026** (2 Main, 2 Findings), including one in the Main Conference as first author!
- *2026.06*: &nbsp;🎖 I joined the Foundation Model Department at **Tencent Hunyuan** as a research intern, working on foundation model safety and alignment.
- *2025.12*: &nbsp;🎉 One paper on AI-generated image detection was accepted by **ICASSP 2026**!
- *2025.11*: &nbsp;🎉 One paper (as first author) on deepfake detection was accepted by **AAAI 2026**!
- *2025.06*: &nbsp;🎊 I received my B.Eng. from Huazhong University of Science and Technology (HUST) and started my Ph.D. in August 2025. Thank you to all my advisors and collaborators!
- *2025.03*: &nbsp;🎉 One paper on backdoor sample detection was accepted by **IEEE S&P 2025**!
- *2025.03*: &nbsp;🎖 I joined Flow Security at ByteDance as a research intern, mentored by <a href="https://scholar.google.com/citations?user=wBH_Q1gAAAAJ&hl=zh-CN" target="_blank">Yang Bai</a>!
- *2024.11*: &nbsp;🎉 One paper on adversarial examples was accepted by **AAAI 2025** as an **Oral**!
- *2024.07*: &nbsp;🥇 Our work won <a href="https://mp.weixin.qq.com/s/FgapWoppYAo9-hf7h3Rdzw" target="_blank">Special Prize (only 12 nationwide, first in HUST history)</a> and First Prize in the <a href="http://www.ciscn.cn/" target="_blank">National College Student Information Security Competition</a>.

# 📝 Publications

<sub>\* denotes first author. Full list available on <a href="https://scholar.google.com/citations?user=3r8slUEAAAAJ" target="_blank">Google Scholar</a>.</sub>

### Safety & Alignment of Foundation Models

- **EMNLP 2026 (Main)** &nbsp; [Why Does Weak-OOD Help? A Further Step Towards Understanding Jailbreaking VLMs](https://arxiv.org/pdf/2511.08367)  
**Yuxuan Zhou**\*, Yuzhao Peng, Yang Bai, Kuofeng Gao, Yihao Zhang, Yechao Zhang, Xun Chen, Tao Yu, Tao Dai, Shu-Tao Xia
  - Examines the robustness of safety alignment through the lens of jailbreaking, identifying the *weak-OOD* phenomenon as a mismatch between intent perception and refusal triggering.

- **IEEE S&P 2025** &nbsp; [Secure Transfer Learning: Training Clean Model Against Backdoor in Pre-trained Encoder and Downstream Dataset](https://arxiv.org/pdf/2504.11990)  
Yechao Zhang, **Yuxuan Zhou**, Tianyu Li, Minghui Li, Shengshan Hu, Wei Luo, Leo Yu Zhang

- **AAAI 2025 (Oral)** &nbsp; [Breaking Barriers in Physical-World Adversarial Examples: Improving Robustness and Transferability via Robust Feature](https://ojs.aaai.org/index.php/AAAI/article/view/32870)  
Yichen Wang, **Yuxuan Zhou**, Ziqi Zhou, Hangtao Zhang, Wei Wan, Shengshan Hu, Minghui Li

- **Preprint** &nbsp; [JPRO: Automated Multimodal Jailbreaking via Multi-Agent Collaboration Framework](https://arxiv.org/pdf/2511.07315)  
**Yuxuan Zhou**\*, Yang Bai, Kuofeng Gao, Tao Dai, Shu-Tao Xia

### AI-Generated Content Detection

- **AAAI 2026** &nbsp; [Improving Deepfake Detection with Reinforcement Learning-Based Adaptive Data Augmentation](https://arxiv.org/pdf/2511.07051) &nbsp; [[code]](https://github.com/Yuxuan2003/CRDA)  
**Yuxuan Zhou**\*, Tao Yu, Wen Huang, Yuheng Zhang, Tao Dai, Shu-Tao Xia
  - Recasts data augmentation as an RL-scheduled curriculum, letting an agent adapt forgery difficulty to the detector's current state, with causal inference suppressing augmentation-induced spurious correlations.

- **ICASSP 2026** &nbsp; [M2EA: Multi-VAE Manifold Envelope Alignment for Challenging AI-Generated Image Detection](https://ieeexplore.ieee.org/abstract/document/11463215)  
Ruiqi Liu, Yi Han, Boyi Sun, Houxin He, **Yuxuan Zhou**, Yan Wang

### Others

- **TMLR 2025** &nbsp; [BrowserAgent: Building Web Agents with Human-Inspired Web Browsing Actions](https://arxiv.org/abs/2510.10666)  
Tao Yu, Zhengbo Zhang, Zhiheng Lyu, Junhao Gong, Hongzhu Yi, Xinming Wang, **Yuxuan Zhou**, Jiabing Yang, Ping Nie, Yan Huang, Wenhu Chen

# 💻 Experience
- *2026.06 - 2026.08*, <a href="https://hunyuan.tencent.com/" target="_blank">**Tencent Hunyuan**</a>, Foundation Model Department, China — foundation model safety and alignment.
- *2025 - 2026*, <a href="https://www.bytedance.com/" target="_blank">**ByteDance**</a>, Flow Security, China — mentored by <a href="https://scholar.google.com/citations?user=wBH_Q1gAAAAJ&hl=zh-CN" target="_blank">Yang Bai</a>.

# 📖 Education
- *2025.08 - Now*, **Ph.D. in Computer Science**, Shenzhen International Graduate School, Tsinghua University, Shenzhen, China.
- *2021.09 - 2025.06*, **B.Eng. in Cybersecurity (Qiming Honor Class)**, Huazhong University of Science and Technology, Wuhan, China. &nbsp;GPA 3.92/4.00, rank 2/18.

# 🎖 Honors and Awards
- *2024.07*: The 17th National College Student Information Security Competition — Special Prize (12 nationwide) and First Prize. <a href="https://mp.weixin.qq.com/s/FgapWoppYAo9-hf7h3Rdzw" target="_blank">First in HUST history</a>.
- *2024.03*: Qiushi Cup, Silver Award (only one in the department).
- *2023.07*: National-level Undergraduate Innovation & Entrepreneurship Training Program (only one in the department).
- *2022.01*: Shenyang Aircraft Corporation "Flying Shark" Scholarship.

# 🛠 Academic Service
- Reviewer: AAAI 2026, AAAI 2027, ACL 2026.
