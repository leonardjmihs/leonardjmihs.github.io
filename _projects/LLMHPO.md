---
layout: page
title: LLMs for HPO 
description: TLDR -- Combining LLMS and Bayes for Hyperparameter Optimization
img: assets/img/LLMHPO/LLMHPO.png
importance: 1
category: Class 
related_publications: false
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/LLMHPO/LLMHPO.png" title="Problem Statement" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<strong> Abstract</strong>:
A common challenge when training a neural network (NN) is the choice of hyperparameters for the network, e.g., layer count, learning rate, and dropout. We propose combining traditional HPO algorithms with several LLM agents that decide the initialization of the parameter space, exploration of the parameter space, and real-time trial monitoring.

We evaluated several open source LLM models, including Deepseek and LLAMA, with the Optuna Bayesian HPO library.

<div class="row justify-content-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid loading="eager"
            path="assets/img/LLMHPO/optimization_history_best.png"
            title="example image"
            class="img-fluid w-100 rounded z-depth-1"
        %}
    </div>
</div>