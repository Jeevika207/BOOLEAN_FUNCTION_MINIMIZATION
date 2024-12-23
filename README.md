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

**Output:**

**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
module logic1(a,b,c,d,f1);

input a,b,c,d;

output f1;

assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));

endmoodule

Developed by: Jeevika R

RegisterNumber:24900508


**RTL realization**

![image](https://github.com/user-attachments/assets/82237491-def3-4fc3-bbc8-2c47e693388c)


**Timing Diagram**

![image](https://github.com/user-attachments/assets/2629484b-dbb4-415d-aad2-c8e0f0a9b3b5)

**Program 2:**

module logic3(w,x,y,z,f2);

input w,x,y,z;

output f2;

assign f2=((~y & z)|( w & y )|(x & y));

endmodule

**RTL realization**

![image](https://github.com/user-attachments/assets/811d365b-ea31-40d8-9fed-49ebaaf2b71a)


**Timing Diagram**

![image](https://github.com/user-attachments/assets/0fcdf80d-02ba-45fc-9d97-cb50ed1925e3)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

