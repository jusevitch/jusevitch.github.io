---
title: Safety for Multi-Agent Systems using Control Barrier Function Methods
show_date: false
# date: 2024-01-14
# external_link: https://rosflight.org/
# tags:
  # - current_proj
---

Safety and collision avoidance are fundamental requirements for operating mobile multi-agent systems. Control Barrier Function (CBF) methods are effective tools for maintaining online safety in dynamic environments with multiple obstacles. CBFs apply an online "filter" to nominal control laws to minimally modify a control law to prevent the system from exiting a set of safe states. CBFs can also be combined with CLFs to compute both safe and stabilizing control laws simultaneously.

We develop novel CBF-based techniques for strengthening safety guarantees for multi-agent systems. Our contributions were the first to develop CBF methods for adversarial multi-agent scenarios, and the first to apply CBFs to preserving safety for entire convex sets without requiring the use of nonsmooth analysis.

Relevant papers include:

* [Safety for Time-Varying Parameterized Sets Using Control Barrier Function Methods](https://arxiv.org/abs/2503.12003)

* [Advances in the Theory of Control Barrier Functions: Addressing practical challenges in safe control synthesis for autonomous and robotic systems](https://doi.org/10.1016/j.arcontrol.2024.100945)

* [Adversarial Resilience for Sampled-Data Systems Under High-Relative-Degree Safety Constraints](https://doi.org/10.1109/TAC.2022.3157791)

* [Strong Invariance Using Control Barrier Functions: A Clarke Tangent Cone Approach](https://doi.org/10.1109/CDC42340.2020.9303873)