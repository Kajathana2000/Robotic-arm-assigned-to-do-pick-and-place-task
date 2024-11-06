# Pick and Place Robotic Arm Simulation 🤖🛠️

This project automates a **pick and place task** within a manufacturing line, using a robotic arm to move a disk between stations for labeling and transfer. The simulation uses **RoboDK** for real-world modeling and **MATLAB Robotics Toolbox** for trajectory planning and kinematics verification.

---

## 📋 Project Overview

**Objective:**  
Design and simulate a robotic arm system to automate disk handling across three stations:
1. **Station 1:** Pick the disk from the conveyor.
2. **Station 2:** Label the disk.
3. **Station 3:** Transfer the disk to another conveyor.

**Key Specifications:**
- **Disk Dimensions:** 2 cm width, 0.5 kg weight.
- **Robotic Arm Model:** ABB IRB 1100-4/0.58 with 5 Degrees of Freedom (DOF).
- **Simulation Software:** RoboDK for modeling and MATLAB for kinematic analysis.

---

## 🛠️ Project Steps

### 1. **Robotic Arm Selection**
   - The ABB IRB 1100-4/0.58 arm was chosen for its reach, payload, and DOF suitable for handling the disk.

### 2. **Simulation and Modeling with RoboDK**
   - Developed a 3D model in RoboDK, selecting **RobotiQ Epick Vacuum Gripper** for accurate disk handling.
   - Positioned the arm to operate within a **table size of 1400 x 800 x 800 mm**.

### 3. **Trajectory Planning**
   - Defined two waypoints for smooth movement from the pick to place stations.
   - Planned the arm’s trajectory, ensuring optimized paths between the stations for efficiency.

### 4. **Kinematics Analysis in MATLAB**
   - Verified forward and inverse kinematics using MATLAB's Robotics Toolbox.
   - Generated a velocity profile and 3D trajectory visualization of the end effector.

---

## 🔍 Observations

- The robotic arm successfully performs the pick and place task, with efficient movement through designated waypoints.
- Forward and inverse kinematics confirm accurate positioning of the arm at each station.
- Simulation results indicate reliable operation, maintaining smoothness and stability.

---

## 🚧 Challenges and Solutions

- **Trajectory Smoothness:** Adjusted waypoint placements to optimize motion paths.
- **Simulation Accuracy:** Verified kinematic models in MATLAB to match RoboDK movements.
- **Component Constraints:** Selected a compatible gripper (RobotiQ Epick) to secure the disk accurately.

---

## 🏁 Conclusion

The **Pick and Place Robotic Arm Simulation** demonstrates a successful automation solution for manufacturing lines, showcasing the ABB IRB 1100-4/0.58's effectiveness in handling, trajectory planning, and stability. The simulation validates the feasibility of using robotic arms for precise and efficient manufacturing tasks.

---

## 📚 References

- [RoboDK Documentation](https://robodk.com/doc/en/)
- [MATLAB Robotics Toolbox Documentation](https://www.mathworks.com/help/robotics/)
