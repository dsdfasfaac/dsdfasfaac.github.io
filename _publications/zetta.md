---
title: "Zetta ζ: An Efficient Closed-Loop Embodied Harness for Self-Evolving Physical Intelligence"
collection: publications
permalink: /publication/zetta/
year: 2026
order: 3
venue: "arXiv preprint"
contribution: "Co-author; base policy and real-robot deployment"
authors: "Xin Ding, Liang Mi, Mingzhe Huang, Zixuan Wang, Chao Zhang, Zixu Hao, Fu Chen, Xiangyu Li, Yikai Zheng, Yaoyu Guo, Weijun Wang, Kun Li, Hao Wu, Yunxin Liu, Ting Cao"
paperurl: "https://arxiv.org/abs/2608.16590"
projecturl: "https://air-embodied-brain.github.io/zetta/"
excerpt: "A closed-loop embodied agent evolves runtime critics and recovery skills around a frozen base policy."
---

**Authors:** Xin Ding, Liang Mi, Mingzhe Huang, Zixuan Wang, Chao Zhang, Zixu Hao, **Fu Chen**, Xiangyu Li, Yikai Zheng, Yaoyu Guo, Weijun Wang, Kun Li, Hao Wu, Yunxin Liu, Ting Cao.

**My contribution.** I worked on the base policy and implemented real-robot deployment.

**Approach.** Zetta is a multi-timescale closed-loop method. It keeps the base policy frozen, monitors execution with runtime critics, invokes recovery skills when needed, and updates verified skills using rollout-level analysis and validation gates.

**Results.** The paper reports **90.8% success on LIBERO-Pro** and **93.6% on RoboCasa**, together with an **11.1× inference speedup**.

[Read the paper](https://arxiv.org/abs/2608.16590) · [Project page](https://air-embodied-brain.github.io/zetta/)
