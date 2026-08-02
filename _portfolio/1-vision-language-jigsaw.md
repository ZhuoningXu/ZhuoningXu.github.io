---
title: "VLHSA: Vision–Language Jigsaw Puzzle Solving with Eroded Gaps"
excerpt: "A multimodal (Mamba-based) framework that uses text as semantic guidance to solve jigsaw puzzles with eroded gaps — +14.2 pp piece accuracy. <b>AAAI-26 Student Abstract.</b>"
collection: portfolio
authors: '<strong>Zhuoning Xu</strong><sup>1</sup> and Xinyan Liu<sup>1</sup>'
affiliations: '<sup>1</sup> The Hong Kong Polytechnic University'
---

**2025 · Accepted to the AAAI-26 Student Abstract Program**
· [arXiv:2509.25202](https://arxiv.org/abs/2509.25202)
· [DOI](https://doi.org/10.1609/aaai.v40i48.42244)

A vision–language framework for solving jigsaw puzzles with **eroded gaps**, where
visual cues alone (edge matching, coherence) are insufficient and textual context
provides crucial semantic guidance.

- Core contribution: the **Vision-Language Hierarchical Semantic Alignment (VLHSA)**
  module, aligning visual patches with textual descriptions through multi-level
  semantic matching from local tokens to global context.
- Multimodal architecture combining **dual visual encoders (including a Mamba /
  state-space backbone)** with language features for cross-modal reasoning.
- Significantly outperforms state-of-the-art vision-only models across datasets,
  with a **+14.2 percentage-point** gain in piece accuracy; ablations confirm the
  critical role of the VLHSA module.
