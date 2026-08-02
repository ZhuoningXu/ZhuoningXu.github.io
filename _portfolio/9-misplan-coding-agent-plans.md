---
title: "MisPlan: When Plans Hurt Coding Agents"
excerpt: "A diagnostic benchmark showing that correct plans help coding agents, while goal-scope errors can make planning substantially worse than having no plan. <b>AAAI 2027 Conference Submission.</b>"
collection: portfolio
order: 2
authors: '<a href="https://openreview.net/profile?id=~Hanjun_Luo1">Hanjun Luo</a>, <a href="https://openreview.net/profile?id=~Xiucheng_Zhang1">Xiucheng Zhang</a>, <strong><a href="https://openreview.net/profile?id=~Zhuoning_Xu3">Zhuoning Xu</a></strong>, et al.'
affiliations: 'New York University; New York University Abu Dhabi'
author_note: 'Corresponding author: <a href="https://openreview.net/profile?id=~Hanan_Salam1">Hanan Salam</a> (New York University Abu Dhabi). Full author list available on OpenReview.'
---

**2026 · AAAI 2027 Conference Submission** ·
[OpenReview](https://openreview.net/forum?id=EYL854kJNj)

MisPlan studies when plan modes help or hurt coding agents. Grounded in an analysis
of **125,275 real coding-agent sessions**, it introduces a five-type failure taxonomy
and **193 human-validated repository tasks**, each tested with no plan, a correct
plan, and five defective plan variants.

- Evaluates six models on a unified harness and three native coding agents.
- Finds that correct plans raise resolve rates by 3–14 percentage points.
- Identifies goal-scope errors as the most damaging failure: a 25-point drop that can
  make the expected benefit of plan mode negative.
- Shows that errors in implementation details are substantially less damaging,
  motivating clarification-centric plan-mode design.
