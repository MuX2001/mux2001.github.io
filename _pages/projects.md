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

### Learning Mixed-Integer Solvers for MPC (2025)
Explored differentiable optimization for mixed-integer quadratic programs (MIQP) in model predictive control.  
Developed a CVXPYLayer-based learning framework where neural networks predict integer decisions while the continuous optimization is solved in a differentiable QP layer.  
**Keywords:** differentiable optimization, MIQP, learning-to-optimize, MPC

### Gaussian Process Dynamics with MPPI (2025)
Built a Gaussian Process (GP) model to estimate vehicle dynamics and integrated it with Model Predictive Path Integral (MPPI) control.  
Focused on uncertainty propagation and adaptive trajectory control performance.  
**Keywords:** Gaussian Process regression, uncertainty-aware control, Bayesian learning

---

## Autonomous Systems

### F1TENTH Autonomous Racing (2025)
Participated in three autonomous racing rounds using a full **ROS 2** stack for perception, planning, and control.  
Developed and integrated multiple subsystems that formed a complete racing pipeline:

- **Planning & Control**
  - Implemented *Wall-Follow* and *Gap-Follow* algorithms with PID tracking.
  - Developed *Pure Pursuit* trajectory tracking and *MPC-based optimal control*.
  - Added *dynamic obstacle avoidance*.

- **Perception**
  - Designed vehicle detection pipeline combining *YOLO object detection* and *LiDAR clustering* for robust localization and obstacle tracking.

- **Races**
  - Competed in **two time-trial** events and **one head-to-head** race, achieving real-time performance under tight computational budgets.

**Tools:** ROS 2, Python/C++, RViz, TensorRT  
**Keywords:** autonomous racing, motion planning, perception, MPC, embedded robotics

### LLM-Guided Navigation for F1TENTH (2025)
Investigated using large language models (LLMs) for natural-language-driven navigation and control decisions.  
Connected semantic task instructions to high-level control primitives in simulation.  
**Keywords:** LLM robotics, task planning, autonomous driving

---

## Classical Control and Learning Foundations

### Quadrotor Control Paper Reproduction (2025)
Reproduced results from a published nonlinear quadrotor control paper.  
Implemented attitude and trajectory controllers, sensor fusion and state estimation, validated stability and robustness, and analyzed sensitivity to modeling errors.  
**Tools:** Python

### Image-to-GPS Regression (2024)
Implemented Vision-Transformer regression to estimate geographic coordinates from street images, benchmarking against classical feature-matching baselines.  
**Keywords:** vision transformers, geolocation, regression
