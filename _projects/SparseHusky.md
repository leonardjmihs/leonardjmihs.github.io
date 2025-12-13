---
layout: page
title: Sparse Actuator Control of Aerial Legged Robot
description: TLDR -- Used Hiearchical QP's to keep redundancy in acutators via sparsity 
img: assets/img/SparseHusky/cover-wair.png
importance: 1
category: Class 
related_publications: false
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/SparseHusky/cover-wair.png" title="Problem Statement" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<strong> Abstract</strong>:
Multimodal Aerial legged robots create redundancy in actuators with the addition of thrusters. 
This paper introduces a novel optimization framework for actuator usage for a multimodal quadrupedal robot equipped with thrusters, with a focus on sparsity to enhance efficiency and adaptability. 
The framework combines hierarchical quadratic programming (QP) to prioritize task execution while satisfying constraints like friction and torque limits, with sparse optimization to sparsify the number of actuator's used.
Thus, the framework dynamically reallocates actuation to balance the robot under disturbances, demonstrating the advantages of sparsity-aware optimization. By minimizing redundant actuator engagement and leveraging thrusters for supplementary force generation, the proposed method enhances flexibility and resource efficiency in multi-actuator robotic systems. This work provides a robust foundation for scalable and efficient control strategies in complex robotic platforms, advancing the capabilities of multi-legged robots in dynamic and unpredictable environments.

<div class="row justify-content-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid loading="eager"
            path="assets/img/SparseHusky/husky_peeing.jpg"
            title="example image"
            class="img-fluid w-100 rounded z-depth-1"
        %}
    </div>
</div>