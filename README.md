# Key Tag Detector Circuit Project

**📌 Project Title:** Key Tag Detector Circuit Using Consecutive Hand Claps  
**👥 Group Members:** Me (Don Dew) and Saumya de Costa  
**📚 Course:** EC4050 - Electronic Circuits and Devices  
**📅 Year:** 2024  
**🏛️ University:** University of Jaffna, Faculty of Engineering  

---

## 📝 Project Overview

### 🎯 **Objective:**  
The aim of this project was to design a key tag detector circuit that produces a distinct tone when two consecutive hand claps are detected within a three-second duration. This innovative solution helps identify misplaced key tags through an audible alert system.

### 📋 **Requirements & Constraints:**  
- 🔋 Battery-powered circuit  
- ⏳ Tone resets after a certain time  
- 🚫 Logic gate ICs were not permitted; only 555 Timer ICs were allowed  
- ⚡ Optimized usage of electrical components, avoiding unnecessary parts  

---

## 🛠️ Circuit Design and Components

### 🔩 **Components Used:**  
- 🕑 2 x 555 Timer ICs  
- 🔧 1 x BC547 Transistor  
- 🔌 9 x Resistors (300kΩ, 100kΩ, 33kΩ + 10kΩ, 22Ω, 17kΩ)  
- ⚡ 3 x Capacitors (100µF, 10µF)  
- 🎙️ 1 x Microphone  
- 💡 2 x 12V LEDs  
- 🔔 1 x 12V Buzzer  
- 🔋 1 x 9V Battery  

### 🖥️ **Circuit Design:**  
The circuit was designed in three stages:  
1️⃣ **Simulation:** Implemented and verified using Proteus software  
2️⃣ **Breadboard Implementation:** Assembled and tested the circuit on a breadboard  
3️⃣ **PCB Design and Fabrication:** Designed using EasyEDA software and fabricated on a copper board  

---

## ⚙️ Working Principle

The key tag detector works by detecting two consecutive claps and generating an alert tone. The system operates through:

- 🎤 **Sound Detection:** A microphone captures the sound waves from hand claps  
- 🔍 **Signal Filtering:** The filtering system ensures only the sharp sound of claps is detected, eliminating background noise  
- ⏱️ **Monostable Multivibrator Operation:** Two 555 Timer ICs are configured as monostable multivibrators, each generating a pulse when triggered by a clap sound  
- 🔊 **Tone Generation:** When two pulses are detected within three seconds, the buzzer is activated, producing a distinct tone  

---

## 🛠️ PCB Design and Fabrication

**🖥️ Software:** EasyEDA  
**📜 Materials:** Copper board, photo paper, ferric chloride solution, soldering equipment  

**🛠️ Fabrication Steps:**  
1️⃣ **Circuit Path Design:** Created on EasyEDA and printed on photo paper  
2️⃣ **Transferring Circuit:** Heated and transferred the design onto the copper board using an iron  
3️⃣ **Etching:** Immersed the board in ferric chloride solution to etch the circuit path  
4️⃣ **Drilling:** Drilled holes for component placement  
5️⃣ **Soldering:** Placed and soldered the components onto the board  

---

## 🧪 Testing and Results

- 🖥️ **Simulation:** Verified correct operation in Proteus  
- 🛠️ **Breadboard:** Confirmed the real-time functionality of the circuit  
- 🛠️ **PCB:** Successfully fabricated and tested the final version  

**📊 Performance:** The circuit reliably detected two consecutive hand claps and activated the buzzer, meeting all design requirements and constraints  

---

## 🏁 Conclusion

The key tag detector circuit was successfully designed, simulated, and implemented. It provides an efficient and innovative solution for locating key tags using sound-based detection. The project allowed us to apply theoretical knowledge in a practical setting, enhancing our understanding of electronic circuit design and PCB fabrication.

