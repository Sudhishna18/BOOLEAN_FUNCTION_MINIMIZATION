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
Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
Developed by:P.Sudhishna
RegisterNumber:24007608

```
```
module funct1(a,b,c,d,f1);
 input a,b,c,d;
 output f1;
 assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
 endmodule
```
**RTL realization**

![image](https://github.com/user-attachments/assets/d3f41dde-96be-4f91-a4bf-8add2de9466b)

**Output:**

![image](https://github.com/user-attachments/assets/00a7bf88-1b07-4851-93a2-1ecbf337923a)


**Timing Diagram**

![image](https://github.com/user-attachments/assets/7da86a5c-687c-4bad-8401-a85ef36a4c55)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

