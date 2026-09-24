---
title: "Zeva-Ego: Egocentric Mid-Training with In-Context Causal Learning for Robot Manipulation"
collection: publications
permalink: /publication/zeva-ego/
year: 2026
order: 2
venue: "arXiv preprint"
contribution: "Co-first author"
authors: "Bingjia Huang, Xin Ding, Fu Chen, Kun Li, Wei Sun, Hao Wu, Yunxin Liu, Ting Cao"
paperurl: "https://arxiv.org/abs/2609.24411"
projecturl: "https://air-embodied-brain.github.io/Zeva-Ego/"
excerpt: "An action-centric encoder turns egocentric video into VLA mid-training supervision; causal interaction learning supports parameter-free adaptation."
---

**Authors:** Bingjia Huang<sup>*</sup>, Xin Ding, <strong>Fu Chen</strong><sup>*</sup>, Kun Li, Wei Sun, Hao Wu, Yunxin Liu, Ting Cao.<br>
*Equal contribution by the marked authors.*

**Research question.** How can large-scale human first-person video provide physical priors for robot action, and how can the resulting policy keep adapting after deployment?

**Approach.** An Action-Centric Encoder converts egocentric visual transitions into action-centered supervision for VLA mid-training. At deployment, in-context causal learning uses action-effect feedback to adapt the frozen action policy without parameter updates.

**Results.** Scaling egocentric mid-training data to **10,000 hours** improved RoboTwin success from **63.8% to 75.3%**. With accumulated interaction experience, success increased from **58% on the first attempt to 89% on the fourth attempt**.

[Read the paper](https://arxiv.org/abs/2609.24411) · [Project page](https://air-embodied-brain.github.io/Zeva-Ego/)
