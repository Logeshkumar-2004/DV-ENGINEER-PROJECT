UART Transmitter (Verilog HDL)

Overview

This project implements a UART Transmitter in Verilog HDL.

The transmitter sends serial data using:

- Start Bit
- Data Bits
- Stop Bit

Data is transmitted in LSB-first format.

Features

- UART TX implementation
- Serial communication
- Start and Stop bit generation
- Testbench verification
- GTKWave waveform analysis

Tools Used

- Verilog HDL
- Icarus Verilog
- GTKWave
- Visual Studio Code

Files

- uart_3ip.v
- uart_3ip_tb.v
- uart-3-input.vcd

Simulation

Compile:
iverilog -o sim uart_tx.v uart_tx_tb.v

Run:
vvp sim

View Waveform:
gtkwave uart.vcd

Learning Outcomes

- UART Protocol Basics
- Serial Data Transmission
- Testbench Development
- Waveform Debugging

Author

Logesh Kumar