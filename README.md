# The-Zynq-7000-UART-Interface

## Overview
This project focuses on implementing UART interfacing using FreeRTOS on the Zybo Z7 board. It covers both polling and interrupt-driven communication methods and includes a hashing system with a proof-of-work mechanism. The project aims to provide hands-on experience with real-time operating systems, hardware-software interfacing, and hashing algorithms.

## Learning Objectives
* Implement UART communication using polling and interrupts.
* Use FreeRTOS queues for inter-task communication.
* Understand hashing functions and their applications.
* Develop a proof-of-work mechanism for data verification.

## Hardware Requirements
* Zybo Z7 development board with Zynq-7000 SoC.
* UART interface for serial communication.
* Input devices for user interaction (e.g., keyboard).
* Output devices for system feedback (e.g., terminal window).

## Software Requirements
* Xilinx Vivado for hardware configuration.
* Xilinx SDK for software development.
* FreeRTOS library for real-time task management.
* Hashing library (e.g., SHA-256 implementation).

## Project Structure
### Part 1: Basic Hashing System Using Polling
* Implement a text hashing and verification system using UART polling.
* Utilize FreeRTOS tasks for input processing, hashing, and output display.
* Include a proof-of-work task for computational challenge verification.

### Part 2: Interrupt-Driven Input and Output
* Enhance the UART driver with interrupt handling for improved efficiency.
* Implement receive and transmit functions using interrupt service routines (ISRs).
* Manage data queues for seamless communication between tasks and UART.

## How to Run
* Clone the repository to your local machine.
* Open the project in Xilinx Vivado and SDK.
* Configure the hardware design for Zybo Z7 and generate the bitstream.
* Create a new FreeRTOS application project in SDK.
* Include the provided source files for each part of the lab.
* Compile and build the project.
* Upload the generated executable to the Zybo Z7 board.
* Connect a serial terminal to the UART interface of the board for input/output.
* Power on the board and interact with the system via the terminal.
* Follow the on-screen instructions to use the hashing and proof-of-work features.
