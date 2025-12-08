# 🦿 MetaMobility Lab — Carnegie Mellon University  
### **Graduate Researcher (2024–Present)**

---

# 🧭 Introduction

Lower-limb exoskeletons have significant **social value** in rehabilitation, workplace injury prevention, and mobility assistance for individuals with reduced strength. Improving comfort, transparency, and reliability directly affects how well users adopt wearable robotics in everyday life.

This project focuses on developing the **hardware, control systems, and human-in-the-loop optimization** required for a next-generation hip and knee exoskeleton platform at CMU’s MetaMobility Lab.  
**Objective:** Build lightweight, reliable, and personalized exoskeleton systems that assist common motions such as standing, sitting, lifting, and walking.

---

# 🖼️ Featured Hardware

<img src="/assets/Hip_Exo.png" alt="Hip Exo" width="400"/>

---

# 🛠️ Design / Methods

## ⚡ Electrical & PCB Design

I designed custom electrical systems that support sensing, motor control, and data acquisition for the hip and knee exoskeleton prototypes.

### **Advanced 4-Layer Power & Signal PCB**
- 4-layer stack with **dedicated power/ground planes** for noise reduction  
- High-current motor supply lines with **wide traces + solder-mask relief**  
- Routing for **Jetson GPIO, IMU signals, encoders, and motor drivers**  
- Added surge protection (TVS), decoupling, and robust connector layout  
- Integrated test points for fast debugging and version-controlled updates

**Impact:** Reduced wiring complexity, lower sensor noise, and more stable real-time control loops.

---

## 🧩 Mechanical System Contributions
- Modeled and refined **V1 & V2 hip exoskeleton joint assemblies**  
- Performed tolerance checks and full wearable assembly integration  
- Improved structural alignment, comfort, and load consistency  
- Built and tested complete prototypes for multi-phase motion tasks  

---

## 🧠 Embedded Systems & Real-Time Control
- Developed **Teensy 4.1** firmware for knee exoskeleton actuation  
- Implemented filtering, calibration routines, sensor drivers, and IMU/encoder fusion  
- Built torque-assistance controllers for sit-to-stand and multi-phase tasks  
- Created the full logging + communication pipeline for human trials  

---

## 🔁 Human-in-the-Loop CMA-ES Optimization

### **Overview**
Implemented a **CMA-ES–based optimization pipeline** that tunes assistance parameters in real time using human feedback, minimizing effort and improving comfort.

### **Methods**
- Real-time CMA-ES updates to torque magnitude and timing  
- Cost functions combining metabolic effort proxies, user comfort, and motion smoothness  
- Safe perturbation strategy for sit-to-stand and future walking tasks  
- Synchronized Teensy–Simulink communication for online optimization  

**Purpose:** Enable **personalized, adaptive assistance** without manual tuning.

---

# 📈 Evaluation / Results

### **Effectiveness of the Electrical System**
- New 4-layer PCB reduced wiring failures and improved reliability during multi-day trials  
- Lower EMI and cleaner sensor lines → improved torque tracking stability  
- Enhanced integration between Jetson, sensing units, and motor drivers

### **Effectiveness of the Control & Optimization Pipeline**
- CMA-ES successfully converged to improved assistive parameters within a small number of trials  
- Sit-to-stand controller produced smooth, consistent torque profiles  
- Firmware and data pipeline supported rapid iteration during human testing

### **Mechanical & System-Level Impact**
- Improved joint alignment reduced mechanical friction and enhanced user comfort  
- Modular hardware allowed for fast swapping of sensors and actuators  
- Overall system became more reproducible and easier to debug across different test sessions

---

# 🧾 Conclusion

This project demonstrates the integration of **mechanical design**, **embedded systems**, **PCB/electrical engineering**, and **advanced control/optimization** in a wearable robotics research environment.  
The resulting hardware and firmware systems significantly improved reliability, reduced noise, and enabled **real-time CMA-ES human-in-the-loop optimization**, advancing the lab’s exoskeleton experimental capabilities.

---

# 👤 My Role

### **Hardware Engineer**
- Designed multi-layer PCBs and electrical subsystems  
- Integrated sensing, power, and communication hardware  

### **Mechanical Engineering Contributor**
- Supported prototyping and structural assembly for hip exoskeletons  
- Ensured mechanical-electrical compatibility across joints and frames  

### **Embedded Systems & Optimization Engineer**
- Programmed Teensy firmware for real-time control  
- Built the sit-to-stand torque-assistance controller  
- Implemented the full CMA-ES optimization pipeline  

---

# 🧩 Skills Demonstrated
- Mechatronics integration  
- Motor control (FOC, impedance control)  
- Embedded systems (Teensy, IMUs, encoders)  
- PCB design (4-layer boards, power distribution)  
- MATLAB / Simulink / Python  
- Optimization (CMA-ES)  
- Mechanical design and prototyping  

---

[← Back to Home](/)
