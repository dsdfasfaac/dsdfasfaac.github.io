---
permalink: /
title: "Fu Chen"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<p class="home-kicker">EMBODIED INTELLIGENCE · ROBOT LEARNING</p>

I am a master's student in Electronic and Information Engineering at the **University of Science and Technology of China (USTC)**. My research focuses on robots that learn from physical interaction: vision-language-action models, world-action models, test-time adaptation, and reliable closed-loop manipulation.

I work across the full research pipeline, from data collection and model training to simulation, deployment, and evaluation on real robots. As a research intern at the **Institute for AI Industry Research (AIR), Tsinghua University**, I worked with robot arms and a dexterous hand and contributed to the [Zeva](/publication/zeva/), [Zeva-Ego](/publication/zeva-ego/), and [Zetta](/publication/zetta/) projects.

<div class="home-actions">
  <a class="btn btn--primary" href="/publications/">View publications</a>
  <a class="btn" href="/research/">Explore research</a>
  <a class="btn" href="mailto:chenfu0603@mail.ustc.edu.cn">Email me</a>
</div>

## Research directions

<div class="research-grid">
  <div class="research-card">
    <span class="research-card__index">01</span>
    <h3>Learning from interaction</h3>
    <p>Use action-effect feedback and persistent memory to adapt a frozen robot policy during deployment.</p>
    <a href="/publication/zeva/">Zeva →</a>
  </div>
  <div class="research-card">
    <span class="research-card__index">02</span>
    <h3>Learning from egocentric video</h3>
    <p>Turn large-scale human first-person video into action-centered supervision for robot learning.</p>
    <a href="/publication/zeva-ego/">Zeva-Ego →</a>
  </div>
  <div class="research-card">
    <span class="research-card__index">03</span>
    <h3>Closing the loop</h3>
    <p>Connect foundation policies, runtime critics, recovery skills, and real-robot deployment.</p>
    <a href="/publication/zetta/">Zetta →</a>
  </div>
</div>

## Recent publications

{% assign selected_papers = site.publications | sort: "order" %}
{% for paper in selected_papers %}
<div class="paper-row">
  <div class="paper-row__meta">{{ paper.year }} · {{ paper.venue }}</div>
  <h3><a href="{{ paper.url }}">{{ paper.title }}</a></h3>
  <p>{{ paper.excerpt }}</p>
  <div class="paper-row__links"><a href="{{ paper.paperurl }}">Paper</a><a href="{{ paper.projecturl }}">Project page</a></div>
</div>
{% endfor %}

<p class="section-more"><a href="/publications/">All publications →</a></p>
