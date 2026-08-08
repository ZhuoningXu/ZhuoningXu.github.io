---
title: "Reconcile-then-Resume: Proportionate Mid-Run Steering for Coding Agents"
excerpt: "A runtime framework that reconciles new user instructions against in-progress coding-agent state and selectively preserves, revises, or reverts prior work. <b>Manuscript in preparation for ICLR 2027.</b>"
collection: portfolio
order: 3
authors: '<strong>Zhuoning Xu</strong> (first author)'
affiliations: 'New York University; New York University Abu Dhabi'
author_note: 'Advisor: Hanan Salam (New York University Abu Dhabi).'
---

**2026 · Manuscript in preparation for ICLR 2027**

Reconcile-then-Resume formalizes mid-run steering of coding agents as a
proportional-integration problem over aligned, partial-revision, and conflicting
user instructions.

- Built a **SWE-bench-based evaluation pipeline** with normalized integration-loss,
  overhead, and behavior-retention metrics.
- Proposed a runtime framework that reconciles new instructions against in-progress
  agent state and selectively preserves, revises, or reverts prior work.
- Validated the framework in controlled experiments and through **Codex's native
  steering interface**.
