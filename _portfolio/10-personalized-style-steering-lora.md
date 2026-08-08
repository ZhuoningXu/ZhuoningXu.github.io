---
title: "Personalized Style Steering with a LoRA Guide Model"
excerpt: "A parameter-efficient guide model that steers a frozen LLM toward a target task style at inference time. <b>Machine Learning course project.</b>"
collection: portfolio
order: 7
---

**Machine Learning course project · May 2026**

Explored efficient post-training and inference-time steering with a compact guide
model.

- **LoRA-fine-tuned a Qwen 3.5-4B model** to capture a fixed task style using a
  reinforcement-learning objective that combines style-consistency and task-success
  rewards instead of full-model tuning.
- Used the small style model to steer a frozen large model's generation at inference,
  improving style and format adherence at substantially lower cost than fine-tuning
  the large model.
- Benchmarked the approach against prompt-only and supervised fine-tuning baselines.
