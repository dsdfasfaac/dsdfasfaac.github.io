---
layout: home
permalink: /
title: "Fu Chen"
redirect_from:
  - /about/
  - /about.html
  - /publications/
  - /research/
  - /cv/
  - /resume/
  - /publication/zeva/
  - /publication/zeva-ego/
  - /publication/zetta/
---

I am a master's student in Electronic and Information Engineering at the **University of Science and Technology of China (USTC)**. I work on robot learning and embodied intelligence, with an emphasis on making manipulation policies adapt to physical interaction and work reliably on real robots.

My work covers the full experimental pipeline: robot and camera calibration, data collection, simulation, model training, inference, control interfaces, and real-robot evaluation. At the **Institute for AI Industry Research (AIR), Tsinghua University**, I worked with robot arms and a dexterous hand on the Zeva, Zeva-Ego, and Zetta projects.

## Publications

<article class="publication">
  <div class="publication__text">
    <div class="publication__heading"><span>2026</span><h3><a href="https://air-embodied-brain.github.io/Zeva/">Zeva: In-Context Causal Learning for Generalizable Embodied Manipulation</a></h3></div>
    <p class="publication__authors"><strong>Fu Chen*</strong>, Xin Ding*, Bingjia Huang, Xiangyu Li, Mingju Wang, Jiawei He, Kun Li, Wei Sun, Yunxin Liu, Hao Wu, Ting Cao · <em>Co-first author, listed first</em></p>
    <p>Zeva encodes executed actions and observed state changes as causal interaction signals. A dual-timescale memory retrieves useful experience to adapt a frozen policy without gradient updates. It reached <strong>76.8% average success</strong> on RoboCasa365-Atomic5; in a separate repeated-attempt evaluation, cumulative success rose from <strong>26% on the first attempt to 73% within four attempts</strong>.</p>
    <p class="publication__links"><a href="https://air-embodied-brain.github.io/Zeva/">Project page →</a></p>
  </div>
  <a class="publication__image" href="https://air-embodied-brain.github.io/Zeva/" aria-label="View the Zeva project page"><img src="/images/publications/zeva.png" alt="Zeva overview: causal interaction extraction, memory, and manipulation results" width="2784" height="1766" loading="lazy" decoding="async"></a>
</article>

<article class="publication">
  <div class="publication__text">
    <div class="publication__heading"><span>2026</span><h3><a href="https://air-embodied-brain.github.io/Zeva-Ego/">Zeva-Ego: Egocentric Mid-Training with In-Context Causal Learning for Robot Manipulation</a></h3></div>
    <p class="publication__authors">Bingjia Huang*, Xin Ding, <strong>Fu Chen*</strong>, Kun Li, Wei Sun, Hao Wu, Yunxin Liu, Ting Cao · <em>Co-first author</em></p>
    <p>Zeva-Ego turns egocentric video into action-centered supervision for VLA mid-training, then uses interaction feedback for parameter-free adaptation at deployment. Scaling to <strong>10,000 hours</strong> of video improved RoboTwin success from <strong>63.8% to 75.3%</strong>; repeated-attempt success rose from <strong>58% to 89%</strong>.</p>
    <p class="publication__links"><a href="https://air-embodied-brain.github.io/Zeva-Ego/">Project page →</a></p>
  </div>
  <a class="publication__image" href="https://air-embodied-brain.github.io/Zeva-Ego/" aria-label="View the Zeva-Ego project page"><img src="/images/publications/zeva-ego.png" alt="Zeva-Ego overview: egocentric data, VLA mid-training, and robot results" width="2555" height="1290" loading="lazy" decoding="async"></a>
</article>

<article class="publication">
  <div class="publication__text">
    <div class="publication__heading"><span>2026</span><h3><a href="https://air-embodied-brain.github.io/zetta/">Zetta ζ: An Efficient Closed-Loop Embodied Harness for Self-Evolving Physical Intelligence</a></h3></div>
    <p class="publication__authors">Xin Ding, Liang Mi, Mingzhe Huang, Zixuan Wang, Chao Zhang, Zixu Hao, <strong>Fu Chen</strong>, Xiangyu Li, Yikai Zheng, Yaoyu Guo, Weijun Wang, Kun Li, Hao Wu, Yunxin Liu, Ting Cao</p>
    <p>Zetta keeps a base policy frozen while runtime critics detect failures and recovery skills support continued execution. Rollout analysis and validation update those skills over time. The paper reports <strong>90.8% success on LIBERO-Pro</strong>, <strong>93.6% on RoboCasa</strong>, and an <strong>11.1× inference speedup</strong>. I worked on the base policy and implemented real-robot deployment.</p>
    <p class="publication__links"><a href="https://air-embodied-brain.github.io/zetta/">Project page →</a></p>
  </div>
  <a class="publication__image" href="https://air-embodied-brain.github.io/zetta/" aria-label="View the Zetta project page"><img src="/images/publications/zetta.png" alt="Zetta overview: closed-loop critics, recovery skills, and rollout results" width="6084" height="5124" loading="lazy" decoding="async"></a>
