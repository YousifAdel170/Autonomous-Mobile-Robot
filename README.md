# 🤖 Autonomous Mobile Robot (AMR) – Simulation Only

This project simulates an **Autonomous Mobile Robot (AMR)** using **ROS (Robot Operating System)** and **Gazebo**, focusing on robot modeling, SLAM, and autonomous navigation.

---

## 🛠️ Project Overview

The AMR was built and tested entirely in simulation. It uses a custom robot model created with **URDF**, and integrates various sensors to explore autonomous capabilities.

Key components include:

- **URDF** modeling to define the robot’s physical properties and sensor placements.
- **GMapping algorithm** for SLAM using two different sensors:
  - **Kinect** (180° field of view)
  - **LIDAR** (360° field of view)

> 🔍 The project explores the effectiveness and differences in mapping performance between Kinect and LIDAR sensors.

- **MoveBase** package for autonomous navigation:
  - **A\*** algorithm for global path planning
  - **DWA (Dynamic Window Approach)** for local obstacle avoidance
- Parameter tuning for accurate path planning, smooth motion, and safe navigation.

---

## 🔧 Technologies Used

- **ROS Noetic**
- **Gazebo Simulator**
- **URDF / xacro**
- **GMapping**
- **RViz**
- **MoveBase**
- **A\*** & **DWA Planners**

---

## 🧠 Learning Outcomes

- Learned how different sensor configurations affect mapping performance.
- Gained hands-on experience with:
  - Robot modeling
  - SLAM techniques
  - Autonomous path planning
  - Parameter tuning for navigation
- Improved understanding of real-world robotic challenges, even in simulation.

---

## 🔗 Related Projects

- [🦽 Self-Driving Wheelchair (Simulation & Real)](https://github.com/YousifAdel170/Autonomous-Wheelchair)

---

## Demo

**Live Demo**

For a live demo of the **AMR Simulation** system:  
[Watch on LinkedIn](https://www.linkedin.com/posts/yousif-adel-a601641b1_autonomousrobots-pathplanning-ros-activity-7235637954805723136-6JO7?utm_source=share&utm_medium=member_desktop&rcm=ACoAADFSougBbplLvCFvoq2oVcM3uoEe_eK2zig)

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 🙋‍♂️ Author

**Yousif Adel** – [LinkedIn](https://www.linkedin.com/in/yousif-adel-a601641b1/)
