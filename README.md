# Automatic Lamp with Light Sensor

## 📖 Overview
This project demonstrates an **intelligent lighting system** that automatically activates in low-light conditions.  
It was developed as part of a **Physics Class 12 Final Project**, showcasing practical applications of **semiconductor physics, resistive networks, and transistor switching**.

The system uses a **Light Dependent Resistor (LDR)** to detect ambient light intensity. When darkness is detected, the LDR’s resistance increases, triggering a **transistor switch** that powers the LED lamp. This simulates an automatic lamp system that responds to environmental changes without manual input.

---

## ⚙️ Components Used
- **9V Battery** – power supply  
- **Breadboard** – circuit assembly platform  
- **Photoresistor (LDR)** – ~5kΩ in light, 200kΩ+ in dark  
- **Transistor BC547 (NPN)** – switching element  
- **Resistor 100 kΩ** – biasing resistor for transistor base  
- **Resistor 470 Ω** – current limiting resistor for LED  
- **Light-Emitting Diode (LED)** – output indicator lamp  
- **Jumper wires** – connections between components  

---

## 🔬 Working Principle
1. **Light Detection**  
   - In bright conditions, the LDR has low resistance.  
   - Current flows through the LDR, keeping the transistor off, so the LED remains off.  

2. **Darkness Detection**  
   - In darkness, the LDR’s resistance increases.  
   - This changes the voltage across the transistor’s base, switching it on.  
   - The transistor allows current to flow to the LED, turning it on automatically.  

3. **Automation**  
   - The circuit continuously adjusts based on ambient light, requiring no manual control.  

---

## 🛠️ Circuit Diagram
*(Insert circuit diagram image here if available)*

---

## 🚀 Applications
- Automatic street lighting  
- Smart home lighting systems  
- Energy-efficient illumination  
- Security lighting  

---

## 📸 Prototype
Final version housed inside a **cardboard box** with:  
- Battery holder (positive terminal currently disconnected for testing)  
- Breadboard circuit with LDR, transistor, resistors, and LED  
- Jumper wires connecting power rails and components  

---

## 🧑‍💻 Skills Demonstrated
- Circuit design & assembly  
- Sensor calibration  
- Transistor biasing & switching  
- Practical electronics troubleshooting  
- Physics-to-real-world application  

---

## 📚 Project Context
- **Event**: Physics Class 12 Final Project  
- **Purpose**: To demonstrate how resistors, sensors, and transistors can be combined to create an **automatic lamp system**.  

---

## 📺 Reference
This project was inspired and guided by the tutorial:  
[How To Build An Automatic Night-Light – YouTube](https://www.youtube.com/watch?v=mHBG2sBcyTM)

Credit to the original creator for demonstrating the core concept of using an LDR and transistor to automate lamp control. My prototype builds on this foundation with additional documentation, testing, and presentation for academic purposes.
