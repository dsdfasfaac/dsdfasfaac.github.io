---
title: "Zeva: In-Context Causal Learning for Generalizable Embodied Manipulation"
collection: publications
permalink: /publication/zeva/
year: 2026
order: 1
venue: "arXiv preprint"
contribution: "Co-first author (listed first)"
authors: "Fu Chen, Xin Ding, Bingjia Huang, Xiangyu Li, Mingju Wang, Jiawei He, Kun Li, Wei Sun, Yunxin Liu, Hao Wu, Ting Cao"
paperurl: "https://arxiv.org/abs/2608.30880"
projecturl: "https://air-embodied-brain.github.io/Zeva/"
excerpt: "A frozen robot policy learns from its own action-effect feedback through causal interaction signals and dual-timescale memory."
---

**Authors:** <strong>Fu Chen</strong><sup>*</sup>, Xin Ding<sup>*</sup>, Bingjia Huang, Xiangyu Li, Mingju Wang, Jiawei He, Kun Li, Wei Sun, Yunxin Liu, Hao Wu, Ting Cao.<br>
*Equal contribution; Fu Chen is listed first.*

**Research question.** Can a robot adapt to unfamiliar physical conditions using its own interaction experience while keeping the policy weights fixed?

**Approach.** Zeva encodes an executed action and its observed state change into a causal interaction signal. A brief interaction trace captures recent dynamics, while a persistent memory carries useful evidence across attempts. Retrieved signals condition subsequent action generation without test-time gradient updates.

**Results.** On RoboCasa365-Atomic5, Zeva achieved **76.8% average success**. In a separate repeated-attempt setting on that benchmark, cumulative success increased from **26% on the first attempt to 73% within four attempts**. The paper also reports real-robot experiments and cross-task reuse of interaction experience.

[Read the paper](https://arxiv.org/abs/2608.30880) · [Project page](https://air-embodied-brain.github.io/Zeva/)
