# Johnson Counter Using Verilog HDL

## Overview

This project implements a 4-bit Johnson Counter using Verilog HDL. A Johnson Counter, also known as a Twisted Ring Counter, is a modified shift register where the complement of the last flip-flop output is fed back to the input of the first flip-flop.

## Features

* 4-bit Johnson Counter
* Asynchronous Reset
* Sequential Logic Design
* Verilog HDL Implementation
* Testbench Verification

## Files

* `johnson_counter.v` – Johnson Counter design
* `johnson_counter_tb.v` – Testbench file
* `simulation_results.png` – Simulation waveform screenshot

## Working Principle

The complemented output of the last stage is fed back to the first stage, producing a sequence of 2N states for an N-bit counter.

### State Sequence

0000 → 0001 → 0011 → 0111 → 1111 → 1110 → 1100 → 1000 → 0000

For a 4-bit Johnson Counter:

* Number of Flip-Flops = 4
* Total States = 2 × 4 = 8

## Tools Used

* Verilog HDL
* ModelSim
* Icarus Verilog
* GTKWave

## Simulation Procedure

1. Compile the Verilog files.
2. Run the simulation.
3. Open the waveform viewer.
4. Verify the Johnson counter sequence.

## Applications

* Frequency Division
* Sequence Generation
* Digital Timing Circuits
* State Machines
* FPGA and ASIC Designs

## Results

The Johnson Counter successfully generates eight unique states before repeating, confirming correct twisted-ring counter operation.

## Author

Akula Rajini Yadav

B.Tech – Electronics and Communication Engineering (ECE)
