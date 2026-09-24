---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume/
---

## Education

**University of Science and Technology of China (USTC)** · Master's student, Electronic and Information Engineering<br>
*Sep 2025 – Jun 2028 (expected)*

**Hunan University** · B.Eng., Electronic and Information Engineering<br>
*Sep 2021 – Jun 2025*

## Research and engineering experience

**Research Intern, Institute for AI Industry Research (AIR), Tsinghua University**<br>
*Jun 2026 – Sep 2026*<br>
Research on VLA and world-action models, interaction-driven adaptation, and robot manipulation. Built and evaluated the data-to-deployment pipeline on robot arms and a dexterous hand. Designed a Real2Sim2Real workflow for simulation rollouts, policy optimization, and real-robot validation.

**Research Intern, Eastern Institute of Technology, Ningbo**<br>
*Jun 2025 – Sep 2025*<br>
Conducted Franka manipulation experiments and reproduced the Seer predictive inverse-dynamics model, including training and inference for multimodal encoding, future visual prediction, and action prediction.

**Motion Control Engineer, Gaoqing Electromechanical (高擎机电)**<br>
*Jan 2025 – Apr 2025*<br>
Developed a C++ SDK for robot walking speed and mode switching. Adapted ModelBasedFootstepPlanning to a 12-DoF biped, trained in simulation, and validated sim-to-sim and sim-to-real deployment with MuJoCo and RKNN.

## Publications

{% assign papers = site.publications | sort: "order" %}
{% for paper in papers %}
- **{{ paper.title }}** · {{ paper.venue }}, {{ paper.year }} · {{ paper.contribution }}. [Paper]({{ paper.paperurl }}) · [Project]({{ paper.projecturl }})
{% endfor %}

## Technical skills

- **Robot learning:** vision-language-action models, world-action models, test-time adaptation, reinforcement learning.
- **Training and deployment:** PyTorch, Transformers, distributed training, MuJoCo, Isaac Sim, RKNN, Real2Sim2Real.
- **Development:** Python, C++, ROS/ROS 2, real-robot manipulation systems.

## Leadership and open source

**RoboMaster Yuelu Team, Hunan University** · Control group leader and team captain, 2023. Led a [modular embedded control framework](https://gitee.com/hnuyuelurm/basic_framework) with 400+ stars, recognized with the RoboMaster 2023 Open Source Award (third prize). Developed a wheel-legged balancing infantry control system using Kalman filtering and LQR; the team won first prize in the 2023 RoboMaster University League infantry robot competition.
