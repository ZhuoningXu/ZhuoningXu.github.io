---
title: "MasDrift: Benchmarking Authorization Preservation Across Multi-Agent Architectures"
collection: publications
category: preprints
permalink: /publication/2026-masdrift-authorization-preservation
excerpt: 'A benchmark of 600 benign productivity tasks across eight domains for measuring how well single-agent, centralized, and decentralized multi-agent architectures preserve user authorization while completing delegated work.'
date: 2026-08-02
status: 'Preprint — arXiv posting forthcoming'
citation: 'Zhuoning Xu, Xiucheng Zhang, Hanjun Luo, Yingbin Jin, Yinpeng Dong, and Hanan Salam. (2026). &quot;MasDrift: Benchmarking Authorization Preservation Across Multi-Agent Architectures.&quot; Preprint.'
---

**Authors:** Zhuoning Xu<sup>1,*</sup>, Xiucheng Zhang<sup>1,*</sup>,
Hanjun Luo<sup>1,2,*</sup>, Yingbin Jin<sup>3</sup>,
Yinpeng Dong<sup>4,†</sup>, Hanan Salam<sup>1,2</sup>

<sup>*</sup> Equal contribution. <sup>†</sup> Corresponding author.

**Affiliations:**

1. New York University
2. New York University Abu Dhabi
3. The Hong Kong Polytechnic University
4. Tsinghua University

Abstract
======

Multi-agent systems (MAS) decompose long-horizon tasks across supervisors and
subagents, but delegated goals do not necessarily carry their original authorization
boundaries. Existing safety benchmarks mainly study adversarial compromise, while
work on constraint drift lacks controlled architecture-level evaluation.

We introduce **MasDrift**, a benchmark of 600 benign productivity tasks across eight
domains. Each task pairs required work with reserved actions. MasDrift compares
single-agent, centralized, and decentralized coordination while varying hierarchy
depth and peer width, measuring task completion and authorization preservation.
Across generic multi-agent conditions, centralized hierarchies achieve 93.9–98.6%
task completion versus 85.7–87.0% for peer networks, while unauthorized actions
occur in 2.7–19.8% of tasks versus 0.6–0.8%, a gap that widens with hierarchy depth.

We further compare two defenses that differ in where authorization evidence resides.
One re-anchors every pending call to the original user request. The other carries an
attenuated policy along the delegation chain. Re-anchoring reduces unauthorized
actions in every model configuration we evaluate, at a cost of 1.6 points of pooled
completion. Chain propagation blocks required work instead, forfeiting up to 36.3
points. A heterogeneous case study confirms that the failure follows from
coordination rather than model strength. MasDrift exposes a centralization tradeoff
and makes authorization preservation a measurable property of MAS design.

Links
======

**Paper:** arXiv link forthcoming

**Code:** [github.com/ZhuoningXu/MasDrift](https://github.com/ZhuoningXu/MasDrift)
