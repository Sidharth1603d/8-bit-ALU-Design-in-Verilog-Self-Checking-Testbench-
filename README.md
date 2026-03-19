

## 📌 Overview

This project implements an **8-bit Arithmetic Logic Unit (ALU)** using **Verilog HDL**.
The ALU performs a variety of arithmetic and logical operations based on a control signal (opcode).

A **self-checking testbench** is included to automatically verify the correctness of the design, making this project closer to real-world VLSI verification practices.

---

## 🚀 Features

* ✅ 8-bit input operands (A and B)
* ✅ Multiple arithmetic and logical operations
* ✅ 3-bit opcode control
* ✅ Self-checking testbench (automatic verification)
* ✅ Clean and modular Verilog design

---

## ⚙️ Operations Supported

| Opcode | Operation   | Description |
| ------ | ----------- | ----------- |
| 000    | Addition    | A + B       |
| 001    | Subtraction | A - B       |
| 010    | AND         | A & B       |
| 011    | OR          | A | B       |
| 100    | XOR         | A ^ B       |
| 101    | NOT         | ~A          |
| 110    | Left Shift  | A << 1      |
| 111    | Right Shift | A >> 1      |

---

## 🏗️ Design Architecture

* **Inputs:**

  * A (8-bit)
  * B (8-bit)
  * Opcode (3-bit)

* **Outputs:**

  * Result (8-bit)
  * Carry (optional)
  * Zero flag (optional)

---

## 🧪 Self-Checking Testbench (🔥 Highlight)

The testbench:

* Applies multiple test cases automatically
* Calculates expected outputs
* Compares with actual outputs
* Displays **PASS/FAIL**

👉 This eliminates manual waveform checking and ensures correctness.

---

## 🛠️ Tools Used

* Verilog HDL
* ModelSim / Vivado

---

## 🎯 Learning Outcomes

* ✔ Digital logic design
* ✔ Combinational circuit implementation
* ✔ Verilog HDL coding
* ✔ Testbench design & verification
* ✔ ALU as a core processor component

---

## 🔮 Future Improvements

* Add overflow flag
* Extend to 16-bit / 32-bit ALU
* Pipeline architecture
* FPGA implementation

---

## 📌 Applications

* CPU design
* Embedded systems
* Digital signal processing
* VLSI design projects
