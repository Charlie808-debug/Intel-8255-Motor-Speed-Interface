# Intel-8255-Motor-Speed-Interface
Motor Speed Monitoring and Direction Detection using Intel 8255 Programmable Peripheral Interface and LCD Display
# Intel-8255-Motor-Speed-Interface

![8086](https://img.shields.io/badge/8086-Microprocessor-blue?style=for-the-badge)
![8255](https://img.shields.io/badge/8255-PPI-success?style=for-the-badge)
![Assembly](https://img.shields.io/badge/Assembly-Language-red?style=for-the-badge)
![Proteus](https://img.shields.io/badge/Proteus-Simulation-orange?style=for-the-badge)
![LCD](https://img.shields.io/badge/16x2-LCD-green?style=for-the-badge)
![L293D](https://img.shields.io/badge/L293D-H--Bridge-purple?style=for-the-badge)

> 🚀 Completed Academic Project | Microprocessors | Peripheral Interfacing | Embedded Systems

---

# Overview

This project demonstrates the design and implementation of an **8086-based DC Motor Speed Monitoring and Direction Control System** using the **8255 Programmable Peripheral Interface (PPI)**.

Developed as part of the **Computer Design and Applications** course under the guidance of **Dr. Mahesh Kumar**, the system interfaces an 8086 processor with two 8255 PPIs, an L293D motor driver, and a 16×2 LCD to perform real-time motor control and speed visualization within Proteus.

---

# Features

- Real-time DC motor speed monitoring
- Clockwise and Anti-clockwise direction control
- Signed speed display on a 16×2 LCD
- PWM-based software speed regulation
- Dual Intel 8255 PPI architecture
- I/O-Mapped I/O implementation
- Address decoding using 74HC373 latch
- Proteus-based hardware simulation

---

# Hardware Components

- Intel 8086 Microprocessor
- Intel 8255A Programmable Peripheral Interface (2×)
- L293D H-Bridge Motor Driver
- 74HC373 Address Latch
- 16×2 LCD Display
- DC Motor
- Push Buttons
- Proteus Design Suite

---

# System Architecture

The system follows an **I/O-Mapped I/O architecture**, where the 8086 communicates with external peripherals using **IN** and **OUT** instructions.

- **8255 (U3)** handles motor control and switch inputs.
- **8255 (U6)** manages LCD communication.
- **74HC373** demultiplexes the address/data bus.
- **L293D** drives the DC motor.
- **16×2 LCD** displays real-time signed motor speed.

---

# Working Principle

1. Configure both 8255 PPIs.
2. Initialize the LCD.
3. Continuously poll user switches.
4. Determine motor direction.
5. Generate PWM for speed control.
6. Update LCD with signed speed.
7. Repeat the control loop.

---

# Project Outcomes

- Designed an 8086-based embedded control architecture.
- Configured Intel 8255 PPI in Mode 0.
- Implemented PWM-based speed regulation.
- Controlled motor direction through L293D.
- Displayed signed real-time motor speed.
- Strengthened understanding of microprocessor interfacing and hardware debugging.

---

# Applications

- Embedded Systems Education
- Microprocessor Laboratories
- Industrial Motor Control
- Peripheral Interfacing
- Digital Control Systems

---

# Project Structure

```
Intel-8255-Motor-Speed-Interface
│
├── docs/
├── firmware/
├── report/
└── README.md
```

---

# Contributors

- Dhruvi Singh
- Kahaan Padiya
- Anurag Tripathi

Guided by **Dr. Mahesh Kumar**

---
