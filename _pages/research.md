---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My goal is to make robot manipulation more reliable outside a fixed training distribution. I study how policies can acquire physical priors from large-scale data, learn from their own action outcomes, and improve through closed-loop execution on real hardware.

## Interaction-driven adaptation

[Zeva](/publication/zeva/) studies how a frozen policy can adapt without gradient updates. It encodes executed actions and observed state changes as causal interaction signals, then retrieves relevant experience from a dual-timescale memory to guide later actions. On RoboCasa365-Atomic5, it reached **76.8% average success**; in a separate repeated-attempt evaluation, cumulative success rose from **26% on the first attempt to 73% within four attempts**.

## Learning from human video

[Zeva-Ego](/publication/zeva-ego/) uses an action-centric encoder to derive training signals from egocentric video for VLA mid-training. Scaling the video data to **10,000 hours** raised RoboTwin success from **63.8% to 75.3%**. Interaction memory then supports parameter-free adaptation across repeated attempts.

## Closed-loop agents and real robots

[Zetta](/publication/zetta/) combines a frozen base policy with runtime critics and recovery skills that evolve through execution, rollout analysis, and validation. I worked on the base policy and real-robot deployment. At AIR, I also worked across data collection, training, calibration, control interfaces, inference, and evaluation on robot arms and a dexterous hand.
