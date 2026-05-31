# Maryam Mahmood

**MS EE — AI & Autonomous Systems · NUST Islamabad · DAAD-Funded Thesis Project**

[![Email](https://img.shields.io/badge/Email-mmahmood.msee23seecs%40seecs.edu.pk-8B4513?style=flat-square&logo=gmail&logoColor=white)](mailto:mmahmood.msee23seecs@seecs.edu.pk)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Maryam--Mahmood-6b4c2a?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/maryam-m-507a20348)
[![Portfolio](https://img.shields.io/badge/Portfolio-maryam--mahmood--1.github.io-9a7040?style=flat-square&logo=githubpages&logoColor=white)](https://maryam-mahmood-1.github.io/MM_portfolio/)

---

## About

Deploying autonomous systems into spaces shared with humans demands a shift from heuristic safety to provable guarantees. When a high-torque manipulator operates alongside a person, constraint satisfaction cannot be approximate. My current research focuses on the formal and statistical frameworks that make such deployment defensible — validated through end-to-end implementation on real hardware.

---

## Research

**CBF-QP safety filters.** Forward-invariant safe sets via Control Barrier Functions. A min-norm QP at each timestep keeps the nominal controller's intent while enforcing the safety constraint. Validated across 8 systems — inverted pendulum, cart-pole, Dubins car, quadrotor, ACC, and 2/3/7-DOF manipulators.

**Conformal prediction for safety.** I'm currently wrapping learned dynamics models with a distribution-free robustness margin `q_{1-δ}`, calibrated from held-out trajectories, that tightens the CLF decrease condition. No parametric uncertainty model assumed.

**7-DOF manipulator.** Custom arm, MyActuator RMD motors, dual CAN-bus topology that drops the control loop from 14 ms to 7 ms. I authored the full ROS 2 stack — URDF/Xacro, custom `ros2_control` hardware interface, MoveIt 2, Gazebo.

---

## Projects

| Repository | Description |
|---|---|
| [`CRCLF_Inverted_Pendulum`](https://github.com/Maryam-Mahmood-1/CRCLF_Inverted_Pendulum) | Conformally robust CLF control — SINDy and PINN model classes under one conformal calibration layer |
| [`daadbot_manipulator`](https://github.com/Maryam-Mahmood-1/daadbot_manipulator) | Full ROS 2 stack for a custom 7-DOF arm — `ros2_control`, MoveIt 2, Gazebo, hardware interface |

---

## Stack

```
Control   │ CBF-QP · CLF-QP · Conformal Prediction · PID · Cascaded PI · Computed Torque
Robotics  │ ROS 2 · ros2_control · MoveIt 2 · Gazebo · URDF/Xacro · Pinocchio · MuJoCo
Hardware  │ MyActuator RMD-X8/X6 · CAN/SocketCAN · ESP32 · MCP2515 · Intel RealSense D435i
Languages │ Python · C++ · MATLAB · Bash
Tools     │ Docker · Git · LaTeX · Ubuntu 22.04
Theory    │ Lyapunov Stability · Set Invariance · Convex Optimization · Stochastic Systems
```

<!--
## Upcoming
- arXiv preprint — Statistical Safety Guarantees via Conformal CBFs
- CBF safety filter suite — public release
- ICRA 2027 submission
- Multi-CAN bus orchestrator for ros2_control
-->

---

<sub>SEECS · NUST · Islamabad, Pakistan</sub>
