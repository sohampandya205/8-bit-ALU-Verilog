🔷 8-bit ALU Design in Verilog

📌 Overview

This project implements an **8-bit Arithmetic Logic Unit (ALU)** using Verilog HDL.
The ALU performs **16 different operations** including arithmetic, logical, shift, rotate, and comparison operations.

⚙️ Features

* 8-bit input operands (`A`, `B`)
* 4-bit control signal (`ALU_Sel`)
* Supports 16 operations
* Carry output support
* Designed and simulated in Vivado

🧠 ALU Operations

| ALU_Sel | Operation      | Description          |
| ------- | -------------- | -------------------- |
| 0000    | A + B          | Addition             |
| 0001    | A - B          | Subtraction          |
| 0010    | A * B          | Multiplication       |
| 0011    | A / B          | Division             |
| 0100    | A << 1         | Left Shift           |
| 0101    | A >> 1         | Right Shift          |
| 0110    | Rotate Left    | Circular left shift  |
| 0111    | Rotate Right   | Circular right shift |
| 1000    | A & B          | AND                  |
| 1001    | A \| B         | OR                   |
| 1010    | A ^ B          | XOR                  |
| 1011    | ~(A \| B)      | NOR                  |
| 1100    | ~(A & B)       | NAND                 |
| 1101    | ~(A ^ B)       | XNOR                 |
| 1110    | A > B ? 1 : 0  | Greater than         |
| 1111    | A == B ? 1 : 0 | Equality             |

🧪 Simulation

The ALU is verified using a Verilog testbench in Vivado.

🛠️ Tools Used

* Verilog HDL
* Xilinx Vivado

🚀 Future Improvements

* Add Zero, Overflow, and Sign flags
* Extend to 16-bit ALU
* Implement pipelined ALU
* Integrate into RISC-V processor

👨‍💻 Author

Soham Pandya
B.Tech Electrical Engineering (VLSI Enthusiast)
