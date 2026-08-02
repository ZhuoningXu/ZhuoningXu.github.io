---
title: "MisPlan: When Plans Hurt Coding Agents"
collection: publications
category: preprints
permalink: /publication/2026-misplan-coding-agent-plans
excerpt: 'A diagnostic benchmark of coding-agent plan modes that isolates five plan-content failures and shows that goal-scope errors can erase the benefits of planning.'
date: 2026-07-21
status: 'AAAI 2027 Conference Submission'
paperurl: 'https://openreview.net/forum?id=EYL854kJNj'
authors: '<a href="https://openreview.net/profile?id=~Hanjun_Luo1">Hanjun Luo</a>, <a href="https://openreview.net/profile?id=~Zhimu_Huang1">Zhimu Huang</a>, <a href="https://openreview.net/profile?id=~Alyssa_Wu1">Alyssa Wu</a>, <a href="https://openreview.net/profile?id=~Xiucheng_Zhang1">Xiucheng Zhang</a>, <strong><a href="https://openreview.net/profile?id=~Zhuoning_Xu3">Zhuoning Xu</a></strong>, et al.'
affiliations: 'New York University; New York University Abu Dhabi'
author_note: 'Corresponding author: <a href="https://openreview.net/profile?id=~Hanan_Salam1">Hanan Salam</a> (New York University Abu Dhabi). Full author list available on OpenReview.'
---

Abstract
======

Coding agents increasingly rely on plan modes, but erroneous plans can harm
execution. Prior work establishes that plans can hurt but does not decompose the
effect, leaving developers without criteria for which plan aspects demand the
highest fidelity. We introduce **MisPlan**, a diagnostic benchmark that measures how
specific plan-content failures change coding-agent execution.

Grounded in an analysis of 125,275 real coding-agent sessions, we derive a five-type
failure taxonomy and construct 193 human-validated repository tasks, each evaluated
under seven paired conditions: no plan, one correct plan, and five defective
variants. Based on extensive experiments across six models on a unified harness and
three native coding agents, we find a pronounced asymmetry. A correct plan raises
resolve rates by 3 to 14 percentage points, yet a single goal-scope error causes a
25-percentage-point drop and is the most prevalent failure type in practice. As a
result, the overall expected gain of plan mode can turn negative.

In contrast, errors in implementation details produce drops of only 1 to 6
percentage points. These results reveal that the bottleneck of plan mode is not
insufficient elaboration but misaligned goal framing, motivating
clarification-centric design for the plan mode of coding agents.

Links
======

**Paper:** [OpenReview](https://openreview.net/forum?id=EYL854kJNj)
