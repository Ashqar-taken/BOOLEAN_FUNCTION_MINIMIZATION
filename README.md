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

Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
```
module Exp2(a,b,c,d,w,x,y,z,f1,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&`d|(~a&b&d)|(a&b&~c)));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```
Developed by: Ashqar Ahamed S.T 
RegisterNumber: 24004759


**RTL realization**

![Exp2](https://github.com/user-attachments/assets/89252638-cfa7-405a-bc2b-f0ac9ccc88a4)

**Timing Diagram**

![Screenshot 2024-10-22 110331](https://github.com/user-attachments/assets/42687b1e-4f5b-4cc1-8977-8c640e84d155)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

