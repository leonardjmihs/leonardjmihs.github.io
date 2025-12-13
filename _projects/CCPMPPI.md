---
layout: page
title: Contingency Planning
description: TLDR -- Backup Planning using Sampling-MPC
img: assets/img/ContingencyPlanningMPPI/problem_statement.png
importance: 1
category: Research
related_publications: true
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/ContingencyPlanningMPPI/problem_statement.png" title="Problem Statement" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/ContingencyPlanningMPPI/branching_scaled.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
{% cite jung2025contingency %} <strong> Abstract</strong>:
For safety, autonomous systems must be able to consider sudden changes and enact contingency
plans appropriately. State-of-the-art methods currently find trajectories that balance between nominal and contingency behavior, or plan for a singular contingency plan; however, this does not guarantee that the resulting plan is safe for all time. To address this research gap, this paper presents
Contingency-MPPI, a data-driven optimization-based strategy that embeds contingency planning
inside a nominal planner. By learning to approximate the optimal contingency-constrained control
sequence with adaptive importance sampling, the proposed method’s sampling efficiency is further
improved with initializations from a lightweight path planner and trajectory optimizer. Finally, we
present simulated and hardware experiments demonstrating our algorithm generating nominal and
contingency plans in real time on a mobile robots

<strong> Code: </strong> <a href="https://github.com/neu-autonomy/Contingency-MPPI"> https://github.com/neu-autonomy/Contingency-MPPI<a>