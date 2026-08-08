---
title: "MisPlan: When Plans Hurt Coding Agents"
excerpt: "A diagnostic benchmark showing that correct plans help coding agents, while goal-scope errors can make planning substantially worse than having no plan. <b>Under review at AAAI 2027; preprint forthcoming.</b>"
collection: portfolio
order: 2
authors: '<a href="https://openreview.net/profile?id=~Hanjun_Luo1">Hanjun Luo</a>, <a href="https://openreview.net/profile?id=~Xiucheng_Zhang1">Xiucheng Zhang</a>, <strong><a href="https://openreview.net/profile?id=~Zhuoning_Xu3">Zhuoning Xu</a></strong>, et al.'
affiliations: 'New York University; New York University Abu Dhabi; Tencent'
author_note: 'Advisor and corresponding author: <a href="https://openreview.net/profile?id=~Hanan_Salam1">Hanan Salam</a> (New York University Abu Dhabi). Industry mentor: <a href="https://openreview.net/profile?id=~richeng_xuan1">Richeng Xuan</a> (Tencent). Full author list available on OpenReview.'
---

**2026 · Under review at AAAI 2027; preprint forthcoming** ·
[OpenReview](https://openreview.net/forum?id=EYL854kJNj)

MisPlan studies when plan modes help or hurt coding agents. Grounded in an analysis
of **125,275 real coding-agent sessions**, it introduces a five-type failure taxonomy
and **193 human-validated repository tasks**, each tested with no plan, a correct
plan, and five defective plan variants.

- Ran the full evaluation across **six models** on a unified mini-SWE-agent harness
  and **three native coding agents**: Claude Code, Codex, and CodeBuddy.
- Quality-checked every task's Docker environment and pass/fail oracle so condition
  differences reflected plan content rather than harness artifacts.
- Analyzed cross-condition resolve-rate asymmetry and produced the paper's diagnostic
  figures and tables, showing that goal-scope errors dominate the harm while
  implementation-detail errors are largely recoverable.
