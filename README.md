# Project 004: UART Transmitter using Verilog HDL

## Overview

This project implements a UART (Universal Asynchronous Receiver Transmitter) Transmitter using Verilog HDL.

UART is one of the most widely used serial communication protocols in embedded systems and digital hardware applications.

## Features

- UART transmission logic
- Start bit generation
- Stop bit generation
- 8-bit data transmission
- Verilog HDL implementation
- Simulation-ready architecture

## Architecture

                +------------------+
Data[7:0] ----->|                  |
                | UART Transmitter |-----> TX
TX_START ------>|                  |
                +------------------+
                         ^
                         |
                       Clock

## Files

| File | Description |
|--------|--------|
| uart_tx.v | UART transmitter module |
| uart_tx_tb.v | UART simulation testbench |

## Applications

- Embedded Systems
- FPGA Development
- Serial Communication
- Microcontroller Interfaces
- Digital Hardware Design

## SiliconSprint Labs

Embedded Systems • Digital Design • Semiconductor Technology
