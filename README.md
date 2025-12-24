# ABROB – AI-Powered Humanoid Chat Robot  
**Python • FFT Audio Processing • Vision Model • Arduino • I2C • PCA9685 Servo Control**

ABROB ( AI-Powered Humanoid Chat Robot) is a humanoid robot head prototype capable of **listening**, **seeing**, and **reacting** through audio and vision-driven behavior. It combines Python-based perception modules with Arduino-based servo actuation to simulate natural human-like interactions.

> ⚠ **Note:** Source code is intentionally omitted.  
This project is under active academic research and paper preparation. Preprint is now have been posted. 
The repo contains a overview and prototype images only.

---

##  Key Features
- **Sound direction detection** using dual-mic FFT analysis  
- **Vision-based face tracking** using Python model  
- **Naturalistic mechanical movement** (eyes + neck) via PCA9685  
- Multi-modal behavior engine combining audio & visual cues  
- Python ↔ Arduino serial communication protocol  
- Smooth servo motion with state-machine logic  
- Designed for real-time interaction & experimentation  

---

##  System Overview

The robot is divided into four core modules:

### 1️. **Audio Perception Module**
- Dual microphone input  
- FFT-based DOA (Direction-of-Arrival)  
- RMS thresholding  

### 2. **Vision Module**
- Face detection  
- Eye tracking communication engaged person in multiple person scenario   
- Stabilized gaze/attention changing algorithm  

### 3️. **Behavior Engine**
- Defines robot states:  
  - *Idle → Track (Vision + Audio) → Respond → Idle*  
- Locks direction of attention after sound detection  
 

### 4️. **Actuation Layer**
- Arduino + PCA9685  
- Controls:  
  - Neck movement to response the detected audio direction  
  - Eye movement to give attention to engaged talker  
  - Jaw movement to simulate talking 

---

##  Prototype Images

| <img src="image/Robot_Head.jpg" width="350"> |  <img src="image/Robot_Head_1.jpg" width="300"> |

---

##  Hardware Used
- **Arduino** (actuation controller)  
- **PCA9685 Servo Driver**  
- **Multiple MG995 / SG90 Servo motors**  
- **USB Camera**  
- **Dual microphone module**  
- **Host computer running Python** (perception)  

---



##  Research Context
ABROB is part of an ongoing academic research effort focused on:  
- Multi-modal sensor fusion  
- Real-time robotic interaction  
- Human-robot audio-visual communication  

Detailed algorithms & code will be released following publication.

---

##  Status
- Prototype: **Working**  
- Audio localization: **Tested successfully**  
- Vision tracking: **Functional**  
- Behavior engine: **Stable**  
- Research paper: **In preparation**

---


