# Delta Robot Parallel Kinematics 3D Simulator

<div align="center">

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Interactive-brightgreen?style=for-the-badge&logo=googlechrome&logoColor=white)](https://djidelabdelali.github.io/delta-robot-simulator/)
[![Portfolio](https://img.shields.io/badge/Portfolio-DJIDEL%20Abdelali%20Rayan-blue?style=for-the-badge&logo=react&logoColor=white)](https://djidelabdelali.github.io/portfolio/)
[![GitHub Repo](https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/DjidelAbdelali/delta-robot-simulator)

</div>

---

## 📌 Project Overview

Interactive 3D simulation of the Delta parallel robot designed during my Master's PFE at USTHB. Reconstructed from Simulink (.slx) & SolidWorks CAD models: real-time forward/inverse kinematics, closed-loop PID control simulation, trajectory playback, and WebGL command console.

This project is an engineering module built by **DJIDEL Abdelali Rayan** (Systems & Automation Engineer, USTHB).

---

## 🏗️ System Architecture & Data Flow

```mermaid
graph TD
    User[User Controls / Sliders / Trajectory Playback] --> IK[Inverse Kinematics Solver (IK)]
    IK --> Controller[Closed-Loop PID Controllers (Arms 1, 2, 3)]
    Controller --> Dynamics[Simulink Dynamic Model / Physics Engine]
    Dynamics --> FK[Forward Kinematics Validation (FK)]
    FK --> WebGL[Three.js 60FPS WebGL Renderer]
```

---

## 🛠️ Key Technologies & Frameworks

- **Three.js**
- **TypeScript**
- **MATLAB/Simulink**
- **Kinematics (FK/IK)**
- **PID Control**

---

## 🚀 Live Interactive Web Demo

No installation required! Test and interact with the full web simulation live in your browser:
🔗 **[Launch Interactive Web Demo](https://djidelabdelali.github.io/delta-robot-simulator/)**

---

## 🔗 Connected Portfolio Ecosystem

- 🌐 **Main Portfolio**: [djidelabdelali.github.io/portfolio](https://djidelabdelali.github.io/portfolio/)
- 💻 **GitHub Profile**: [github.com/DjidelAbdelali](https://github.com/DjidelAbdelali)
- 💼 **LinkedIn Profile**: [DJIDEL Abdelali Rayan](https://linkedin.com/in/djidel-abdelali-rayan-814b25207)

---

<div align="center">
  <sub>Developed by DJIDEL Abdelali Rayan — Systems & Automation Engineering</sub>
</div>
