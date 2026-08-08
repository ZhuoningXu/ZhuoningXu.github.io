---
title: "Reconcile-then-Resume: Proportionate Mid-Run Steering for Coding Agents"
collection: publications
category: manuscripts
permalink: /publication/2026-reconcile-then-resume
excerpt: 'A runtime framework for reconciling new user instructions against in-progress coding-agent state while proportionately preserving, revising, or reverting prior work.'
date: 2026-08-08
status: 'Manuscript in preparation for ICLR 2027'
authors: '<strong>Zhuoning Xu</strong> (first author)'
affiliations: 'New York University; New York University Abu Dhabi'
author_note: 'Advisor: Hanan Salam (New York University Abu Dhabi).'
---

Reconcile-then-Resume formalizes mid-run steering of coding agents as a
proportional-integration problem over aligned, partial-revision, and conflicting
user instructions. The evaluation pipeline is based on SWE-bench and measures
normalized integration loss, overhead, and behavior retention.

The runtime framework reconciles new instructions against in-progress agent state
and selectively preserves, revises, or reverts prior work. It is evaluated in
controlled experiments and through Codex's native steering interface.
