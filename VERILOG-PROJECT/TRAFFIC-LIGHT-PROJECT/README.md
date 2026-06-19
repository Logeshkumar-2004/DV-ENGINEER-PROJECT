Traffic Light Controller (Verilog HDL)

Overview

This project implements a Traffic Light Controller using a Finite State Machine (FSM) in Verilog HDL.

The controller cycles through:

- RED
- YELLOW
- GREEN
- WALK

The design demonstrates FSM concepts commonly used in digital design and verification.

Features

- FSM-based design
- Sequential state transitions
- Verilog RTL implementation
- Custom testbench
- GTKWave waveform verification

Tools Used

- Verilog HDL
- Icarus Verilog
- GTKWave
- Visual Studio Code

Files

- traffic_light.v
- traffic_light_tb.v
- traffic_light.vcd

Simulation

Compile:
iverilog -o sim traffic_light.v traffic_light_tb.v

Run:
vvp sim

View Waveform:
gtkwave traffic_light.vcd

Learning Outcomes

- FSM Design
- State Transition Logic
- Testbench Development
- Waveform Analysis

Author

Logesh Kumar