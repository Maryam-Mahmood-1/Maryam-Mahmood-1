<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=14&pause=1000&color=00D4AA&center=true&vCenter=true&width=600&lines=Control+Barrier+Functions+%E2%80%94+CBF-QP+Safety+Filters;Conformal+Prediction+for+Statistical+Safety;7-DOF+Manipulator+%E2%80%94+Real+Hardware%2C+Real+Control;ROS+2+%C2%B7+ros2_control+%C2%B7+MoveIt+2+%C2%B7+CAN+Bus" />

# Maryam Mahmood

**MS Robotics Engineering · NUST Islamabad · DAAD-Funded**

[![Email](https://img.shields.io/badge/Email-mmahmood.msee23seecs%40seecs.edu.pk-c0392b?style=flat-square&logo=gmail&logoColor=white)](mailto:mmahmood.msee23seecs@seecs.edu.pk)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Maryam--Mahmood-0077b5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/maryam-m-507a20348)
[![GitHub](https://img.shields.io/badge/GitHub-Maryam--Mahmood--1-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Maryam-Mahmood-1)
[![Portfolio](https://img.shields.io/badge/Portfolio-maryam--mahmood--1.github.io-00d4aa?style=flat-square&logo=githubpages&logoColor=white)](https://maryam-mahmood-1.github.io/MM_portfolio/)

</div>

---

## About

I build **optimization-based safety filters** for robotic manipulators.
My work sits at the intersection of rigorous control theory and physical hardware deployment — CBFs and CLFs that produce formal constraint satisfaction and convergence guarantees, extended into the statistical regime via conformal prediction.

Most robotics code on GitHub is either perception demos or simulation-only controllers.
Mine runs on a custom 7-DOF arm over a 7 ms CAN bus loop.

> *Systems validated:* inverted pendulum · cart-pole · Dubins car · quadrotor · ACC · 2/3/7-DOF manipulators

---

## Research Focus

### Control Barrier & Lyapunov Functions
- CBF-QP safety filters: forward invariance validated on 8 dynamical systems
- CLF-QP convergence: joint CLF-CBF formulations for simultaneous stability + safety
- Solver backends: OSQP, CVXPY — min-norm QP at each timestep

### Conformal Prediction for Safety
- Distribution-free coverage guarantees wrapped around learned dynamics models
- Calibrated robustness margin `q_{1-δ}` tightens the CLF decrease condition
- No parametric uncertainty assumption required
- *arXiv preprint targeting June 2026*

### 7-DOF Manipulator Stack
- MyActuator RMD-X8/X6 motors · dual CAN-bus topology (7 ms loop, down from 14 ms)
- Custom `ros2_control` hardware interface authored from scratch
- Full bringup: URDF/Xacro · MoveIt 2 · Gazebo · hardware-in-the-loop

---

## Active Projects

| Repository | Description | Status |
|---|---|---|
| [`CRCLF_Inverted_Pendulum`](https://github.com/Maryam-Mahmood-1/CRCLF_Inverted_Pendulum) | Conformally robust CLF control — SINDy + PINN model classes, distribution-free safety margins | `public` |
| [`daadbot_manipulator`](https://github.com/Maryam-Mahmood-1/daadbot_manipulator) | Full ROS 2 stack for a custom 7-DOF arm — ros2_control, MoveIt 2, Gazebo, hardware interface | `public` |
| CBF Safety Filter Suite | CBF-QP benchmarked across 8 systems · ros2_control plugin · accompanies arXiv | `releasing Jun 2026` |
| Multi-CAN Bus Orchestrator | Open-source dual-bus topology layer for ros2_control | `planned` |

### Conformal CLF — Headline Numbers

Conformal robustness keeps closed-loop trajectories inside the exponential envelope `V(x₀)·e^(−c₃t)` regardless of model class. The price: control aggressiveness scales with `q_{1-δ}`.

| Model | `q_{1-δ}` | CR-CLF violation | Without robustness term |
|---|---|---|---|
| SINDy | 0.115 | ~10⁻¹⁵ | 0.056 |
| Generic PINN | 6.572 | ~10⁻¹⁵ | **1.975** |
| Structured PINN | **0.057** | ~10⁻¹⁵ | 0.004 |

*Seed 5, T = 5 s, δ = 0.1. All CR-CLF runs satisfy the bound at machine precision.*

---

## Stack

```
Control   │ CBF-QP · CLF-QP · Conformal Prediction · PID · Cascaded PI · CTC · Impedance
Robotics  │ ROS 2 · ros2_control · MoveIt 2 · Gazebo · URDF/Xacro · Pinocchio · MuJoCo
Hardware  │ MyActuator RMD-X8/X6 · CAN/SocketCAN · ESP32 · MCP2515 · Intel RealSense D435i
Languages │ Python · C++ · MATLAB · Bash
Tools     │ Docker · Git · LaTeX · Ubuntu 22.04
Theory    │ Lyapunov Stability · Set Invariance · Convex Optimization · Stochastic Systems
```

---

## Upcoming

- [ ] **arXiv** — *Statistical Safety Guarantees via Conformal CBFs* · Jun 2026
- [ ] **CBF suite public release** · Jun 2026 (with arXiv)
- [ ] **ICRA 2027 submission** · Sep 15, 2026
- [ ] **Portfolio site** · [maryam-mahmood-1.github.io/MM_portfolio](https://maryam-mahmood-1.github.io/MM_portfolio/)

---

## GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Maryam-Mahmood-1&show_icons=true&theme=github_dark&hide_border=true&title_color=00d4aa&icon_color=00d4aa&text_color=c9d1d9&bg_color=0d1117" height="160"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=Maryam-Mahmood-1&theme=github-dark-blue&hide_border=true&ring=00d4aa&fire=00d4aa&currStreakLabel=00d4aa" height="160"/>

</div>

---

<div align="center">
<sub>SEECS · NUST · Islamabad, Pakistan</sub>
</div>
