# STM32 3-Phase PWM Generator ⚡

A **STM32-based 3-Phase PWM Generator** for precise, real-time control of sinusoidal PWM signals with a **2π/3 phase shift**.  
Designed for **motor control, power electronics experiments, and embedded systems**, this project features an intuitive user interface, a potentiometer for adjusting duty cycle, and a **16x2 LCD** to display real-time values.

---

## ⚙️ Key Features

- **STM32-based PWM generation** for three-phase systems  
- **Real-time duty cycle adjustment** via potentiometer  
- **16x2 LCD interface** to display current duty cycle  
- Output and ground pins for easy measurement using oscilloscopes or probes  
- Compact, portable design with secure STM32 housing  
- Adjustable duty cycle and frequency  
- Ideal for educational use, experimentation, and embedded systems learning  

---

## 🏗 Design Overview

The system is designed for both usability and precision. Key components include:

1. **STM32 Microcontroller** – generates three-phase PWM signals  
2. **USB port** – for powering and communication  
3. **Ground pins** – for measurement reference  
4. **Output pins** – for accessing PWM signals  
5. **Output status indicators** – show the signal state  
6. **LCD display** – shows duty cycle in real-time  
7. **Potentiometer** – for adjusting duty cycle  
8. **Compact housing** – protects the STM32 and components  

> The PWM output can be easily measured with oscilloscope probes or crocodile clips for testing and verification.

---

## 📁 Project Structure

```plaintext
stm32-3phase-pwm-generator/
├── src/
│   └── SourceCode.zip          # Full STM32CubeIDE project
├── docs/
│   ├── USERMANUAL.pdf          # Detailed user manual
│   ├── rapport.pdf             # Project report
│   ├── pinout.txt              # Pin connections and wiring
│   └── simulation.mp4          # Demo video
├── README.md
└── LICENSE