</article>

<p class="note">* Equal contribution, as indicated in the papers.</p>

## Experience

<div class="entry entry--with-logo">
  <div class="entry__text">
    <div class="entry__heading"><h3>Research Intern · AIR, Tsinghua University</h3><span>Jun–Sep 2026</span></div>
    <p>Worked on VLA and world-action models for robot manipulation across data collection, training, inference, and real-robot evaluation. Integrated robot arms and a dexterous hand, including calibration and control interfaces. Built a Real2Sim2Real workflow for simulation rollouts, policy training, and transfer back to physical robots.</p>
  </div>
  <div class="entry__logo entry__logo--air"><img src="{{ '/images/organizations/air.png' | relative_url }}" alt="AIR, Tsinghua University logo" loading="lazy"></div>
</div>

<div class="entry entry--with-logo">
  <div class="entry__text">
    <div class="entry__heading"><h3>Research Intern · Eastern Institute of Technology, Ningbo</h3><span>Jun–Sep 2025</span></div>
    <p>Ran Franka manipulation experiments and reproduced <a href="https://nimolty.github.io/Seer/">Seer</a>, a predictive inverse-dynamics model, including its training and inference pipeline.</p>
  </div>
  <div class="entry__logo entry__logo--eit"><img src="{{ '/images/organizations/eit.png' | relative_url }}" alt="Eastern Institute of Technology, Ningbo logo" loading="lazy"></div>
</div>

<div class="entry entry--with-logo">
  <div class="entry__text">
    <div class="entry__heading"><h3>Motion Control Engineer · Gaoqing Electromechanical</h3><span>Jan–Apr 2025</span></div>
    <p>Developed a C++ SDK for robot walking speed and mode switching. Adapted ModelBasedFootstepPlanning to a 12-DoF biped, trained in simulation, and validated sim-to-sim and sim-to-real deployment with MuJoCo and RKNN.</p>
  </div>
  <div class="entry__logo"><img src="{{ '/images/organizations/gao.png' | relative_url }}" alt="Gaoqing Electromechanical logo" loading="lazy"></div>
</div>

## Education

<div class="entry entry--compact entry--with-logo">
  <div class="entry__text">
    <div class="entry__heading"><h3>University of Science and Technology of China</h3><span>2025–2028 (expected)</span></div>
    <p>M.Eng., Electronic and Information Engineering</p>
  </div>
  <div class="entry__logo entry__logo--seal"><img src="{{ '/images/organizations/ustc.jpg' | relative_url }}" alt="University of Science and Technology of China emblem" loading="lazy"></div>
</div>

<div class="entry entry--compact entry--with-logo">
  <div class="entry__text">
    <div class="entry__heading"><h3>Hunan University</h3><span>2021–2025</span></div>
    <p>B.Eng., Electronic and Information Engineering</p>
  </div>
  <div class="entry__logo entry__logo--seal entry__logo--hnu"><img src="{{ '/images/organizations/hnu.png' | relative_url }}" alt="Hunan University emblem" loading="lazy"></div>
</div>

## Selected engineering work

<div class="entry">
  <div class="entry__heading"><h3>RoboMaster Yuelu Team · Control group leader and team captain</h3><span>2023</span></div>
  <p>Led a <a href="https://gitee.com/hnuyuelurm/basic_framework">modular embedded control framework</a> with 400+ stars, recognized with the RoboMaster 2023 Open Source Award (third prize). Developed a wheel-legged balancing infantry control system using Kalman filtering and LQR; the team won first prize in the 2023 RoboMaster University League infantry robot competition.</p>
</div>

## Skills

<p class="skills"><strong>Programming:</strong> Python, C++ · <strong>Robot systems:</strong> ROS/ROS 2, MuJoCo, Isaac Sim, RKNN · <strong>Machine learning:</strong> PyTorch, Transformers, distributed training, VLA and world-action models</p>
