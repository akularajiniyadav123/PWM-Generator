# PWM Generator Using Verilog HDL

## Overview

This project implements a Pulse Width Modulation (PWM) Generator using Verilog HDL. PWM is a technique used to control power delivered to electrical devices by varying the duty cycle of a digital signal while maintaining a constant frequency.

## Features

* Adjustable Duty Cycle
* 8-bit Counter-Based Design
* PWM Signal Generation
* Verilog HDL Implementation
* Testbench Verification

## Files

* `pwm_generator.v` – PWM generator design
* `pwm_generator_tb.v` – Testbench file
* `simulation_results.png` – Waveform screenshot

## Working Principle

The PWM generator compares a counter value with the desired duty cycle value.

* If Counter < Duty Cycle → Output HIGH
* If Counter ≥ Duty Cycle → Output LOW

This creates a PWM waveform whose duty cycle can be adjusted dynamically.

## Duty Cycle Examples

| Duty Cycle Value | Percentage |
| ---------------- | ---------- |
| 64               | 25%        |
| 128              | 50%        |
| 192              | 75%        |

## Tools Used

* Verilog HDL
* ModelSim
* Icarus Verilog
* GTKWave

## Simulation Procedure

1. Compile the Verilog design and testbench.
2. Run the simulation.
3. Open the waveform viewer.
4. Observe PWM output for different duty cycles.

## Applications

* DC Motor Speed Control
* LED Brightness Control
* Power Electronics
* Servo Motor Control
* FPGA-Based Embedded Systems

## Results

The PWM generator successfully produces pulse-width-modulated waveforms with varying duty cycles of 25%, 50%, and 75%, demonstrating accurate PWM signal generation.

## Author

Akula Rajini Yadav

B.Tech – Electronics and Communication Engineering (ECE)
