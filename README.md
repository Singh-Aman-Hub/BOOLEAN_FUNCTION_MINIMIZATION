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

module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule 

Developed by: RegisterNumber: 24900215 (Aman Singh)


**RTL realization**
![logic gate](https://github.com/user-attachments/assets/3f8836ef-07f2-4f3e-8651-858192ee98f6)


**Output:**
![waveform](https://github.com/user-attachments/assets/6fd00534-c148-413f-a1c9-af5540041a32)
**Result:**

Thus the given logic functions are implemented and their operations are verified using Verilog programming.

**RTL**

![waveform](https://github.com/user-attachments/assets/0491dbe1-a893-4404-b4d8-28565f94054b)




