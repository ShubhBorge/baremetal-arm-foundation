# Bare-Metal ARM Cortex-M Foundation

This repository contains hands-on bare-metal firmware experiments on ARM Cortex-M
microcontrollers. The focus is on register-level programming using Embedded C,
without relying on high-level abstraction libraries.

The objective is to build a strong foundation in MCU internals, interrupts,
timers, and low-level firmware design required for industrial and automotive
embedded systems.

---

## 🎯 Objectives
- Understand ARM Cortex-M architecture basics
- Write register-level drivers (no Arduino-style abstraction)
- Configure GPIO, timers, and interrupts
- Develop interrupt-driven firmware
- Gain confidence reading datasheets and reference manuals

---

## 🛠️ Target Platform
- ARM Cortex-M based microcontroller (STM32 / NXP LPC family)
- Toolchain: GCC / vendor IDE
- Debugger: SWD / JTAG

---

## 📂 Repository Structure
baremetal-arm-foundation/
├── src/ # Source files
├── inc/ # Header files
├── docs/ # Documentation and notes
└── README.md

---

## 🧪 Experiments (Planned)
1. GPIO control using register-level access  
2. Timer configuration and periodic interrupts  
3. External interrupt handling  
4. Interrupt latency observation  
5. Basic system clock configuration  

Each experiment includes:
- Clear problem statement
- Firmware design explanation
- Code implementation
- Observations and learnings

---

## 🧠 Key Learnings
- MCU startup and reset behavior
- Difference between polling and interrupt-driven systems
- Importance of volatile, memory mapping, and bit manipulation
- Debugging using breakpoints and registers

---

## 📌 Notes
This repository is part of a structured learning path towards becoming an
embedded firmware engineer, with a focus on power and industrial systems.

---

## 👤 Author
**Shubham Borge**  

