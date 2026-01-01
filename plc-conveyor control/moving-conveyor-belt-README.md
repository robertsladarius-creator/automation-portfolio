# PLC Conveyor Control Automation  
**Siemens TIA Portal + PLCSIM + Factory I/O**

This project demonstrates a basic industrial automation task: moving a conveyor from Point A to Point B using a Siemens PLC, simulated through TIA Portal, PLCSIM, and Factory I/O.

---

## 🎯 Objective
Design and simulate a PLC program that:

- Starts the conveyor when the **Start Pushbutton** is pressed  
- Stops the conveyor when the **Stop Pushbutton** is pressed  
- Automatically stops the conveyor when a **photo sensor** detects a box  
- Turns on the **Start PB indicator** when the conveyor is running  
- Turns on the **Stop PB indicator** when the conveyor is stopped  

---

## 🛠 Tools & Technologies
- **Siemens TIA Portal V16**  
- **Siemens PLCSIM**  
- **Factory I/O**  
- **Ladder Logic (LD)**  
- **Digital I/O (PBs, sensors, indicators)**  

---

## 🧩 Implementation Steps

### 1. Project Setup
- Loaded the provided TIA Portal template  
- Saved a new project instance  
- Switched to Project View  
- Created PLC tags based on the I/O diagram  

### 2. Ladder Logic Development
Implemented logic inside `Block_1 (FB1)`:

- Latching circuit for Start/Stop control  
- Photo sensor interlock to stop conveyor  
- Indicator lights tied to conveyor run state  

### 3. Simulation
- Compiled and loaded the program into **PLCSIM**  
- Switched PLC to **RUN** mode  
- Enabled monitoring to observe real‑time logic behavior  

### 4. Factory I/O Integration
- Loaded the matching Factory I/O scene  
- Connected Factory I/O to PLCSIM  
- Tested the system using virtual Start/Stop buttons  
- Verified conveyor behavior and sensor response  

---

## 📈 What This Demonstrates
This project highlights core automation engineering skills:

- PLC programming fundamentals  
- Realistic simulation workflow  
- Understanding of industrial I/O  
- Troubleshooting and iterative testing  
- Integration between PLC logic and 3D process simulation  

---

## 📸 Screenshots (to be added)
- Ladder Logic  
- Tag Table  
- PLCSIM in RUN mode  
- Factory I/O scene  

---

## 📂 Files Included
- Assignment instructions  
- Project notes  
- Screenshots 

---

## 🚀 Next Steps
Future improvements could include:
- Adding timers for smoother conveyor control  
- Implementing fault detection logic  
- Expanding to multi‑station conveyor systems  
