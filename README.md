# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime:**

**Theory:**

**Logic Diagram:**

**Procedure:**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

i)
module exp1de1(a,b,c,d,f1); 
input a,b,c,d; 
output f1; 
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c)); 
endmodule
ii) 
module exp2de2(w,x,y,z,f2); 
input w,x,y,z; 
output f2; 
assign f2=((~y & z)|( w & y )|(x & y)); 
endmodule

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: A.B.GNANA PRAGATHIKA

RegisterNumber:212225230075

**Output:**

**RTL:**

<img width="1920" height="1080" alt="Screenshot 2026-05-27 100944" src="https://github.com/user-attachments/assets/314c2d84-9bd9-4247-9da1-e72b205dbbae" />


<img width="1920" height="1080" alt="Screenshot 2026-05-27 102907" src="https://github.com/user-attachments/assets/e8075ddc-811a-42bc-88cd-61f00db277d9" />


**WAVEFORM:**

<img width="1920" height="1080" alt="Screenshot 2026-05-27 102005" src="https://github.com/user-attachments/assets/9fc49502-f242-4b76-a0b3-5bd28af08219" />


<img width="1920" height="1080" alt="Screenshot 2026-05-27 103656" src="https://github.com/user-attachments/assets/8e8b186d-a346-4aff-9009-7aa5400f9a71" />


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

