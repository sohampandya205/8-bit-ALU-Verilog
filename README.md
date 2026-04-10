🔷 8-bit ALU Design in Verilog

📌 Overview
This project implements an **8-bit Arithmetic Logic Unit (ALU)** using Verilog HDL.
The ALU performs 16 different operations including arithmetic, logical, shift, rotate, and comparison operations.

⚙️ Features
* 8-bit input operands (A, B)
* 4-bit control signal (ALU_Sel)
* 16 operations supported
* Carry output support
* Verified using Vivado simulation

🧠 ALU Operations

| ALU_Sel | Operation    |
| ------- | ------------ |
| 0000    | A + B        |
| 0001    | A - B        |
| 0010    | A * B        |
| 0011    | A / B        |
| 0100    | A << 1       |
| 0101    | A >> 1       |
| 0110    | Rotate Left  |
| 0111    | Rotate Right |
| 1000    | A & B        |
| 1001    | A | B        |
| 1010    | A ^ B        |
| 1011    | NOR          |
| 1100    | NAND         |
| 1101    | XNOR         |
| 1110    | A > B        |
| 1111    | A == B       |

🧪 Simulation

The design was verified using a Verilog testbench in Vivado.

🛠️ Tools Used
* Verilog HDL
* Xilinx Vivado

🚀 Future Improvements
* Add Zero, Overflow flags
* Pipeline implementation
* Extend to 32-bit ALU

👨‍💻 Author
Soham Pandya
