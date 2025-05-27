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

I am a PhD student at the [Hong Kong University of Science and Technology (Guangzhou)](https://www.hkust-gz.edu.cn/), starting from Fall 2024. I am honored to be supervised by Professor [Yuyu Luo](https://luoyuyu.vip/). Previously, I obtained my bachelor's degree from the [School of Information](http://info.ruc.edu.cn/), [Renmin University of China](https://www.ruc.edu.cn/). My research interest primarily focuses on LLM Based Agents, with a particular emphasis on reasoning ablity and the paradigm of constructing agents that are adaptable to multiple environments. 

I am building a community called [MindForge](https://github.com/Mind4Forge), aimed at bringing together researchers and engineers interested in intelligence to explore autonomous and efficient agents across different environments. ***If you are interested, feel free to reach out to me***.

You can find my CV here: [didi's Curriculum Vitae](../assets/CV.pdf).

<span class='anchor' id='news'></span>


# 🔥 News
- *2025.05* We proposed [LiteCoT](https://arxiv.org/abs/2505.19716), simple data synthesis pipeline!
- *2025.05* [Data Interpreter](https://arxiv.org/abs/2402.18679) was accepted by ACL findings.
- *2025.05* [AlphaSQL](https://arxiv.org/abs/2502.17248) was accepted by ICML 2025.
- *2025.04* We finalize the [Foundation Agent Survey](https://arxiv.org/abs/2504.01990) V1, Let's talk about cross-environment agents.
- *2025.03* We proposed [OpenManus](https://github.com/FoundationAgents/OpenManus), we get **46.1K** Stars in two months!
- *2025.02* We proposed [AlphaSQL](https://arxiv.org/abs/2502.17248), the o1 moment for NL2SQL!
- *2025.02* We proposed [SPO](https://arxiv.org/abs/2502.06855) (Self-Supervised Prompt Optimization) and [AoT](https://arxiv.org/abs/2502.12018) (Atom of Thoughts for Markov Test-Time Scaling)
- *2025.02* [AFLOW](https://openreview.net/forum?id=z5uVAKwmjf) was accepted by ICLR 2025 as an Oral Presentation (Top 1.8%)
- *2024.08* I joined the DialLab at HKUST(GZ) as a PhD student, advised by Professor Yuyu Luo.
- *2024.07* We proposed [MobileExperts](https://arxiv.org/abs/2407.03913), a Multi-Agent system in GUI environments.
- *2024.06* MathAI won third place in the 2024 Alibaba Global Mathematics Competition AI Challenge, thanks to SuperCarryMan!
- *2024.02* Participated in my first academic paper, delighted to collaborate with the MetaGPT community to publish [Data Interpreter](https://arxiv.org/abs/2402.18679).
- *2023.12* Participated in the Baidu Hackathon with my homies and won second place.

<span class='anchor' id='publications'></span>
# 📝 Selected Publications
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025 Oral</div><img src='images/aflow.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[AFlow: Automating Agentic Workflow Generation](https://arxiv.org/abs/2410.10762) [[X]](https://x.com/didiforx/status/1890242001817464935)

**Jiayi Zhang**, Jinyu Xiang, Zhaoyang Yu, Fengwei Teng, Xionghui Chen, Jiaqi Chen, Mingchen Zhuge, Xin Cheng, Sirui Hong, Jinlin Wang, Bingnan Zheng, Bang Liu, Yuyu Luo, Chenglin Wu

We introduces AFlow, an automated framework that reformulates workflow optimization as a search problem over code-represented workflows, using Monte Carlo Tree Search to efficiently explore and refine workflows through code modification and execution feedback.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv 2025</div><img src='images/foundationagent-survey.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Advances And Challenges In Foundation Agents](https://arxiv.org/abs/2504.01990) [[X]](https://x.com/BangL93/status/1908128095967592485)

Bang Liu†, Xinfeng Li†, **Jiayi Zhang†**, Jinlin Wang†, Tanjin He†, Sirui Hong†, Hongzhang Liu†, Shaokun Zhang†, Kaitao Song†, Kunlun Zhu†, more than 30 authors , Jian Pei, Qiang Yang, Xiaoliang Qi, Chenglin Wu

We introduce Foundation Agent Survey, let's talk about more on "Fundamental intelligent unit with universal understanding, cognition, and action capabilities that can operate in any environments and collaborate to form collective intelligence".

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">46K Stars</div><img src='images/openmanus.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[OpenManus](https://github.com/FoundationAgents/OpenManus) [[X]](https://x.com/didiforx/status/1897675038972883408) 

OpenManus Team

We introduce OpenManus, an open-source project for enhancing public's understanding of agents. 

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv 2025</div><img src='images/spo.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Self-Supervised Prompt Optimization](https://arxiv.org/abs/2502.06855) [[X]](https://x.com/didiforx/status/1891403112583197111)

Jinyu Xiang†, **Jiayi Zhang†**, Zhaoyang Yu, Fengwei Teng, Jinhao Tu, Xinbing Liang, Sirui Hong, Chenglin Wu, Yuyu Luo

We introduce SPO, a little step into optimizing agent for open-ended tasks.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv 2025</div><img src='images/aot.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Atom of Thoughts for Markov LLM Test-Time Scaling](https://arxiv.org/abs/2502.06855) [[X]](https://x.com/didiforx/status/1895902471635288252)

Fengwei Teng, Zhaoyang Yu, Quan Shi, **Jiayi Zhang**, Chenglin Wu, Yuyu Luo

We introduce Aot, a unique perspective for viewing test time scaling.

</div>
</div>




<span class='anchor' id='educations'></span>

# 📖 Educations
- *2024.08 - Present*, The Hong Kong University of Science and Technology (Guangzhou), Information Hub.
- *2020.09 - 2024.06*, Renmin University of China, Information School.

<span class='anchor' id='internships'></span>

# 💻 Internships
- *2024.7 - Present*, Research Intern, [DeepWisdom](https://www.deepwisdom.ai/), China.
- *2024.6 - 2025.2*, Research Intern, [Thin Red Line](https://www.thinredline.com.cn/), China.
- *2023.12 - 2024.5*, Research Intern, [Lenovo Research AI Lab](https://research.lenovo.com/webapp/view/index.html), China.
- *2023.08 - 2023.12*, Algorithm intern, [ZhiPuAI](https://www.zhipuai.cn/) ,China.
- *2023.07 - 2023.08*, Algorithm intern,[CYOU](https://www.changyou.com/cu.shtml), China.

<span class='anchor' id='competitions'></span>

# 🎯 Competitions and Side Projects
- *2024.6*, 2024 Alibaba Global Mathematics Competition AI Challenge, Top 1% (3/563), Team Leader
- *2024.4*, MetaGPT Android Environment, Core Contributor
- *2023.12*, Baidu & FounderPark AGI Hackathon, Second Place Award, Team Leader
- *2023.9*, MetaGPT Mini Hackathon, Best Contributor
- *2023.8*, AWS GenAl Talent Program, 2 out of 4 awards, Team member

<span class='anchor' id='honors'></span>

# 🎖 Honors and Awards
- *2022.10* The First Class Academic Progress Scholarship, Renmin University of China. 
- *2022.10* The First Class Social Work and Leadership Scholarship, Renmin University of China.
- *2023.10* The First Class Outstanding Student Leadership Scholarship, Renmin University of China.

<span class='anchor' id='leaderships'></span>

# 👥 Leaderships
- *2023.07 - 2024.06*, RUC 36th Student Union Committee, Member.
- *2023.04 - 2024.03*, RUC 45th School of Information Student Union, Chairman.
- *2022.07 - 2023.07*, RUC lth Mingli Academy Student Union, Chairman.

<span class='anchor' id='invited-talks'></span>

# 🔈 invited-talks
- *2025.5*, International Conference on General Artificial Intelligence, Advances And Challenges In Foundation Agents, Conf Org.
- *2025.3*, Jiaxian Workshop, Towards Foundation Agents, HUAWEI ICT
- *2025.3*, Guest Talk, Towards Foundation Agents, Where we are, and where we go?, University of Sydney
- *2025.3*, ThinkZo Workshop, From OpenManus to Foundation Agents, HUAWEI
- *2024.10*, GraphTalk: Automating Effective Agentic Workflow Generation, Ant Group

<span class='anchor' id='services'></span>

# 💁 Services
- Reviewer: ICML 2025, ICML 2025 MAS Workshop