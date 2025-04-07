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

  Developed by: Jude Clement Jose G
  
  RegisterNumber:212224230109
  
  module exp_2(a,b,c,d,F1);
  
  input a,b,c,d;
  
  output F1;
  
  assign F1=((~a&b&d)|(~b&~d)|(a&b&~c));
  
  endmodule 
  module proj23(w,x,y,z,f2);
  
  input w,x,y,z;
  
  output f2;
  
  assign f2= ((~y&z)|(w&y)|(x&y));
  
  endmodule
**RTL realization**

![WhatsApp Image 2025-03-17 at 14 31 38_e3b2870c](https://github.com/user-attachments/assets/737436c3-6ca0-49f4-a06f-09a8cad5ea2a)

**Output:**

2A

![Screenshot 2025-03-17 135750](https://github.com/user-attachments/assets/fbc94b03-6b27-4352-932b-866894cdb027)

2B

![WhatsApp Image 2025-04-07 at 13 34 51_ecfda3f6](https://github.com/user-attachments/assets/97fc02a8-26f0-4dfb-b2c1-cfec31e17dca)


**RTL**
2A

![exp_2](https://github.com/user-attachments/assets/db543de6-7b99-45d0-8c72-824b1c670015)

2B

![WhatsApp Image 2025-04-07 at 13 31 04_7010e4b3](https://github.com/user-attachments/assets/a8485565-b81f-49a9-b2a6-a2bab8579694)

**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

