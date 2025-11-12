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

Developed by:A MUHILAN
RegisterNumber:25015918
```
module boolean_functions(a, b, c, d, w, x, y, z, f1, f2);
input a, b, c, d, w, x, y, z;
output f1, f2;
assign f1 = ((~b & ~d) | (~a & b & d) | (a & b & ~c));
assign f2 = ((~y & z) | (w & y) | (x & y));
endmodule

```

**RTL realization**
<img width="1407" height="886" alt="Screenshot 2025-11-12 213404" src="https://github.com/user-attachments/assets/260d5809-bef0-4d2a-a1b6-2c18c9244d88" />


**Output:**
<img width="1151" height="585" alt="Screenshot 2025-11-12 220934" src="https://github.com/user-attachments/assets/9c97abc5-7d61-450f-b02c-36cc657e2e6b" />


**RTL**
<img width="1917" height="645" alt="Screenshot 2025-11-12 215640" src="https://github.com/user-attachments/assets/7865a1a0-436e-41c6-9500-f7c37192c8df" />

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

