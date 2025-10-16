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
F(A,B,C,D)=AB+CD+AD

module boolean_function_4var (
    input  wire A,
    input  wire B,
    input  wire C,
    input  wire D,
    output wire F
);

assign F = (~A & B) | (C & D) | (A & ~D);

endmodule


/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: RegisterNumber:*/


**RTL realization**

**Output:**

**RTL**

**Timing Diagram**

**Result:**
Logic diagram:
<img width="605" height="728" alt="EXPERIMENT 2 BOOLEAN FUNCTION" src="https://github.com/user-attachments/assets/29f3553c-ee47-4974-985e-7df1482c0144" />
state diagram:

<img width="1048" height="713" alt="Screenshot 2025-10-16 100912" src="https://github.com/user-attachments/assets/3301f811-2cd2-476c-8c18-634cb828038f" />

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

