# ⚙️ Control of a Mechanical System with Two Carts and a Rolling Body

## 📌 Overview
This project presents the modeling, analysis, and control of a mechanical system composed of two carts and a rolling body connected by springs and dampers. Various control techniques are explored to ensure system stability and optimal performance.

## 🔬 Key Contributions
- **📐 Mathematical Modeling**: Derived equations of motion and state-space representation.
- **🕵️ System Analysis**:
  - Controllability and observability verification.
  - Stability assessment using eigenvalue analysis.
- **🎯 Control Strategies Implemented**:
  - **State Feedback with Eigenvalue Assignment**: Ensures desired closed-loop dynamics.
  - **Observer Design**: Estimates system states when direct measurements are unavailable.
  - **Optimal Control (LQR)**: Minimizes a quadratic cost function for energy-efficient control.
  - **LQG Control**: Combines LQR with Kalman filtering for robust state estimation.
  - **H∞ Control and Mixed Sensitivity Design**: Enhances disturbance rejection and robustness.

## 📈 Results
- ✅ All controllers successfully regulate the system while meeting design specifications:
  - **Settling time**: < 8s
  - **Overshoot**: < 10%
  - **Steady-state error**: 0 for step inputs.
- 📊 Comparative analysis highlights trade-offs in control performance, robustness, and computational complexity.

## 🚀 Future Work
- 🔧 Implement adaptive control techniques for varying system parameters.
- 📡 Explore real-time implementation with hardware-in-the-loop testing.

## 👩‍🔬 Author
**Fiorella Maria Romano**  
📍 Scuola Politecnica e delle Scienze di Base, Ingegneria dell’Automazione e Robotica  
📅 Academic Year 2023/2024
