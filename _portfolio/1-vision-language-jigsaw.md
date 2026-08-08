---
title: "VLHSA: Vision–Language Jigsaw Puzzle Solving with Eroded Gaps"
excerpt: "A multimodal (Mamba-based) framework that uses text as semantic guidance to solve jigsaw puzzles with eroded gaps — +14.2 pp piece accuracy. <b>AAAI-26 Student Abstract.</b>"
collection: portfolio
order: 4
authors: '<strong>Zhuoning Xu</strong><sup>1</sup> and Xinyan Liu<sup>1</sup>'
affiliations: '<sup>1</sup> The Hong Kong Polytechnic University'
---

**2025 · Accepted to the AAAI-26 Student Abstract Program**
· [arXiv:2509.25202](https://arxiv.org/abs/2509.25202)
· [DOI](https://doi.org/10.1609/aaai.v40i48.42244)

A vision-language framework for solving jigsaw puzzles with **eroded gaps**, where
textual descriptions act as global semantic anchors for resolving patch-level
ambiguity.

- Extracts visual and text features with **Vision Mamba and BLIP**, aligning their
  representations at both patch and image levels using InfoNCE contrastive loss.
- Uses **Hungarian matching** for optimal permutation assignment.
- Led the full research pipeline and ablations over local and global alignment
  branches, demonstrating significant permutation-accuracy gains over pure-vision
  baselines.
