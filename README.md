# 🤖 Autonomous Mobile Robot for Special Operations

## 📌 Project Overview
This project presents an **autonomous mobile robot** designed to support **special operations in restricted or hazardous areas**, reducing risk to human forces.  
The robot integrates **sensors, actuators, and embedded systems** to perform real-time navigation, environment mapping, and enemy detection, with a GUI for operator interaction.  

---

## 🚀 Key Features
- **Autonomous Navigation**: Real-time localization and mapping (SLAM) using **LiDAR and odometry**.  
- **Threat Detection**: Integrated **camera system** for enemy detection and visual feedback.  
- **Remote Monitoring & Control**: GUI-based interface for real-time monitoring and threat neutralization.  
- **Embedded System Integration**: Coordinated control between Raspberry Pi and Arduino boards.  

---

## 🛠️ Hardware Components
- **Raspberry Pi 4** – High-level processing and SLAM.  
- **Arduino Mega & Arduino Uno** – Motor control and sensor interfacing.  
- **LiDAR Sensor** – Mapping and obstacle detection.  
- **Camera Module** – Enemy/threat detection.  
- **DC Motors with Motor Driver** – Robot mobility.  
- **Wireless Communication Module** – Remote control and monitoring.  

---

## 💻 Software & Tools
- **Programming Languages**: Python, C, Embedded C++  
- **Frameworks/Tools**:  
  - Robot Operating System (**ROS**)  
  - SLAM algorithms (Gmapping/Cartographer)  
  - OpenCV for computer vision  
  - Arduino IDE for firmware  
  - GUI for operator interaction  

---

## ⚙️ System Architecture
1. **Raspberry Pi** handles SLAM, camera feed processing, and GUI communication.  
2. **Arduino Mega** manages motor drivers and LiDAR data acquisition.  
3. **Arduino Uno** handles additional low-level sensor inputs.  
4. Data is fused and sent back to the operator GUI for live monitoring.  

---

## 📊 Results
- Successfully tested in controlled environments with autonomous navigation and obstacle avoidance.  
- Demonstrated real-time mapping and camera-based threat detection.  
- Operator GUI provided reliable interaction for remote monitoring and decision-making.  

---

## 📸 Demo
