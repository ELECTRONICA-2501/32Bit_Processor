# 32-bit RISC MIPS Processor

## Project Overview

This project involves designing a 32-bit RISC MIPS Processor with a 5-stage pipeline: IF (Instruction Fetch), ID (Instruction Decode), EX (Execute), MEM (Memory Access), and WB (Write Back). The objective is to implement R-type, I-type, and J-type instructions using VHDL. The project provides students with practical experience in FPGA design and a deep understanding of processor architecture, instruction sets, and digital design.

## Table of Contents
- [Abstract](#abstract)
- [Introduction](#introduction)
- [Design](#design)
- [Test Results](#test-results)
- [Concluding Remarks](#concluding-remarks)
- [Appendices](#appendices)

## Abstract
In this project, students delve into the intricacies of processor architecture by implementing a 32-bit RISC MIPS processor. The hands-on experience with VHDL and FPGA design provides a foundation for understanding complex digital systems, including multiplexer design, instruction sets, and functional components required for full processor development.

## Introduction
The project focuses on designing a 32-bit processor that can handle R-type, I-type, and J-type instructions. The implementation involves building a datapath for a 5-stage pipeline, ensuring smooth execution across each stage. Each component, such as the Arithmetic Logic Unit (ALU), is carefully crafted to lay a strong foundation for a functional MIPS processor.

## Design
The processor's pipeline consists of five stages (IF, ID, EX, MEM, WB), each modeled structurally in VHDL. Each stage is tested individually using a testbench for thorough validation. The stages are interconnected under a `CPU` structural model, ensuring modular development and testing. Components include PCMUX, Instruction Memory, ALU, RegFile, and more, each contributing to the overall pipeline.

## Test Results
Various simulations were conducted to test the functionality of each stage and component. The following tests were performed:
- Shift Left by 2
- ALU Control
- Control Unit
- Data Memory
- SignExtend
- PC
- ALU
- RegFile
- ID, EX, MEM, WB stages
- Processor Testbench

## Concluding Remarks
This project demonstrates the significance of the 5-stage MIPS pipeline in creating a structured framework for seamless instruction execution. By focusing on the pipeline design without memory management complexities, a robust foundation was established for the processor, with the potential for further expansion and refinement.

## Appendices
The appendix contains the VHDL code for various components of the MIPS processor, including the ALU, Control Unit, Memory, Register File, and individual testbenches.
