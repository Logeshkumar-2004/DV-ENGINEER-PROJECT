4-Bit ALU (Arithmetic Logic Unit)

Overview

This project implements a 4-Bit Arithmetic Logic Unit (ALU) using Verilog HDL.

The ALU performs arithmetic and logical operations based on a control signal.

Operations Supported

Select| Operation
000| ADD
001| SUB
010| AND
011| OR
100| NAND
101| NOR
110| XNOR

Features

- Combinational logic design
- Multiple arithmetic and logic operations
- Self-checking testbench
- GTKWave verification

Tools Used

- Verilog HDL
- Icarus Verilog
- GTKWave
- Visual Studio Code

Files

- alu.v
- alu_tb.v
- alu.vcd

Simulation

Compile:
iverilog -o sim alu.v alu_tb.v

Run:
vvp sim

View Waveform:
gtkwave alu.vcd

Learning Outcomes

- ALU Design
- Case Statements
- Functional Verification
- Self-Checking Testbench

Author

Logesh Kumar