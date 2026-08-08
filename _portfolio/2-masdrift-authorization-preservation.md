---
title: "MasDrift: Benchmarking Authorization Preservation Across Multi-Agent Architectures"
excerpt: "A 600-task benchmark for measuring whether authorization survives delegation across single-agent, centralized, and decentralized coordination. <b>Under review at AAAI 2027; submitted to arXiv.</b>"
collection: portfolio
order: 1
authors: '<strong>Zhuoning Xu</strong><sup>1,*</sup>, Xiucheng Zhang<sup>1,*</sup>, Hanjun Luo<sup>1,2,*</sup>, Yingbin Jin<sup>3</sup>, Yinpeng Dong<sup>4,†</sup>, and Hanan Salam<sup>1,2</sup>'
affiliations: '<sup>1</sup> New York University; <sup>2</sup> New York University Abu Dhabi; <sup>3</sup> The Hong Kong Polytechnic University; <sup>4</sup> Tsinghua University'
author_note: '<sup>*</sup> Equal contribution; <sup>†</sup> Corresponding author.'
---

**2026 · Under review at AAAI 2027; submitted to arXiv** ·
[Code](https://github.com/ZhuoningXu/MasDrift)

MasDrift formulates authorization preservation as a property that must survive
delegation rather than be checked locally at each agent. Its deliberately benign
threat model excludes prompt injection and malicious agents, isolating authorization
drift as an endogenous failure of decomposition and hand-off.

- Designed a **600-task benchmark across eight productivity domains**, a parameterized
  coordination runner, and trace-level evaluators for unauthorized action,
  over-disclosure, and constraint loss with lost-at-hop localization.
- Combined deterministic evaluation rules with a human-calibrated LLM judge across
  single-agent, centralized, and decentralized coordination.
- Proposed a **source-anchored authorization defense** that revalidates every pending
  tool call against the original user request, suppressing unauthorized actions
  across model configurations at negligible completion cost.
