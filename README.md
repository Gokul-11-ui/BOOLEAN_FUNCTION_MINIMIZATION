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

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
Developed by:Nidishkumar S
RegisterNumber:24002777
module exp21(a,b,c1,c2,c3,c4,c5,c6,c7);
input a,b;
output c1,c2,c3,c4,c5,c6,c7;
not y1(c1,a);
and y2(c2,a,b);
or y3(c3,a,b);
nand y4(c4,a,b);
nor y5(c5,a,b);
xor y6 (c6,a,b);
xnor y7(c7,a,b);
endmodule
Developed by: RegisterNumber:*/24001755


**RTL realization**
![386236522-12cc10e7-b5f4-49f6-b99f-7787eeda650b](https://github.com/user-attachments/assets/a030f9e1-e8bf-4f64-a5e6-39784f4cf9c6)

**Timing Diagram**
![386236588-e0c8e98b-bc8a-4be9-8258-7d8d586e13eb](https://github.com/user-attachments/assets/13917ebd-141e-4b41-b5be-182933bd614c)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

