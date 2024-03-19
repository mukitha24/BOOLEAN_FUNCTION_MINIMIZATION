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
```
// Verilog model:Circuit with boolean expressions
module ex02 (E,F,A,B,C,D);
input A, B, C, D;
output E,F;
assign E = A || (B && C) || ((!B) && D);
assign F=((!B) && C) || ( B && (!C) && (!D));
endmodule
```
Developed by:Mukitha V M
RegisterNumber:*/212223040119



**RTL realization**
![Screenshot 2024-03-19 093023](https://github.com/mukitha24/BOOLEAN_FUNCTION_MINIMIZATION/assets/154068225/0fc55de3-d0f2-49a4-8869-46e28885aa7e)
**Output:**

**RTL**

**Timing Diagram**
![Screenshot 2024-03-19 094242](https://github.com/mukitha24/BOOLEAN_FUNCTION_MINIMIZATION/assets/154068225/31edc7cd-c879-4b14-b10e-12e4285c6a95)

**Result:**
Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

