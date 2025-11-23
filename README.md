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
'''
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
'''

Developed by:Janani Sree M
RegisterNumber:25015867


**RTL realization**
<img width="1721" height="913" alt="Screenshot 2025-11-23 214815" src="https://github.com/user-attachments/assets/6c7a6dca-1b31-4e09-96d2-7f509bf9d07a" />

**Output:**

**RTL**

**Timing Diagram**
<img width="1696" height="912" alt="Screenshot 2025-11-23 215157" src="https://github.com/user-attachments/assets/8b09b5cf-136e-4e88-9704-ccdbcdd5275d" />

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

