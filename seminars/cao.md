---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: seminar
title: "Decoding control: scalable MPC approximation with decision trees"
date: 2025-05-08 2:00pm
author: Yankai Cao
affiliation: University of British Columbia
# zoom: https://mit.zoom.us/j/123456789
---
# Abstract
<div style="text-align: justify;">
Model Predictive Control (MPC) is widely used in the process industry for its superior control performance. However, its real-time computational demands limit implementation in systems with fast dynamics. To address this, we propose an offline approach to approximate MPC control laws using oblique decision trees (DTs) with linear predictions, which are then deployed as online controllers. Unlike Explicit MPC—which suffers from scalability issues due to the exponential growth of partitions—DTs offer both interpretability through if-else rules and scalability via data-driven training, with datasets generated from ideal MPC simulations. Notably, DTs with oblique splits and linear leaf predictions mirror the piecewise affine structure of explicit MPC. A key challenge is training the DT model, a mixed-integer problem. We tackle this with a novel gradient-based algorithm, enabling efficient training with GPU-accelerated machine-learning tools. Through case studies, we demonstrate that this method accurately approximates both linear and nonlinear MPC control laws, significantly reducing online computation time while maintaining control performance.
</div>
# Speaker Bio
<div style="text-align: justify;">
Dr. Yankai Cao is an associate professor in the Department of Chemical and Biological Engineering at the University of British Columbia (UBC). He received a bachelor’s degree in Biological Engineering in 2010 from Zhejiang University and a Ph.D. degree in Chemical Engineering in 2015 from Purdue University. Before joining UBC, he was a research associate at the University of Wisconsin-Madison from 2016 to 2018. His research focuses on the design and implementation of large-scale optimization algorithms. His group are using these algorithms to address engineering and scientific questions that arise in diverse domains, including optimal decision trees, optimal clustering, machine-learning-based control, and optimal power system planning. 
</div>