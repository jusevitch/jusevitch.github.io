---
title: Dynamix - A Lightweight Differentiable Control Simulator
date: 2024-05-01
# external_link: https://rosflight.org/
# tags:
  # - current_proj
---

Automatic differentiation has revolutionized how control systems can be developed and simulated. The ability to propagate gradients end-to-end through dynamical simulations allows for simulated control systems to tune parameters and train themselves automatically. In addition, the ability to differentiate through classical algorithms has opened up opportunities to surgically insert neural networks side-by-side with classical algorithms to combine the strengths of both.

We are developing a lightweight differentiable simulator to facilitate researching and developing next-generation control algorithms blending both learning and classical methods. The simulator is written in JAX and is being designed for both analytical policy gradient and reinforcement learning applications. In addition, the simulator will contain several off-the-shelf dynamical models and control algorithms for rapid prototyping and experimentation.