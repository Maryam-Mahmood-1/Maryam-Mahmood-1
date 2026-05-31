# Maryam Mahmood

**MS Electrical Engineering — AI & Autonomous Systems · NUST Islamabad**
**DAAD-Funded Thesis Project · Robotics · Safe Learning-Based Control**

[![Email](https://img.shields.io/badge/Email-mmahmood.msee23seecs%40seecs.edu.pk-8B4513?style=flat-square\&logo=gmail\&logoColor=white)](mailto:mmahmood.msee23seecs@seecs.edu.pk)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Maryam--Mahmood-6b4c2a?style=flat-square\&logo=linkedin\&logoColor=white)](https://linkedin.com/in/maryam-m-507a20348)
[![Portfolio](https://img.shields.io/badge/Portfolio-maryam--mahmood--1.github.io-9a7040?style=flat-square\&logo=githubpages\&logoColor=white)](https://maryam-mahmood-1.github.io/MM_portfolio/)
[![GitHub](https://img.shields.io/badge/GitHub-Maryam--Mahmood--1-2f2f2f?style=flat-square\&logo=github\&logoColor=white)](https://github.com/Maryam-Mahmood-1)

---

## About Me

I work at the intersection of **robotics, control theory, machine learning, and autonomous systems**, with a particular interest in making intelligent systems not only capable, but also **safe, reliable, and formally defensible**.

My current research focuses on safety-critical control for robotic systems operating in human-shared environments. I am especially interested in how tools such as **Control Barrier Functions, Lyapunov-based control, quadratic programming, and conformal prediction** can be combined to provide practical safety guarantees for learned and uncertain systems.

At the same time, I enjoy building complete robotic software stacks — from simulation and control to ROS 2 integration and real hardware deployment.

---

## Research Interests

* Safe learning-based control
* Control Barrier Functions and Control Lyapunov Functions
* Conformal prediction for uncertainty-aware autonomy
* Optimization-based control and safety filters
* Robotic manipulators and autonomous systems
* ROS 2, MoveIt 2, Gazebo, and hardware integration
* Vision, learning, and safety for real-world robotic deployment

---

## Current Research

### CBF-QP Safety Filters

I work with **Control Barrier Function based quadratic-programming safety filters**, where a nominal controller is minimally modified to satisfy formal safety constraints.

The goal is to preserve the controller’s intended behavior while ensuring the system remains inside a forward-invariant safe set.

Validated across multiple nonlinear and robotic systems, including:

* Inverted pendulum
* Cart-pole
* Dubins car
* Quadrotor
* Adaptive cruise control
* 2-DOF, 3-DOF, and 7-DOF manipulators

---

### Conformal Prediction for Safety-Critical Control

My current work explores how **conformal prediction** can be used to wrap learned dynamics models with statistically calibrated robustness margins.

Instead of assuming a parametric uncertainty model, I calibrate a distribution-free margin from held-out trajectory data and use it to tighten Lyapunov-style decrease conditions.

This direction aims to make learned controllers more defensible under model mismatch and uncertainty.

---

### 7-DOF Manipulator Platform

I am also working on a custom 7-DOF robotic manipulator platform using **MyActuator RMD motors** and a dual CAN-bus architecture.

Key contributions include:

* Full ROS 2 stack development
* URDF/Xacro robot modeling
* Custom `ros2_control` hardware interface
* MoveIt 2 motion planning integration
* Gazebo simulation setup
* CAN/SocketCAN communication
* Control-loop latency reduction from around **14 ms to 7 ms** using a dual-bus topology

---

## Featured Projects

| Repository                                                                               | Description                                                                                                                    |
| ---------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------ |
| [`CRCLF_Inverted_Pendulum`](https://github.com/Maryam-Mahmood-1/CRCLF_Inverted_Pendulum) | Conformally robust CLF control framework using SINDy and PINN model classes under a unified conformal calibration layer        |
| [`daadbot_manipulator`](https://github.com/Maryam-Mahmood-1/daadbot_manipulator)         | Full ROS 2 stack for a custom 7-DOF robotic arm, including `ros2_control`, MoveIt 2, Gazebo, and hardware interface components |
| [`Project-Timeline`](https://maryam-mahmood-1.github.io/Project-Timeline/)               | Interactive project timeline documenting research, implementation milestones, and development progress                         |

---

## Technical Stack

```text
Control   │ CBF-QP · CLF-QP · Conformal Prediction · PID · Cascaded PI · Computed Torque
Robotics  │ ROS 2 · ros2_control · MoveIt 2 · Gazebo · URDF/Xacro · Pinocchio · MuJoCo
Hardware  │ MyActuator RMD-X8/X6 · CAN/SocketCAN · ESP32 · MCP2515 · Intel RealSense D435i
Languages │ Python · C++ · MATLAB · Bash
Tools     │ Docker · Git · LaTeX · Ubuntu 22.04
Theory    │ Lyapunov Stability · Set Invariance · Convex Optimization · Stochastic Systems
```

---

## GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Maryam-Mahmood-1&show_icons=true&theme=gruvbox&hide_border=true" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Maryam-Mahmood-1&layout=compact&theme=gruvbox&hide_border=true" height="165" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Maryam-Mahmood-1&theme=gruvbox&hide_border=true" height="165" />
</p>

---

## Currently Exploring

* Statistical safety guarantees for learned controllers
* Conformal CBF/CLF formulations
* Vision and ML-heavy robotics research directions
* Publishable work that can be validated in simulation without requiring extensive hardware experiments
* Interactive project documentation for robotics systems

<!--
## Upcoming

- arXiv preprint — Statistical Safety Guarantees via Conformal CBFs
- CBF safety filter suite — public release
- ICRA 2027 submission
- Multi-CAN bus orchestrator for ros2_control
-->

---

<p align="center">
  <i>Building safer autonomous systems through control, learning, and robotics.</i>
</p>

<p align="center">
  <sub>SEECS · NUST · Islamabad, Pakistan</sub>
</p>
