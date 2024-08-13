# UART Communication Protocol & Corrector Functions on FPGA

This repository contains the implementation of a UART Communication Protocol and Corrector Functions on the Basys3 FPGA board. This project was completed as part of the ECN-300 Lab-Based Project in my 3rd year at IIT Roorkee, under the guidance of Prof. Sparsh Mittal.

## Project Overview

The primary objective of this project was to develop a robust UART communication system on an FPGA platform, capable of real-time serial data transmission. The project involved:

- **Developing the UART Communication Protocol**: Implemented on the Basys3 FPGA board to enable reliable data transfer.
- **Baud Rate Generation**: Techniques were employed to optimize data throughput, ensuring accurate timing for serial communication.
- **File Transmission and Reception**: Utilized PC serial console terminals (RealTerm and TeraTerm) to handle file transmission and reception at a specified baud rate.
- **Corrector Functions**: Integrated optimized corrector functions for error detection and correction on large bit streams.

## Tech Stack

- **FPGA Board**: Basys3
- **Software Tools**: Vivado, RealTerm, TeraTerm
- **Languages**: VHDL/Verilog

## Features

- **Real-time Serial Communication**: Efficient and reliable UART communication protocol.
- **Baud Rate Generation**: Optimized techniques to ensure consistent data throughput.
- **Error Correction**: Implementation of corrector functions to handle large bit streams with minimal errors.
- **File Transfer**: Seamless file transmission and reception using PC serial console terminals.

## Setup and Usage

### Prerequisites

- Basys3 FPGA board
- Vivado Design Suite
- Serial console terminal (e.g., RealTerm or TeraTerm)

### Steps to Implement

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/username/uart-comm-protocol-fpga.git
   cd uart-comm-protocol-fpga
