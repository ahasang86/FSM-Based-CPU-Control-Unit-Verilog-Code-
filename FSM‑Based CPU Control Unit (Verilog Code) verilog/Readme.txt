# CPU Control Unit (FSM-Based) – Verilog

This project implements a CPU Control Unit using a **Moore Finite State Machine (FSM)** in Verilog.  
It models a simplified CPU pipeline with the following stages:

- **FETCH** – Retrieve instruction from memory  
- **DECODE** – Identify opcode and instruction type  
- **EXECUTE** – Perform ALU operations  
- **MEMORY** – Load/Store operations  
- **WRITEBACK** – Write results to register file  

The design includes a fully commented Verilog implementation and a complete testbench for simulation.

---

## 🔧 Features
- Moore FSM architecture  
- Clean, readable Verilog code  
- Opcode-based control signal generation  
- Memory read/write control  
- ALU operation enable logic  
- Testbench with clock generation and opcode testing  
