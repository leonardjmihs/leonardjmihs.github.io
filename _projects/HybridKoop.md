---
layout: page
title: Hybrid Koopman 
description: TLDR -- Combining SDP and Learning for Koopman Operator Identification
img: assets/img/HybridKoop/Arc_fig.png
importance: 1
category: Research
related_publications: true
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/HybridKoop/Arc_fig.png" title="Problem Statement" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
{% cite estornell2025hybrid %} <strong> Abstract</strong>:
Koopman analysis of a general dynamics system provides a linear Koopman operator and an embedded eigenfunction space, enabling the application of standard techniques from linear analysis. However, in practice, deriving exact operators and mappings for the observable space is intractable, and deriving an approximation or expressive subset of these functions is challenging. Programmatic methods often rely on system-specific parameters and may scale poorly in both time and space, while learning-based approaches depend heavily on difficult-to-know hyperparameters, such as the dimension of the observable space. To address the limitations of both methods, we propose a hybrid framework that uses semidefinite programming to find a representation of the linear operator, then learns an approximate mapping into and out of the space that the operator propagates. This approach enables efficient learning of the operator and explicit mappings while reducing the need for specifying the unknown structure ahead of time. 

<div class="row justify-content-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid loading="eager"
            path="assets/img/HybridKoop/Lorenz_MSE.png"
            title="example image"
            class="img-fluid w-100 rounded z-depth-1"
        %}
    </div>
</div>



<div class="caption">
Our framework (W/Pretrain) trains much faster than other methods, and results in an overall lower MSE on multiple different systems, including the Lorenz Oscillator
</div>
<strong> Code: </strong> <a href="https://github.com/neu-autonomy/HybridKoopman"> https://github.com/neu-autonomy/HybridKoopman<a>