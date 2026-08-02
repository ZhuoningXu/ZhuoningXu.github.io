---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Download as PDF:
[CS / ML résumé]({{ base_path }}/files/CV_Zhuoning_Xu_CS.pdf) ·
[Quant / Finance résumé]({{ base_path }}/files/CV_Zhuoning_Xu_Quant.pdf)

Education
======
* M.S. in Computer Science, New York University (Courant Institute of Mathematical Sciences), Sept. 2025 – May 2027 (expected)
  * GPA: 3.78 / 4.0
  * Coursework: Programming Languages (Racket), Fundamental Algorithms, Mathematical Techniques for CS Applications, Machine Learning, Operating Systems, Natural Language Processing
* B.Eng. in Electronic & Information Engineering (Minor in Computing), The Hong Kong Polytechnic University, Sept. 2021 – Jun. 2025
  * First-Class Honours · ranked **Top 3 in major** (GPA 3.8) · Dean's Honours List (2021/22, 2022/23, 2023/24)

Awards &amp; Honors
======
* **Hong Kong Government Scholarship for Outstanding Performance 2024/25** — HK$80,000 · The Hong Kong Polytechnic University
* **Hong Kong Government Scholarship (Talent)** — HK$10,000 · Dec. 2024 · The Hong Kong Polytechnic University
* **Hong Kong Government Scholarship (Reaching Out Award)** — HK$10,000 · Dec. 2024 · The Hong Kong Polytechnic University
* **Dean's Honours List** (2023/24, 2022/23, 2021/22) — Faculty of Engineering, PolyU · Oct. 2024
* **VTech Group of Companies Scholarship 2023/24** — Department of Electrical and Electronic Engineering, PolyU jointly with VTech Group of Companies · Aug. 2024
* **EEE Microcontroller Application Design Contest — 2nd Runner-up** — Department of Electrical and Electronic Engineering, PolyU jointly with RS Components Ltd. · Feb. 2024
* **The Hong Kong Polytechnic University Scholarship** — HKPU Scholarship Selection Panel · Dec. 2023

Skills
======
* **Programming Languages:** Python (Pandas, NumPy, Scikit-Learn, Matplotlib, PyTorch), C/C++, Java, SQL, Assembly, Web (PHP, HTML, CSS, JavaScript, AJAX)
* **Tools & Platforms:** Git, Docker, Linux Shell, MySQL Workbench, MATLAB, PyCharm, Android Studio, AWS, ROS

Internship Experience
======
* **Quantitative Trading Intern**, MOL Quant Limited, Hong Kong (Jan. 2025 – Jun. 2025)
  * Built a Python quantitative trading framework from scratch: data ingestion/cleaning, vectorized processing, signal research, execution interfaces, and a fully vectorized backtesting engine.
  * Established an AI-agent platform for real-time sentiment/event analysis on financial news, producing investment recommendations and risk alerts for intraday strategies and stock selection.
* **Assistant Software Engineer Intern** (Front-end & Data Monitoring), YOTAI Digital Energy Technology Co., Ltd, Shenzhen, China (Jun. 2024 – Aug. 2024)
  * Resolved data loss, errors, and UI lag by refining Umi/Node.js and shipping reusable hooks (WebSocket, device model, device data); improved page responsiveness by 15%.
  * Built a monitoring web app and a unified equipment model, standardizing backend APIs and stabilizing live views with an efficient subscription/update pipeline.
  * Developed a Python analysis module to automate reporting, boosting metric accuracy and cutting preparation time.
* **Data Engineer Intern** (Business Intelligence & Visualization), Hangzhou Green Cloud S & T Co., Ltd., Hangzhou, China (Jun. 2023 – Jul. 2023)
  * Used SQL to collect, clean, and combine operational data for trustworthy dashboards, reducing one-off data requests.
  * Led desktop and mobile report development for 10+ clients; built visualization platforms with FineBI and launched command-center dashboards and large-screen displays.
  * Captured requirements and applied statistical analysis to deliver forecasts and recommendations that improved operational efficiency.

Research Experience
======
* **VLHSA: Vision-Language Hierarchical Semantic Alignment for Jigsaw Puzzle Solving with Eroded Gaps** (2025) — *Accepted to the AAAI-26 Student Abstract Program* ([arXiv:2509.25202](https://arxiv.org/abs/2509.25202)). Multimodal (Mamba / state-space) framework with hierarchical semantic alignment between visual patches and text; +14.2 pp piece accuracy over vision-only baselines. Led the full research pipeline and ablations.
* **MasDrift: Benchmarking Authorization Preservation Across Multi-Agent Architectures** (2026) — benchmarked authorization preservation across single-agent, centralized, and decentralized architectures using 600 benign productivity tasks in eight domains; evaluated request re-anchoring and delegation-chain policy propagation as defenses. *Preprint; arXiv posting forthcoming.* ([Code](https://github.com/ZhuoningXu/MasDrift))
* **A Multi-Perceptual Learning Network for Retina OCT Image Denoising and Classification** (Jan. 2024 – Sept. 2024) — ResNet + Multi-Perception Learning with a Triple-Cross-Fusion GAN for joint denoising and classification.
* **Sensor-based System for Monitoring Physical Activity in Older Adults** (Sept. 2023 – Sept. 2024) — YOLOv8-Pose + LSTM pipeline; >90% accuracy on 200 samples.

Selected Projects
======
* **Automated Cart Delivery Robot** (Sept. 2023 – May 2024) — multi-sensor fusion on ROS with closed-loop PID pose control; travel-distance error within 5%.
* **Traffic-Sign Detection for ADAS** (Feb. 2024 – Feb. 2025) — two-stage image-restoration + classification pipeline; 25 dB PSNR, ~80% accuracy.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
