# FPGA-Ping-Pong-Game
A hardware implementation of the classic Ping Pong game on an FPGA board using Vivado.

## Overview
This project implements a classic **Ping Pong game** on the **FPGA development board Basys 3 Master (Artix-7)** using **Vivado**. The game is written in **Verilog/VHDL** and runs entirely in hardware. The output is displayed on a **7-segment display**, and the paddles are controlled using buttons on the FPGA board.

The project demonstrates how **digital logic, timing control, and hardware description languages** can be used to create a real-time interactive game system on an FPGA.

## Features
- Classic Pong gameplay
- 7-segment display output
- Paddle control using FPGA board buttons
- Ball movement and collision detection implemented in hardware
- Score tracking
- Real-time game logic implemented with synchronous digital design

## Hardware Requirements
- FPGA development board Basys 3 Master

## Software Requirements
- Vivado Design Tool
- FPGA board drivers
- Hardware description language support (Verilog or VHDL)

## Pong Game Logic
Implements the core functionality of the game:
- Ball movement
- Collision detection with paddles
- Collision detection with screen boundaries
- Score updates

## How to Run the Project
1. Open **Vivado**.
2. Create a new project or open the provided project files
3. Add the source files and constraints file (`.xdc`)
4. Synthesize and implement the design
5. Generate the bitstream
6. Program the FPGA board
7. Start playing

## Learning Objectives
Through this project, the following concepts can be explored:
- FPGA design using **Verilog/VHDL**
- VGA signal generation
- Finite State Machines (FSM)
- Synchronous digital design
- Hardware-based game logic

## Authors
- Student project developed for the **Systems with Digital Integrated Circuits** course.
