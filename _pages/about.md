---
permalink: /
title: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am **Zhuoning (Johnny) XU**, a Master's student in Computer Science at the
[Courant Institute of Mathematical Sciences, New York University](https://cs.nyu.edu/)
(Sept. 2025 - May 2027, expected). Before NYU, I earned a First-Class Honours BEng in
Electronic & Information Engineering (Minor in Computing) from
[The Hong Kong Polytechnic University](https://www.polyu.edu.hk/) (Sept. 2021 - Jun.
2025), where I graduated **ranked top 3 in my major** and received several merit
scholarships.

My research interests include **reliable and secure LLM agents**, **agent evaluation
and benchmarking**, **post-training and continual adaptation**, and **human-in-the-loop
and multi-agent systems**. I am especially interested in understanding how agent
systems behave under delegation, planning, and mid-run user steering, and in building
efficient methods that adapt models to user objectives.

**Currently**, I am working with **Prof. Hanan Salam at NYU Abu Dhabi** on coding
agents, evaluation, and human-in-the-loop steering. My recent first-author work,
**MasDrift**, was conducted under the guidance of Prof. Salam and **Prof. Yinpeng Dong
at Tsinghua University**. I am also exploring LLM post-training through
parameter-efficient fine-tuning and guide-model-based style steering. I am **actively
open to research opportunities and collaborations** - feel free to reach out.

Research highlights
======
- **MasDrift - Benchmarking Authorization Preservation Across Multi-Agent
  Architectures** - a 600-task benchmark across eight productivity domains that
  formulates authorization preservation as a delegation-level property. It also
  introduces a source-anchored authorization defense that suppresses unauthorized
  actions across model configurations at negligible completion cost. *Under review
  at AAAI 2027; submitted to arXiv.*
  ([Code](https://github.com/ZhuoningXu/MasDrift)).
  - **Authors:** **Zhuoning Xu**<sup>1,*</sup>, Xiucheng Zhang<sup>1,*</sup>, Hanjun Luo<sup>1,2,*</sup>, Yingbin Jin<sup>3</sup>, Yinpeng Dong<sup>4,†</sup>, and Hanan Salam<sup>1,2</sup>
  - **Affiliations:** <sup>1</sup> New York University; <sup>2</sup> New York University Abu Dhabi; <sup>3</sup> The Hong Kong Polytechnic University; <sup>4</sup> Tsinghua University
  - <sup>*</sup> Equal contribution; <sup>†</sup> Corresponding author.
- **MisPlan - When Plans Hurt Coding Agents** - a diagnostic benchmark grounded in
  125,275 real coding-agent sessions and 193 human-validated repository tasks. The
  study evaluates six models and three native coding agents, showing that goal-scope
  errors can erase the benefit of planning. *Under review at AAAI 2027; preprint
  forthcoming.* ([OpenReview](https://openreview.net/forum?id=EYL854kJNj)).
  - **Authors:** Hanjun Luo, Xiucheng Zhang, **Zhuoning Xu**, et al.
  - **Affiliations:** New York University; New York University Abu Dhabi; Tencent
  - **Advisor:** Hanan Salam, New York University Abu Dhabi; **Industry mentor:** Richeng Xuan, Tencent
- **Reconcile-then-Resume - Proportionate Mid-Run Steering for Coding Agents** - a
  runtime framework that reconciles new user instructions against in-progress agent
  state and selectively preserves, revises, or reverts prior work. It is evaluated
  through a SWE-bench-based pipeline and Codex's native steering interface.
  *Manuscript in preparation for ICLR 2027.*
  - **First author:** **Zhuoning Xu**
  - **Advisor:** Hanan Salam, New York University Abu Dhabi
- **VLHSA - Vision-Language Hierarchical Semantic Alignment for Jigsaw Puzzle
  Solving with Eroded Gaps** - a framework combining Vision Mamba and BLIP with
  hierarchical alignment, InfoNCE contrastive learning, and Hungarian matching.
  Published in the **AAAI 2026 Student Abstract and Poster Program**
  ([arXiv](https://arxiv.org/abs/2509.25202)).
  - **Authors:** **Zhuoning Xu**<sup>1</sup> and Xinyan Liu<sup>1</sup>
  - **Affiliation:** <sup>1</sup> The Hong Kong Polytechnic University
- **MFGAN - OCT Image Super-Resolution and Enhancement** - blind degradation and
  multi-frame fusion for reconstructing high-quality retinal OCT images. Published
  at **IWAIT 2025** ([DOI](https://doi.org/10.1117/12.3057230)).
  - **Authors:** Zongqi He<sup>1</sup>, Zhe Xiao<sup>1</sup>, **Zhuoning Xu**<sup>1</sup>, et al.
  - **Corresponding authors:** Wenjing Jia<sup>2</sup> and Kin-Man Lam<sup>1</sup>
  - **Affiliations:** <sup>1</sup> The Hong Kong Polytechnic University; <sup>2</sup> University of Technology Sydney
- **Multi-Perceptual Learning Network for Retina OCT** - an end-to-end framework
  integrating a Triple-Cross-Fusion GAN for denoising with a ResNet classifier. It
  improves classification accuracy by more than one percentage point and sustains
  real-time GPU inference. Published at **APSIPA ASC 2024**
  ([DOI](https://doi.org/10.1109/APSIPAASC63619.2025.10848686)).
  - **Authors:** Zhe Xiao<sup>1</sup>, Zongqi He<sup>1</sup>, **Zhuoning Xu**<sup>1</sup>, et al.
  - **Corresponding authors:** Wenjing Jia<sup>2</sup> and Kin-Man Lam<sup>1</sup>
  - **Affiliations:** <sup>1</sup> The Hong Kong Polytechnic University; <sup>2</sup> University of Technology Sydney

Beyond research, I have interned across **software engineering and quantitative
trading** - building a real-time equipment-monitoring web application, a vectorized
Python backtesting framework, and an LLM-agent platform for financial-news sentiment
and event analysis. These experiences have strengthened my interest in connecting
rigorous agent research with practical systems, including tools for detecting market
changes and supporting quantitative research. In the longer term, I am especially
interested in opportunities related to Hong Kong's technology and financial
ecosystem.

See my [publications](/publications/) and [projects](/portfolio/) for details.
Feel free to reach out at
[zx2094@nyu.edu](mailto:zx2094@nyu.edu).
