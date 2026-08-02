---
title: "MasDrift: Authorization Preservation Across Multi-Agent Architectures"
excerpt: "A 600-task benchmark for measuring task completion and authorization preservation across single-agent, centralized, and decentralized coordination. <b>Preprint; arXiv forthcoming.</b>"
collection: portfolio
authors: '<strong>Zhuoning Xu</strong><sup>1,*</sup>, Xiucheng Zhang<sup>1,*</sup>, Hanjun Luo<sup>1,2,*</sup>, Yingbin Jin<sup>3</sup>, Yinpeng Dong<sup>4,†</sup>, and Hanan Salam<sup>1,2</sup>'
affiliations: '<sup>1</sup> New York University; <sup>2</sup> New York University Abu Dhabi; <sup>3</sup> The Hong Kong Polytechnic University; <sup>4</sup> Tsinghua University'
author_note: '<sup>*</sup> Equal contribution; <sup>†</sup> Corresponding author.'
---

**2026 · Preprint; arXiv posting forthcoming** ·
[Code](https://github.com/ZhuoningXu/MasDrift)

MasDrift benchmarks whether multi-agent systems preserve the authorization boundaries
of the original user request while completing delegated work. It contains **600
benign productivity tasks across eight domains**, each pairing required work with
reserved actions.

- Compares single-agent, centralized, and decentralized coordination while varying
  hierarchy depth and peer width.
- Measures both task completion and unauthorized actions, exposing a centralization
  tradeoff that widens with hierarchy depth.
- Evaluates request re-anchoring and delegation-chain policy propagation as defenses.
