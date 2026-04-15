---
layout: single
title: "Projects"
permalink: /projects/
author_profile: true
lang: "en-US"
locale: "en-US"
lang_ref: "projects"
---

## Research Projects

In my research at xLab (UPenn), I explore learning-based methods to improve solving time, dynamics modeling, and optimization structure for control problems in safety-critical settings.

### Learning-to-Optimize for Mixed-Integer Nonlinear Programming (2025 – Present)
*MINLPs arise naturally in hybrid systems and safety-constrained control, but their combinatorial structure makes real-time solving intractable — learning can amortize this cost across repeated problem instances.*  
Developed the **L2O-MISQP** framework, integrating neural networks with a trust-region MISQP solver to accelerate solving complex MINLP problems.  
Designed an end-to-end hybrid training pipeline using differentiable optimization layers.  
*Under submission.*  
**Keywords:** MINLP, learning-to-optimize, differentiable optimization, trust-region methods

### Hybrid Learning-to-Optimize for Mixed-Integer MPC (2025)
*MPC requires solving a new MIQP at every control step; the key insight is that these problems share structure across time, so a neural network can predict warm-start integer decisions and cut solve time without sacrificing feasibility.*  
Proposed a hybrid learning-to-optimize framework for parametric MIQPs, targeting acceleration of mixed-integer MPC.  
Integrated neural integer prediction, a differentiable QP layer, and supervised/self-supervised losses to improve feasibility and optimality.  
*Accepted at Learning for Dynamics and Control (L4DC) 2025.* \[[arXiv](https://arxiv.org/abs/2511.19383)\]  
**Keywords:** differentiable optimization, MIQP, learning-to-optimize, MPC

### Gaussian Process Dynamics with MPPI (2025)
*Physics-based vehicle models degrade under changing conditions; a GP learned residual can correct mismatch on-the-fly, but only when the uncertainty is well-calibrated.*  
Learned GP dynamics from F1TENTH vehicle data and integrated uncertainty into Model Predictive Path Integral (MPPI) control.  
Conducted a systematic study of GP-residual dynamics under varying levels of model mismatch, identifying conditions where learned corrections improve performance and where they cause instability.  
**Keywords:** Gaussian Process regression, uncertainty-aware control, MPPI, Bayesian learning

---

## Autonomous Systems

### MPC Controller for BeamNG (2026 – Present)
*Simulation-to-real transfer is hard; BeamNG provides a high-fidelity closed-loop testbed to stress-test planning and control algorithms before hardware deployment.*  
Developed a vehicle control pipeline for trajectory tracking and high-speed autonomous driving in BeamNG.  
Implemented and evaluated LTV-MPC for tracking human-driven waypoints, achieving 80% of human-driver lap pace on the Spa track.  
Ongoing: building Actor-Critic RL with DiffMPC and Vanilla MPPI in the same environment.  
Code: [GitHub - MPC](https://github.com/MuX2001/BeamNG-LTV-MPC)  
**Keywords:** MPC, LTV-MPC, autonomous driving, reinforcement learning, DiffMPC

### F1TENTH Autonomous Racing (2025)
Built a complete **ROS 2** stack for perception, planning, and control for autonomous racing.

- **Planning & Control**
  - Implemented *Wall-Follow*, *Gap-Follow*, *Pure Pursuit*, and *MPC* controllers with dynamic obstacle avoidance and race-line optimization.

- **Perception**
  - Developed LiDAR-based localization and vision-based vehicle detection.

- **Races**
  - Completed **two time-trial** events and **one head-to-head** race on hardware.
  - Placed 1st in the first time-trial event; first team to achieve fully headless on-hardware deployment and real-time debugging.

**Tools:** ROS 2, Python, C++  
**Keywords:** autonomous racing, motion planning, perception, MPC, embedded robotics

### LLM-Guided Navigation for F1TENTH (2025)
*Natural language is the most accessible interface for non-expert operators — bridging it to low-level control requires grounding semantic intent into safe, executable primitives.*  
Created an LLM-based planner converting natural-language commands to driving primitives.  
Integrated symbolic reasoning with classical control for interactive autonomous-navigation tasks.  
Validated in simulation and real F1TENTH environments.  
**Keywords:** LLM robotics, task planning, autonomous driving

---

## Classical Control and Learning Foundations

### Quadrotor Control Paper Reproduction (2025)
Reproduced nonlinear quadrotor control using cascaded attitude/position controllers.  
Analyzed robustness under parameter uncertainty and external disturbances.  
Developed grid-based planners and sensor-fusion routines for trajectory generation.  
**Tools:** Python

### Image-to-GPS Regression (2024)
Implemented Vision-Transformer regression to estimate geographic coordinates from street images, benchmarking against classical feature-matching baselines.  
**Keywords:** vision transformers, geolocation, regression
