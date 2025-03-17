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

**RTL realization**

**Output:**
![Screenshot 2025-03-17 135750](https://github.com/user-attachments/assets/fbc94b03-6b27-4352-932b-866894cdb027)

**RTL**

**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

