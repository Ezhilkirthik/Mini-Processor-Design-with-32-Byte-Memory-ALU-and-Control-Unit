# 🖥️ Mini Processor Design with 32-Byte Memory, ALU, and Control Unit
A fully functional mini-processor built in Proteus, integrating a 32-byte memory module, Arithmetic Logic Unit (ALU), and a custom control unit. The project demonstrates how basic processors fetch, decode, and execute instructions while managing data flow between memory and computational blocks.

---

## 📘 Overview
This project implements a simplified processor architecture suitable for learning and demonstration.  
It includes:

- **Custom RAM (32 bytes)** for program & data storage  
- **ALU** capable of basic arithmetic and logical operations  
- **Control Unit** for instruction decoding & execution flow  
- **Instruction Cycle** (Fetch → Decode → Execute)  
- **Proteus Simulation** for visual understanding and testing  

This design helps learners understand how processors operate at the digital logic level.

---

## 🏗️ System Architecture

### 🔹 1. Memory (32-Byte RAM)
- Stores both instructions and data  
- Supports read/write operations  
- Address-driven memory access  

### 🔹 2. Arithmetic Logic Unit (ALU)
Supports key operations:
- Addition
- Subtraction
- AND, OR, XOR operations
- Logical shifts
- Zero/Carry flag generation

### 🔹 3. Control Unit
- Decodes opcodes  
- Generates control signals for ALU, RAM, and data paths  
- Manages instruction sequencing  

### 🔹 4. Data Path
- Interconnects memory, ALU, and registers  
- Handles operand flow and result storage  

---

## 📂 Repository Structure
```text
Mini-Processor-Design/
│── RAM.pdsprj            # RAM module Proteus file
│── alu.pdsprj            # ALU module Proteus file
│── control unit.pdsprj   # Control Unit Proteus file
│── LICENSE               # MIT License
└── README.md             # Project documentation
```

👤 Author-
Ezhilkirthik
