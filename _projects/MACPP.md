---
layout: page
title: MAC++ 
description: TLDR -- Efficient Graph Sparisification for SLAM
img: assets/img/MACPP/Title.png
importance: 1
category: Research
related_publications: true
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/MACPP/Title.png" title="Problem Statement" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
{% cite jung2025practical %} <strong> Abstract</strong>:
Long-term state estimation over graphs remains challenging as current graph estimation methods scale poorly on large, long-term graphs. To address this, our work advances a current state-of-the-art graph sparsification algorithm, maximizing algebraic connectivity (MAC). MAC is a sparsification method that preserves estimation performance by maximizing the algebraic connectivity, a spectral graph property that is directly connected to the estimation error. Unfortunately, MAC remains computationally prohibitive for online use and requires users to manually pre-specify a connectivity-preserving edge set. Our contributions close these gaps along three complementary fronts: we develop a specialized solver for algebraic connectivity that yields an average 2x runtime speedup; we investigate advanced step size strategies for MAC’s optimization procedure to enhance both convergence speed and solution quality; and we propose automatic schemes that guarantee graph connectivity without requiring manual specification of edges. Together, these contributions make MAC more scalable, reliable, and suitable for real-time estimation applications.
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/MACPP/Flow.png" title="Flow" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
