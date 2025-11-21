# 🦿 MetaMobility Lab — Carnegie Mellon University  
### **Graduate Researcher (2024–Present)**

---

## 🧭 Overview
At CMU’s **MetaMobility Lab**, I work on the hardware, control, and optimization pipeline of **lower-limb exoskeletons**.  
My research spans **PCB/electrical design**, **embedded motor control**, **mechanical prototyping**, and the development of a **human-in-the-loop CMA-ES optimization system** for adaptive assistance.

> **Goal:** Build lightweight, reliable, and personalized exoskeleton systems that assist everyday motions such as standing, sitting, lifting, and walking.

---

## 🖼️ Featured Hardware

<figure>
  <img src="/assets/Hip_Exo.png" alt="Hip Exo" width="400"/>
</figure>

---

## ⚙️ Engineering Highlights

### **Electrical & PCB Design**
- Designed custom PCBs for sensing, power routing, and motor-driver interfaces  
- Integrated IMUs, encoders, and force/torque sensors into compact wearable assemblies  
- Debugged grounding, EMI, and communication noise affecting real-time control loops  
- Developed electrical packaging and wiring harnesses for hip & knee exoskeleton testing  

---

## 📡 Custom 4-Layer Power & Signal PCB
Designed a compact **4-layer PCB** to supply high-current motor power and route all sensing/control signals cleanly between the exoskeleton hardware and the Jetson.

**Contributions**
- 4-layer stack with **dedicated power & ground planes** for noise reduction  
- Wide high-current traces with **solder-mask relief** for motor supply lines  
- Routed **Jetson GPIO, IMU lines, encoders, and motor-driver interfaces**  
- Added essential protection: **decoupling**, TVS diodes, and safe power distribution  
- Included test points and optimized connector layout for fast debugging and assembly  

**Impact**
- Reduced wiring complexity and electrical failure points  
- Lower sensor noise → more stable torque & IMU feedback  
- Cleaner integration between **Jetson, sensors, and motor drivers**

---

### **Mechanical Contributions**
- Contributed to mechanical design of **V1 & V2 hip exoskeleton prototypes**  
- Modeled joint components, wearable frames, and structural housings  
- Conducted fit checks and built complete wearable assemblies  
- Supported redesigns for improved comfort, durability, and load consistency  

---

### **Embedded Systems & Real-Time Control**
- Programmed **Teensy 4.1** firmware for knee exoskeleton actuation  
- Implemented sensor drivers, filtering, calibration, and low-latency data paths  
- Built torque assistance controllers for sit-to-stand and multi-phase motions  
- Developed logging & communication infrastructure for real-time experiments  

---

## 🔁 Human-in-the-Loop CMA-ES Optimization

### **Overview**
Implementing a **CMA-ES–based optimization pipeline** for online tuning of exoskeleton assistance parameters using human feedback and biomechanical signals.

### **Key Features**
- Real-time optimization of torque and timing parameters with **CMA-ES**  
- Cost functions combining effort reduction, comfort, and motion smoothness  
- Safe perturbation strategy for sit-to-stand and future walking tasks  
- Teensy–Simulink communication for synchronized control + data logging  
- Online parameter updates performed trial-by-trial during human testing  

### **Purpose**
Enable **personalized exoskeleton assistance** that adapts dynamically to each user’s biomechanics—no manual tuning required.

---

## 📈 Results & Impact

### **Research Outcomes**
- Delivered reliable electrical modules for multi-phase exoskeleton experiments  
- Successfully integrated CMA-ES into the sit-to-stand controller pipeline  
- Improved hip exoskeleton build consistency and structural alignment  
- Added new sensing/control features to the knee exoskeleton platform  

### **Engineering Improvements**
- Reduced wiring complexity and electrical noise  
- Improved motor-driver robustness with cleaner PCB routing  
- Enabled rapid human-in-the-loop trials via modular electronics + firmware  
- Established a reproducible data pipeline for optimization testing  

---

## 💡 Key Lessons
- Sensor grounding and filtering strongly affect controller stability  
- Wearability and alignment influence both comfort and optimization outcomes  
- Hardware, control software, and firmware must be co-designed—not isolated  
- CMA-ES converges quickly when cost functions reflect user comfort + effort  
- Rapid iteration and version control are essential for research hardware  

---

## 👤 My Roles

### **Hardware Engineer**
- Designed multi-layer PCBs and electrical subsystems for exoskeleton prototypes  
- Integrated embedded electronics and managed power/signal distribution  

### **Mechanical Engineering Contributor**
- Supported hip exoskeleton prototyping and structural assembly  
- Ensured mechanical–electrical compatibility across joints and frames  

### **Embedded Systems & Optimization Engineer**
- Developed Teensy firmware for real-time control and data collection  
- Built the **sit-to-stand assistance controller**  
- Implemented the **human-in-the-loop CMA-ES optimization pipeline**

---

[← Back to Home](/)
