---
permalink: /projects/
title: "Projects"
---

## Cooperative Air-Ground Robot Localization

![State Estimation Diagram](/assets/images/coop_loc_state_estimate.png)

Developed a centralized multi-sensor fusion framework in MATLAB for joint state estimation of a UAV-UGV system. Implemented and compared three Kalman filtering approaches (LKF, EKF, UKF) to fuse GPS data with inter-agent range and bearing measurements.

The system enables cooperative localization where aerial and ground robots improve each other's position estimates. Validated performance via Monte Carlo simulations using Normalized Innovation Squared (NIS) and Normalized Estimation Error Squared (NEES) statistics to verify filter consistency.

---

## Kinodynamic Motion Planning for High-Speed Gliders

![Planner Trajectory Visualization](/assets/images/kinodynamic_planner.png)

Built a C++ motion planning library implementing the Stable Sparse RRT* (SST) algorithm for autonomous glider navigation with non-linear 12-variable state dynamics.

Optimized the planner to handle high-dimensional constraints including wind fields and obstacle detection while achieving asymptotic optimality and sub-10 second planning times for dynamically feasible trajectories.

---

## Adaptive Multi-Objective Autonomous Underwater Vehicle

![AUV Pareto Front](/assets/images/auv_pareto_front.png)

Developed a Pareto-optimal AUV decision system in Julia using MDPs, Q-learning, and Transformer models to balance competing objectives including path efficiency, resource collection, and risk avoidance.

The framework maintains non-dominated action sets for each state, enabling adaptive decision-making without predetermined objective weightings. Achieved over 95% success rate after training, with intelligent behaviors like utilizing favorable currents and taking calculated risks for high-value targets.
