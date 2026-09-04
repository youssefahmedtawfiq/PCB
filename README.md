# STM32 Sensor Interface & Power Management Board

## 📌 Project Overview
This repository contains the hardware design files for a custom, compact **40x40 mm** Sensor Interface and Power Management PCB. It is specifically designed to provide stable power and clean, noise-free sensor signal interfacing for the **STM32 Blue Pill** microcontroller.

## ✨ Key Features
* **Dual Power Regulation:**
  * **Adjustable Output:** Uses an `LM317T` adjustable voltage regulator equipped with a heatsink for efficient thermal dissipation.
  * **3.3V Dedicated Output:** Uses an `AMS1117-33` regulator to supply stable 3.3V specifically for the STM32 MCU.
* **Hardware Protection:** Integrated fuse on the 3.3V line to protect the microcontroller from overcurrent conditions.
* **Dual Sensor Interface (2 Channels):**
  * **Noise Reduction:** Hardware RC filters implemented on the sensor data lines to eliminate high-frequency noise.
  * **Stability:** 10kΩ pull-down resistors are added to the sensor inputs to prevent floating pins and ensure reliable default logic states.
* **Design Standards:** 100% DRC (Design Rule Check) error-free.

## 📷 Board Visuals

*(Note: The images below showcase the schematic and the final PCB layout)*

### Schematic Design
![Schematic](Job2_page-0001.jpg)

### 2D PCB Layout Top
![2D Layout](Job2_page-0002.jpg)

### 2D PCB Layout Bottom
![2D Layout](Job2_page-0003.jpg)

### 3D View (Top)
![3D Top View](Job2_page-0005.jpg)

### 3D View (Bottom)
![3D Bottom View](Job2_page-0004.jpg)

## 🛠️ EDA Tool Used
* Altium Designer

## 👨‍💻 Author
**Youssef Ahmed Sayed**
