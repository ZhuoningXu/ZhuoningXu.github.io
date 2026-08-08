---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
sitemap: false
robots: "noindex, nofollow"
---

{% include base_path %}

PDF Preview
======

<div class="cv-pdf-preview">
  <iframe
    src="https://drive.google.com/file/d/1tGiP4rQVepzG_fB-wuadsPpsBLA_vo6U/preview"
    title="Zhuoning Xu CV PDF preview"
    loading="lazy"
    allow="autoplay">
  </iframe>
</div>

[Open or download the PDF in Google Drive](https://drive.google.com/file/d/1tGiP4rQVepzG_fB-wuadsPpsBLA_vo6U/view?usp=sharing)
· [View the shared folder](https://drive.google.com/drive/folders/1AtOY0I-bBtx2GeO2vApuzI9ZSAp2eh_k?usp=sharing)

Access and download permissions are managed through Google Drive. If the embedded
preview does not load, use the direct Google Drive link above.

Research Interests
======
Reliable and secure LLM agents; agent evaluation and benchmarking; post-training and continual adaptation; human-in-the-loop and multi-agent systems.

Education
======
* M.S. in Computer Science, New York University (Courant Institute of Mathematical Sciences), Sept. 2025 - May 2027 (expected)
  * GPA: 3.8 / 4.0
  * Coursework: Programming Languages, Mathematical Techniques for CS Applications, Machine Learning, Operating Systems, Natural Language Processing, Deep Learning, Computer Vision, GPUs: Architecture & Programming
* B.Eng. in Electronic & Information Engineering (Minor in Computing), The Hong Kong Polytechnic University, Sept. 2021 - Jun. 2025
  * First-Class Honours · ranked **Top 3 in major** (GPA 3.8) · Dean's Honours List (2021-2025)
  * Coursework: Computer Systems, Programming Languages, Object-Oriented Programming, Web Application Design and Development, Operating Systems, Database Systems, Data and Computer Communication, Data Structures, Computer Vision and Pattern Recognition

Awards &amp; Honors
======
* **Dean's Honours List** (2023/24, 2022/23, 2021/22) — Faculty of Engineering, PolyU · Oct. 2024
* **VTech Group of Companies Scholarship 2023/24** — Department of Electrical and Electronic Engineering, PolyU jointly with VTech Group of Companies · Aug. 2024
* **EEE Microcontroller Application Design Contest — 2nd Runner-up** — Department of Electrical and Electronic Engineering, PolyU jointly with RS Components Ltd. · Feb. 2024
* **The Hong Kong Polytechnic University Scholarship** — HKPU Scholarship Selection Panel · Dec. 2023

Skills
======
* **Programming Languages:** Python, C/C++, Java, SQL, JavaScript, PHP, HTML/CSS, Assembly Language
* **LLM & Post-training:** Supervised Fine-tuning (SFT), Parameter-Efficient Fine-tuning (LoRA), Preference Optimization (DPO), Hugging Face Transformers
* **ML & Data Libraries:** PyTorch, scikit-learn, Pandas, NumPy, Matplotlib, OpenCV
* **Development Tools:** Git/GitHub, Docker, Linux/Bash, MySQL, MATLAB, LaTeX/Overleaf, Android Studio
* **Embedded Systems & Robotics:** STM32, Arduino, STM32CubeMX, Arduino IDE, Embedded C, Microcontroller Programming, Sensor Integration

Internship Experience
======
* **Quantitative Trading Intern**, MOL Quant Limited, Hong Kong (Jan. 2025 - Jun. 2025)
  * Built a Python quantitative-trading framework with a data pipeline, vectorized backtesting engine, and execution interfaces, together with an LLM-agent platform for real-time financial-news sentiment and event analysis driving intraday signals.
* **Assistant Software Engineer Intern** (Front-End & Data Monitoring), YOTAI Digital Energy Technology Co., Ltd., Shenzhen, China (Jun. 2024 - Aug. 2024)
  * Built a real-time equipment-monitoring web application with Umi/Node.js, a WebSocket subscription pipeline, a unified device model, and automated Python reporting.

Research Experience
======
<div class="research-featured" markdown="1">

* **MasDrift: Benchmarking Authorization Preservation Across Multi-Agent Architectures** (First Author, 2026) - *Under review at AAAI 2027; submitted to arXiv.* ([Code](https://github.com/ZhuoningXu/MasDrift))
  * **Authors:** **Zhuoning Xu**<sup>1,*</sup>, Xiucheng Zhang<sup>1,*</sup>, Hanjun Luo<sup>1,2,*</sup>, Yingbin Jin<sup>3</sup>, Yinpeng Dong<sup>4,†</sup>, and Hanan Salam<sup>1,2</sup>
  * **Affiliations:** <sup>1</sup> New York University; <sup>2</sup> New York University Abu Dhabi; <sup>3</sup> The Hong Kong Polytechnic University; <sup>4</sup> Tsinghua University
  * <sup>*</sup> Equal contribution; <sup>†</sup> Corresponding author.
  * **Advisors:** Prof. Hanan Salam (NYU Abu Dhabi) and Prof. Yinpeng Dong (Tsinghua University)
  * Formulated authorization preservation as a property that must survive delegation and defined a benign threat model that isolates drift as an endogenous failure of decomposition and hand-off.
  * Designed a 600-task benchmark, a parameterized coordination runner, and trace-level evaluators combining deterministic rules with a human-calibrated LLM judge.
  * Proposed a source-anchored authorization defense and led the experimental study, analysis, manuscript, and figures, showing that source re-anchoring suppresses unauthorized actions at negligible completion cost.

</div>

* **MisPlan: When Plans Hurt Coding Agents** (Co-Author, 2026) - *Under review at AAAI 2027; preprint forthcoming.* ([OpenReview](https://openreview.net/forum?id=EYL854kJNj))
  * **Authors:** Hanjun Luo, Xiucheng Zhang, **Zhuoning Xu**, et al.
  * **Affiliations:** New York University; New York University Abu Dhabi; Tencent
  * **Advisor:** Prof. Hanan Salam (NYU Abu Dhabi); **Industry Mentor:** Richeng Xuan (Tencent)
  * Ran the full evaluation across six models on a unified mini-SWE-agent harness and three native coding agents (Claude Code, Codex, and CodeBuddy), and quality-checked every task's Docker environment and pass/fail oracle.
  * Analyzed cross-condition resolve-rate asymmetry and produced the paper's diagnostic figures and tables, showing that goal-scope errors dominate the harm while implementation-detail errors are largely recoverable.
* **Reconcile-then-Resume: Proportionate Mid-Run Steering for Coding Agents** (First Author, 2026) - *Manuscript in preparation for ICLR 2027.*
  * **Advisor:** Prof. Hanan Salam (NYU Abu Dhabi)
  * Formalized mid-run steering as a proportional-integration problem over aligned, partial-revision, and conflicting user instructions, and built a SWE-bench-based pipeline with integration-loss, overhead, and behavior-retention metrics.
  * Proposed a runtime framework that reconciles new instructions against in-progress agent state and selectively preserves, revises, or reverts prior work; validated it in controlled experiments and through Codex's native steering interface.
* **VLHSA: Vision-Language Hierarchical Semantic Alignment for Jigsaw Puzzle Solving with Eroded Gaps** (First Author, 2025) - *AAAI 2026 Student Abstract and Poster Program.* ([arXiv:2509.25202](https://arxiv.org/abs/2509.25202))
  * **Authors:** **Zhuoning Xu**<sup>1</sup> and Xinyan Liu<sup>1</sup>
  * **Affiliation:** <sup>1</sup> The Hong Kong Polytechnic University
  * **Advisor:** Prof. Kin-Man Lam (PolyU)
  * Introduced textual descriptions as semantic anchors and aligned Vision Mamba and BLIP representations at patch and image levels using InfoNCE contrastive loss and Hungarian matching.
  * Led the research pipeline and ablation studies over local and global alignment branches, demonstrating significant permutation-accuracy gains over pure-vision baselines.
* **A Multi-Perceptual Learning Network for Retina OCT Image Denoising and Classification** (Co-Author, 2024) - *APSIPA ASC 2024.* ([DOI](https://doi.org/10.1109/APSIPAASC63619.2025.10848686))
  * **Authors:** Zhe Xiao<sup>1</sup>, Zongqi He<sup>1</sup>, **Zhuoning Xu**<sup>1</sup>, et al.
  * **Advisors:** Prof. Kin-Man Lam (PolyU) and Prof. Wenjing Jia (UTS)
  * Developed an end-to-end multi-perceptual learning framework integrating a Triple-Cross-Fusion GAN for OCT denoising with a ResNet-based classifier for retinal disease recognition using PyTorch and OpenCV.
  * Conducted controlled comparative experiments, improving classification accuracy by more than one percentage point and reconstruction quality while sustaining real-time GPU inference.

Course Project
======
* **Personalized Style Steering with a LoRA Guide Model** - Machine Learning course project (May 2026)
  * LoRA-fine-tuned a Qwen 3.5-4B model to capture a fixed task style using a reinforcement-learning objective combining style-consistency and task-success rewards.
  * Used the small guide model to steer a frozen large model at inference, improving style and format adherence at substantially lower cost than fine-tuning the large model; benchmarked against prompt-only and SFT baselines.

Publications &amp; Manuscripts
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
