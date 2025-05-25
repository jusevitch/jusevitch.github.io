---
title: Robust and Resilient Multi-Agent Consensus and Broadcasting
date: 2024-01-14
# external_link: https://rosflight.org/
# tags:
  # - Current Work
---

Shared information is necessary for cooperation in multi-agent systems. However, the presence of faulty or adversarial agents can introduce misinformation into the communication network, making it difficult for normally behaving agents to discern whether received information is accurate or not.

We study algorithms and graph theoretic communication topologies that enable normally behaving agents to filter out faulty or adversarial misinformation despite not knowing who is misbehaving. Our work was the first to compute key robustness values ({{< math >}}$(r,s)${{< /math >}}-robustness) using mixed integer linear programming, decreasing computation time and enabling modern commercial solvers to be applied towards designing robust and resilient network topologies.

Relevant papers:

* [Resilient Trajectory Propagation in Multirobot Networks](https://doi.org/10.1109/TRO.2021.3127076)

* [Resilient Leader-Follower Consensus to Arbitrary Reference Values in Time-Varying Graphs](https://doi.org/10.1109/TAC.2019.2934954)

* [Determining r-and (r, s)-robustness of digraphs using mixed integer linear programming](https://doi.org/10.1016/j.automatica.2019.108586)

* [Resilient Finite-Time Consensus: A Discontinuous Systems Perspective](https://doi.org/10.23919/ACC45564.2020.9147904)

* [r-Robustness and (r, s)-robustness of circulant graphs](https://doi.org/10.1109/CDC.2017.8264310)