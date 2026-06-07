<img width="720" alt="fpga_board" src="https://github.com/user-attachments/assets/3de4f929-a596-4f0e-be4d-c33b3238710f" />
# FPGA AND Gate using VHDL

This project demonstrates a simple AND logic gate implemented on a Xilinx FPGA board using VHDL and Xilinx ISE Design Suite.

## Overview

The design uses two onboard switches as inputs and one LED as output.

The LED turns ON only when both switches are activated.

## Technologies Used

* VHDL
* Xilinx ISE Design Suite
* FPGA Development Board

## Project Structure

```bash
src/
constraints/
images/
video/
```

## Files Description

* `and_gate.vhd` → Main VHDL design file
* `and_gate.ucf` → FPGA pin constraints file
* `images/` → FPGA board pictures
* `video/` → Hardware demonstration video

## FPGA Design Flow

```text
VHDL Code
   ↓
Synthesis
   ↓
Implementation
   ↓
Bitstream Generation
   ↓
FPGA Programming
```

## Truth Table

| SW0 | SW1 | LED0 |
| --- | --- | ---- |
| 0   | 0   | 0    |
| 0   | 1   | 0    |
| 1   | 0   | 0    |
| 1   | 1   | 1    |

## Hardware Demonstration

This project was originally implemented during a university FPGA laboratory session using Xilinx ISE Design Suite.

The repository recreates the project structure and documents the hardware experiment using real FPGA board images and testing videos.

## Author

Computer Systems Engineering Student
Embedded Systems & IoT Enthusiast
