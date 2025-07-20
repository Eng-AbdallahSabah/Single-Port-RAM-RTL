# Single-Port RAM — RTL Design

This repository contains a synthesizable Verilog RTL implementation of a Single-Port RAM module.  
The memory is designed for FPGA/ASIC environments and supports synchronous write and asynchronous read operations.

---

## 📐 Overview

The RAM consists of 16 memory locations, each 8 bits wide.  
It is controlled by standard signals such as clock, write enable, address, and data lines.

---

## 🧠 Features

- 16x8 memory configuration (16 addresses × 8-bit word)
- Single-port interface
- Synchronous write operation
- Asynchronous read
- Fully synthesizable and ready for FPGA/ASIC use
- Suitable for educational and prototyping purposes

---

## 📁 Project Structure

Single-Port-RAM-RTL/
│
├── rtl/
│ └── ram.v # Verilog RTL design of Single-Port RAM
│
├── tb/
│ └── ram_tb.v # Testbench for verification
│
├── doc/
│ └── rtl_view.png # RTL schematic or synthesis view
│
└── README.md # Project documentation


---

## 🔬 Testbench

The testbench file `ram_tb.v` is used to simulate and verify the functional behavior of the RAM.  
It includes a set of stimulus signals to test write and read operations under different conditions.

> **Note:** You can use any simulator like [ModelSim](https://www.intel.com/content/www/us/en/software/programmable/modelsim/overview.html) or [QuestaSim](https://eda.sw.siemens.com/en-US/ic/questa/) to run the simulation.

---


## 📊 Simulation Waveform

Below is a waveform captured using **QuestaSim**, showing the write and read operations on the RAM.  
The simulation confirms correct memory behavior across different clock cycles.

![Simulation Waveform](./doc/waveform.png)


---
## 🖼️ RTL/Synthesis View

Below is an image from the RTL analysis or synthesis report:

![RTL View](https://github.com/Eng-AbdallahSabah/Single-Port-RAM-RTL/blob/main/doc/RTL%20Analysis.png)

---

## 🛠️ Future Enhancements

- Add support for configurable memory size via Verilog parameters
- Include formal verification and coverage analysis
- Add waveform snapshot from simulation

---

## 👨‍💻 Author

**Abdallah Sabah**  
B.Sc. in Electronics & Communication Engineering – Suez Canal University (2025)  
GitHub: [Eng-AbdallahSabah](https://github.com/Eng-AbdallahSabah)

---

## 📜 License

This project is released under the [MIT License](https://opensource.org/licenses/MIT). You are free to use, modify, and distribute it.
