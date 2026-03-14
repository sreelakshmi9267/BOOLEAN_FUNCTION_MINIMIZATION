# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
```
module boolean_function_4var (
    input  wire A,
    input  wire B,
    input  wire C,
    input  wire D,
    output wire F
);

assign F = (~A & B) | (C & D) | (A & ~D);

endmodule

```

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: RegisterNumber:*/Sree Lakshmi
212225040421


**RTL realization**
<img width="1620" height="945" alt="image" src="https://github.com/user-attachments/assets/c731a39c-22b5-4def-8298-9e728e971d25" />

**Output:**
<img width="1324" height="1001" alt="Screenshot 2025-11-19 212747" src="https://github.com/user-attachments/assets/3d860f6d-4759-41bd-bf0e-5a80c0e1277d" />


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

