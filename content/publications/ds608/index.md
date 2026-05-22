---
title: "Tracing the Roots: Trust Region Policy Optimization"

authors:
  - Anshu Arora, Pranay Sharma

date: "2026-04-30"

publication_types: ["Report"]

publication: "Unpublished"

abstract: |
  This report examines the origins of the celebrated Trust Region Policy Optimization (TRPO) framework, an application of natural gradient methods in reinforcement learning. While the standard objective of an agent is to maximize cumulative reward, traditional policy gradient approaches are often highly sensitive to step size selection because gradients are typically computed in the parameter space rather than the actual underlying policy space. TRPO addresses this instability by introducing a ‘trust region’ constraint based on the Kullback-Leibler divergence between different policies. This ensures that each policy update remains within a safe distance of the previous iteration. By leveraging the Fisher Information Matrix as an invariant metric to guide the natural gradient, the framework provides a robust optimization strategy that guarantees monotonic improvement of the policy.

summary: |
  This report examins the origins Trust Region Policy Optimization, which is of paramount importance in modern reinforcement learning.

tags:
  - Reinforcement Learning
  - Policy Gradient


links:
  - name: PDF
    url: /uploads/DS_608-TRPO.pdf

# Optional:
# url_pdf:
# url_code:
# url_dataset:
# url_slides:

# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  #caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

featured: false
---