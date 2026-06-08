---
permalink: /
title: "Home"
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

<span class="anchor" id="about-me"></span>

## Hi there, I am **Qizhen Ying**

I am a first-year DPhil student at the [Active Vision Lab](https://www.robots.ox.ac.uk/~lav/), [University of Oxford](https://www.ox.ac.uk) ([Exeter College](https://www.exeter.ox.ac.uk/)), jointly supervised by [Prof. Victor Adrian Prisacariu](https://www.robots.ox.ac.uk/~victor/) and [Dr. Yangchen Pan](https://yannickycpan.github.io/yangchenpan/). I am also a visiting PhD student with [CV4DT](https://cv4dt.github.io/) at the [University of Cambridge](https://www.cam.ac.uk/), where I work with [Guangming Wang](https://guangmingw.github.io/) and [Yixiong Jing](https://cv4dt.github.io/author/dr-yixiong-jing/). Before starting my DPhil, I completed an MSc in Advanced Computer Science at Oxford and obtained my undergraduate degree in Mathematics at the [University of Bristol](https://www.bristol.ac.uk/), where I conducted machine learning research under the guidance of [Dr. Song Liu](https://allmodelsarewrong.net/).

I am passionate about building physically plausible world models. I believe world models should be developed from both deterministic and generative perspectives, corresponding to physical rules and stochastic noise. Thus effective and stable generative techniques can bridge the gap between simulation and real-world scenarios, and I hope the combination of these models can also learn how the real world evolves over time.

**Research interests:** Physically plausible generative models, World Models, Reinforcement Learning.
**Contact:** [qizhen.ying@eng.ox.ac.uk](mailto:qizhen.ying@eng.ox.ac.uk)

<span class="anchor" id="news"></span>
# News

- *2026.05*: 🎉 One paper was accepted by **ICML 2026**, see you in Seoul this July!
- *2026.01*: 🎉 One paper was accepted by **ICRA 2026**, see you in Vienna this June!

<span class="anchor" id="educations"></span>
# Education

- *2025.10 - now*, DPhil in Engineering Science, University of Oxford.
- *2024.09 - 2025.09*, M.Sc. Advanced Computer Science, University of Oxford.
- *2021.09 - 2024.06*, B.Sc. Mathematics, University of Bristol.

<span class="anchor" id="publications"></span>
# Publications

- **Temporal Difference Learning for Diffusion Models**  
  **Qizhen Ying**, Yangchen Pan, Victor Adrian Prisacariu, Junfeng Wen.  
  *International Conference on Machine Learning (ICML), 2026.*

- **ActionReasoning: Robot Action Reasoning in 3D Space with LLM for Robotic Brick Stacking**  
  Guangming Wang\*, **Qizhen Ying**\*, Yixiong Jing, Olaf Wysocki, Brian Sheil.  
  *IEEE International Conference on Robotics and Automation (ICRA), 2026.*  
  [paper](https://arxiv.org/abs/2602.21161)

- **Missing data imputation by reducing mutual information with rectified flows**  
  Jiahao Yu, **Qizhen Ying**, Leyang Wang, Ziyue Jiang, Song Liu.  
  *Advances in Neural Information Processing Systems (NeurIPS), 2026, Vol. 38, pp. 80324-80352.*  
  [paper](https://arxiv.org/abs/2505.11749)

- **High-dimensional differential parameter inference in exponential family using time score matching**  
  Daniel James Williams, Leyang Wang, **Qizhen Ying**, Song Liu, Mladen Kolar.  
  *International Conference on Artificial Intelligence and Statistics (AISTATS), 2025, pp. 3493-3501 (PMLR).*  
  [paper](https://arxiv.org/abs/2410.10637)
