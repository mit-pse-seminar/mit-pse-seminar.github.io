---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: seminar
title: "Nonlinear model predictive control for anything: Designing fast, efficient, and safe neural network controllers"
date: 2025-04-24 2:00pm
author: Sergio Lucia
affiliation: TU Dortmund
# zoom: https://mit.zoom.us/j/123456789
---
# Abstract
<div style="text-align: justify;">
Model predictive control still faces significant computational challenges to be widely applied, particularly in nonlinear systems subject to uncertainties. A promising approach to solve these challenges involves using neural networks to approximate optimal control inputs based on the system's current state. Despite its growing popularity, this strategy has two major challenges: the substantial data requirement for training and the fact that the safety and stability properties of the original MPC controller are not automatically transferred to the closed-loop system. 

In this talk, we first show the potential of the methodology and then outline solutions for the mentioned challenges. Firstly, we demonstrate how integrating parametric sensitivities into the training process can enhance data efficiency, making the neural network training more effective with less data and discuss alternative unsupervised learning strategies. Secondly, we introduce both probabilistic and deterministic verification techniques to guarantee that important closed-loop properties are maintained despite the approximation errors, even when additional uncertainty is present. The effectiveness of these techniques is illustrated in several simulation and experimental studies for linear and non-linear systems.
</div>

# Speaker Bio 
![photo](./headshots/lucia.jpg)
<div style="text-align: justify;">
Sergio Lucia received the M.Sc. degree in Electrical Engineering from the University of Zaragoza, Spain, in 2010 and the Dr.-Ing. degree in Optimization and Automatic Control from the TU Dortmund University, Germany, in 2014. He then joined the Otto-von-Guericke University Magdeburg and visited the Massachusetts Institute of Technology as a Postdoctoral Fellow. From 2017 to 2020, he served as an Assistant Professor at TU Berlin before returning to TU Dortmund University as an Associate Professor in 2020. Since 2023, he has been a Full Professor and Head of the Chair of Process Automation Systems at TU Dortmund University. His research focuses on decision making under uncertainty and the integration of machine learning with control theory. Additionally, he serves as an Associate Editor for the Journal of Process Control.
</div>
