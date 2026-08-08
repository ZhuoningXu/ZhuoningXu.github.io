---
title: "VLHSA: Vision-Language Hierarchical Semantic Alignment for Jigsaw Puzzle Solving with Eroded Gaps (Student Abstract)"
collection: publications
category: conferences
permalink: /publication/2026-vlhsa-jigsaw
excerpt: 'A vision-language framework combining Vision Mamba and BLIP with hierarchical semantic alignment, InfoNCE contrastive learning, and Hungarian matching for jigsaw puzzles with eroded gaps.'
date: 2026-01-01
venue: 'Proceedings of the AAAI Conference on Artificial Intelligence (AAAI 2026), Student Abstract and Poster Program'
paperurl: 'https://arxiv.org/abs/2509.25202'
authors: '<strong>Zhuoning Xu</strong><sup>1</sup> and Xinyan Liu<sup>1</sup>'
affiliations: '<sup>1</sup> The Hong Kong Polytechnic University'
---
Jigsaw puzzle solving requires understanding both local fragment details and global
spatial relationships. We introduce textual descriptions as global semantic anchors
for resolving patch-level ambiguity in challenging **eroded-gap** puzzles.

The framework extracts visual and text features with **Vision Mamba and BLIP** and
aligns cross-modal representations at both patch and image levels using InfoNCE
contrastive loss. Hungarian matching then produces the optimal permutation
assignment. Ablations over local and global alignment branches demonstrate
significant permutation-accuracy gains over pure-vision baselines.

Links:
[arXiv:2509.25202](https://arxiv.org/abs/2509.25202) ·
[DOI: 10.1609/aaai.v40i48.42244](https://doi.org/10.1609/aaai.v40i48.42244)
