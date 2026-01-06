RV32I RISC-V Processor Core (Verilog)

>>OVERVIEW

This repository contains a fully synthesizable RV32I RISC-V processor core implemented in Verilog HDL.
The design supports the complete RV32I base integer instruction set (39 instructions) and follows the official RISC-V ISA specification. Architectural concepts are derived from Digital Design and Computer Architecture (RISC-V Edition).

The core is suitable for educational use, FPGA prototyping, and extension toward custom System-on-Chip (SoC) designs

>>KEY FEATURES

Fully synthesizable RV32I processor core

Modular and readable Verilog HDL

Complete RV32I base integer instruction set

32-bit datapath and register file

Separate Control Unit and Datapath

FPGA-ready RTL design

Designed for extensibility

>>SUPPORTED INSTRUCTIONS 

The processor implements all 39 RV32I base integer instructions, grouped as follows:

Arithmetic & Logical
ADD, SUB, AND, OR, XOR, SLT, SLTU

Immediate Instructions
ADDI, ANDI, ORI, XORI, SLTI, SLTIU

Shift Instructions
SLL, SRL, SRA, SLLI, SRLI, SRAI

Load / Store
LW, SW

Branch Instructions
BEQ, BNE, BLT, BGE, BLTU, BGEU

Jump Instructions
JAL, JALR

Upper Immediate
LUI, AUIPC

///THESE ARE THE SUPPROTED INSTRUCTIONS WITH ADDRESS



