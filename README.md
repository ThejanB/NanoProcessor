# Nanoprocessor Design Project

## Table of Contents
- [Introduction](#introduction)
- [Team Members](#team-members)
- [Project Description](#project-description)
- [Instructions](#instructions)
- [Components](#components)
- [Simulation and Testing](#simulation-and-testing)
- [Results](#results)
- [Conclusion](#conclusion)


## Introduction
This repository contains the project report and design files for a 4-bit nanoprocessor developed by Group 44. The nanoprocessor is capable of executing four basic instructions and includes memory for eight such instructions.

## Team Members
- A.S. Jayathunga (200265T)
- M.R.A.A.K. Gunasinghe (200196G)
- K.A. Anshan Lahiru Kavinda (200300A)
- K.K.A.J.S. Kumarasinghe (200323V)
- W.M.T.B. Weerasekara (200698X)

## Project Description
The goal of this project was to design a 4-bit processor capable of executing four basic instructions: ADD, NEG, MOVI, and JZR. The processor includes memory for eight instructions, and it was verified by running an assembly program to calculate the sum of numbers from 1 to 3. The program's final result is displayed on a seven-segment display, and two output flags indicate whether the value is zero and if an overflow condition occurs.

## Instructions
- [Assembly program and machine code](assembly_and_machine_code.md)
- [Top-level design](top_level_design.md)
- [Simulation and testing](simulation_and_testing.md)

## Components
- [Program Counter](program_counter/)
- [3-bit Ripple Carry Adder](ripple_carry_adder/)
- [Program ROM](program_rom/)
- [Instruction Decoder](instruction_decoder/)
- [Arithmetic Unit](arithmetic_unit/)
- [8-way 4-bit Multiplexer](8_way_mux/)
- [2-way 3-bit Multiplexer](2_way_3_bit_mux/)
- [2-way 4-bit Multiplexer](2_way_4_bit_mux/)
- [Register Bank](register_bank/)
- [Nanoprocessor](nanoprocessor/)

## Simulation and Testing
We conducted extensive simulations and testing to verify the functionality of each component and the entire nanoprocessor. Detailed information can be found in the [simulation_and_testing](simulation_and_testing.md) section.

## Results
The nanoprocessor successfully executed the assembly program to calculate the sum of numbers from 1 to 3, displaying the result on the seven-segment display. Detailed results and timing diagrams are provided in the [simulation_and_testing](simulation_and_testing.md) section.

## Conclusion
In conclusion, this project demonstrated the design and implementation of a 4-bit nanoprocessor capable of executing basic instructions and storing programs in memory. Future improvements and considerations for expanding the processor's capabilities are discussed in the report.

