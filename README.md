#  3-DOF Robotic Arm (MATLAB App Designer)

##  Project Overview
This project is a **3-DOF (Degrees of Freedom) robotic arm simulator** developed using **MATLAB App Designer**.
It allows the user to control and visualize a robotic arm in 3D space using **Forward Kinematics** and **Inverse Kinematics**.

##  Repository Content
This repository contains the following main files:

### 1) MATLAB App Designer File (.mlapp)
This is the main application file created using **MATLAB App Designer**.
It contains the full GUI, simulation logic, and all implemented features.

### 2) Presentation / Documentation (PDF)
This file explains the project idea, kinematics equations, and the main functions of the application.

## ⚙️ Main Features
- **Forward Kinematics**
  - Computes the end-effector position from joint angles (θ1, θ2, θ3)
- **Inverse Kinematics**
  - Computes joint angles required to reach a target position (px, py, pz)
- **3D Visualization**
  - Displays the robotic arm in a 3D workspace
- **Animation**
  - Shows smooth movement of the robotic arm step-by-step
- **Obstacle Detection Mode**
  - Detects collisions during motion and displays an error message
- **Dynamics Mode**
  - Simulates realistic motion including angular velocity and torque calculations

##  Mathematical Model (Summary)
The project is based on transformation matrices for Forward Kinematics:
- T01, T12, T23
- T03 = T01 * T12 * T23

Inverse kinematics uses:
- r = sqrt(px^2 + py^2)
- z = pz - L1
- Cosine law for reachability

##  How to Run the Project
1. Open MATLAB
2. Open the file: `app1.mlapp`
3. Click **Run**
4. Use the GUI inputs to test Forward / Inverse modes and animation features

##  Requirements
- MATLAB (Recommended: R2020+)
- App Designer enabled

## 👤 Author
Ayman AbedAlKarim Hamad
