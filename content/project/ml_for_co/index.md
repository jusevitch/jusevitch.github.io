---
title: Machine Learning for Combinatorial Optimization
show_date: false
date: 2023-09-01
# external_link: https://rosflight.org/
# tags:
  # - current_proj
---

Multi-agent systems require coordination for agents to cooperate effectively towards collaboratively achieving missions. Teams of multiple robots need to perform planning or replanning on the order of seconds to milliseconds in order to quickly react to dynamic environments. However, coordination problems are frequently combinatorial and NP-hard in nature. Using existing algorithms, plans for small teams can take minutes to generate, and this runtime increases to hours or days for larger team sizes.

Machine learning has shown great potential for exploiting hidden problem structure to rapidly predict solutions to these problems, but can struggle with guaranteeing feasibility of predicted solutions. Classical solvers excel at guaranteeing feasibility and optimality, but can suffer from long runtimes. 

We focus on uniting the strengths of both learning and classical algorithms to accelerate solving combinatorial problems encountered by multi-agent systems.