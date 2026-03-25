# STM32 B-L4S5I-IOT01A Discovery Projects

This repository contains firmware, sensor interfacing projects, and technical documentation for the **B-L4S5I-IOT01A** (Discovery kit for IoT node).


## 🛠 Hardware Overview
The heart of this board is the **STM32L4S5VI** microcontroller[cite: 1, 2].
* **Architecture:** Arm® Cortex®-M4 core with FPU and DSP instructions[cite: 7].
* **Performance:** Up to 120 MHz CPU frequency[cite: 8].
* **Memory:** 2 MB of Flash memory and 640 KB of SRAM[cite: 9, 10].
* **Accelerators:** Includes the ART Accelerator, Chrom-ART Accelerator, and a hardware encryption engine (AES/HASH)[cite: 11].

## 📡 Connectivity & IoT Features
This board is a "self-contained IoT node" with massive wireless support[cite: 32]:
* **Wi-Fi:** Inventek ISM43362-M3G-L44 module[cite: 20].
* **Bluetooth:** Bluetooth® V4.1 module (SPBTLE-RF)[cite: 20].
* **NFC:** Dynamic tag with a printed PCB antenna[cite: 21].
* **Sub-GHz:** 815-915 MHz RF module[cite: 29].

## 🌡 Integrated Sensors
The board features a full suite of MEMS sensors[cite: 31]:
* **Motion:** 3D accelerometer, 3D gyroscope (LSM6DSL), and 3-axis magnetometer (LIS3MDL)[cite: 33].
* **Environment:** Humidity/Temperature (HTS221) and Barometer (LPS22HB)[cite: 34].
* **Distance:** FlightSense™ time-of-flight and gesture detection (VL53L0X)[cite: 35].
* **Audio:** Two digital omnidirectional microphones[cite: 36].

## 🔌 Expansion
* **Arduino™ Uno V3** and **Pmod** connectors for easy hardware expansion[cite: 51].
* **ST-LINK/V2-1** on-board debugger for drag-and-drop programming[cite: 71, 75, 68].

## Helpful Links 
* https://docs.zephyrproject.org/latest/boards/st/b_l4s5i_iot01a/doc/index.html

---
*Maintained by Dhiraj 