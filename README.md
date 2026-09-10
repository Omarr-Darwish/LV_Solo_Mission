
# LV Solo Mission - Low Voltage Task

This repository contains the hardware design and embedded software implementation for the Low Voltage task. 

## 🛠️ 1. Hardware Design (PCB)
The printed circuit board was designed using **Altium Designer**. The project includes the complete schematic capture, PCB layout, and generated Gerber files.

**Schematic View:**




<img width="1241" height="880" alt="image" src="https://github.com/user-attachments/assets/22405ada-53c3-4502-9983-66bb77142c6f" />


**PCB 3D View / Layout:**




<img width="1105" height="710" alt="image" src="https://github.com/user-attachments/assets/9c0fd85c-c556-42d7-9406-2f28d9cb1926" />


----------

## 💻 2. Embedded Software (STM32)
The embedded firmware was developed using **STM32CubeIDE** targeting the `STM32F103C8` microcontroller.

* **Mission 1:** GPIO configuration and implementation of an LED Toggle on pin `PC13`.
* **Mission 2:** ADC sensor reading and serial data transmission via UART.


----------

## 📁 Repository Structure
* `AltiumSTM32_ExamplePCB/`: Contains all Altium Designer project files.
* `Low Voltage.rar`: Compressed archive containing the complete STM32CubeIDE workspace , Altium Designer project and Report flie.
