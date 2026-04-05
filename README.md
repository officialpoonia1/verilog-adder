# verilog-adder
Verilog RTL design of a binary adder with testbench and simulation waveform

Overview

This project implements a binary adder using Verilog HDL.
The design performs addition of two input operands and generates sum and carry outputs.

---

Concepts Used

* Combinational Logic
* RTL Design (Register Transfer Level)
* Continuous Assignment (`assign`)
* Verilog Modules & Ports

---

 Design Details

Inputs

`X` : Input operand
`Y` : Input operand

Outputs

* `Sum` : Result of addition
* `Carry` : Carry-out from addition

---

Code Structure

* `adder.v` → RTL design of adder
* `testbench.v` → Testbench for simulation

---

Simulation

Simulation was performed using:

* Icarus Verilog
* GTKWave

Waveform Output

(Add your waveform screenshot here)

---

How to Run

1. Compile the design:

   ```bash
   iverilog -o output.vvp adder.v testbench.v
   ```

2. Run simulation:

   ```bash
   vvp output.vvp
   ```

3. Open waveform:

   ```bash
   gtkwave wave.vcd
   ```

---

Results

* Correct addition verified for multiple input combinations
* Outputs match expected binary results

---

## Author

Mayank Poonia
B.Tech ECE | VLSI Enthusiast
