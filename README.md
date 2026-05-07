# Hey, I'm Rian Archie Fernandes 👋

I'm a Robotics Engineering grad student at Northeastern University in Boston, graduating in April 2026. I love building things that actually work in the real world, not just in simulation. My focus is on sensor fusion, SLAM, motion planning, and computer vision.

---

## A bit about me

- Finishing my MS in Robotics Engineering at **Northeastern University, Boston** in April 2026
- Recently built a **monocular depth estimation pipeline** comparing MiDaS and Depth Anything V2 with 3D point cloud visualization using Open3D
- Also built a **GPS/IMU sensor fusion system using EKF in ROS2** with real driving data collected around Boston
- Actively looking for **full time roles in Robotics Software, Embedded Systems, Computer Vision, and Electrical Engineering**
- I learn best by building things from scratch and understanding every line of code
- Ask me anything about **ROS2, sensor fusion, SLAM, depth estimation, or computer vision**

---

## What I work with

**Robotics**

![ROS2](https://img.shields.io/badge/ROS2-Humble-blue?logo=ros)
![Ubuntu](https://img.shields.io/badge/Ubuntu-22.04-orange?logo=ubuntu)
![Gazebo](https://img.shields.io/badge/Gazebo-Simulation-green)

**Programming**

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![C++](https://img.shields.io/badge/C++-17-blue?logo=cplusplus)
![MATLAB](https://img.shields.io/badge/MATLAB-orange)

**Computer Vision and Deep Learning**

![OpenCV](https://img.shields.io/badge/OpenCV-green?logo=opencv)
![PyTorch](https://img.shields.io/badge/PyTorch-red?logo=pytorch)
![YOLOv8](https://img.shields.io/badge/YOLOv8-purple)
![Open3D](https://img.shields.io/badge/Open3D-3D_Vision-blue)
![HuggingFace](https://img.shields.io/badge/HuggingFace-Transformers-yellow?logo=huggingface)

**Embedded and Hardware**

![Microcontrollers](https://img.shields.io/badge/Microcontrollers-embedded-red)
![PLC](https://img.shields.io/badge/Allen_Bradley_PLC-ladder_logic-orange)
![Oscilloscope](https://img.shields.io/badge/Oscilloscope-debugging-blue)

---

## Projects I've built

### [Monocular Depth Estimation: MiDaS vs Depth Anything V2](https://github.com/Rian013/depth-estimation-midas-vs-dav2)
Implemented and compared two state-of-the-art depth estimation models on real-world indoor and outdoor scenes. Evaluated quantitatively on 50 samples from the NYU Depth V2 benchmark using AbsRel and RMSE. Key finding: Depth Anything V2 produces 60x sharper depth maps by Laplacian variance despite MiDaS scoring better on the indoor benchmark, demonstrating the gap between metrics and perceptual quality. Extended the pipeline to generate colored 3D point clouds using Open3D. Runs fully on CPU.

`PyTorch` `Hugging Face` `Open3D` `OpenCV` `MiDaS` `Depth Anything V2` `NYU Depth V2` `Python`

---

### [EKF GPS/IMU Fusion](https://github.com/Rian013/ekf-gps-imu-fusion)
Built an Extended Kalman Filter from scratch to fuse GPS and IMU data in ROS2. Collected real sensor data by driving around Boston with a VN-100 IMU and BU-353S4 GPS mounted in a car. The filter handles magnetometer calibration, IMU drift correction, and publishes filtered odometry in real time.

`ROS2` `Python` `NumPy` `Sensor Fusion` `EKF` `pyproj`

---

### Dynamic Object Tracking with PX150 Robotic Arm
Built a full ROS2 pipeline where a robotic arm tracks and follows moving objects in real time using YOLOv8 for detection and ArUco markers for camera-to-workspace calibration.

`ROS2` `YOLOv8` `OpenCV` `ArUco` `TF2`

---

### LeGO-LOAM 3D LiDAR SLAM
Integrated LeGO-LOAM into an autonomous system stack for real-time 3D mapping and pose estimation using LiDAR point clouds.

`ROS2` `LiDAR` `SLAM` `Point Cloud`

---

### A* Motion Planning in ROS2
Designed and implemented a simulation-based motion planning system using the A* algorithm with dynamic obstacles in Gazebo.

`ROS2` `Gazebo` `Motion Planning` `Python`

---

## Get in touch

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Rian_Fernandes-blue?logo=linkedin)](https://linkedin.com/in/rian-archie-fernandes-924729265/)
[![Email](https://img.shields.io/badge/Email-fernandes.ri@northeastern.edu-red?logo=gmail)](mailto:fernandes.ri@northeastern.edu)
[![GitHub](https://img.shields.io/badge/GitHub-Rian013-black?logo=github)](https://github.com/Rian013)
