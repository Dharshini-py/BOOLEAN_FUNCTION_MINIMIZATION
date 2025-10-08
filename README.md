# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

module ex2(a,b,c,d,f1);  
input a,b,c,d;  
output f1;  
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));  
endmodule   

module ex3(w,x,y,z,f2);   
input w,x,y,z;   
output f2;  
assign f2=((~y & z)|( w & y )|(x & y));  
endmodule   

Developed by: DHARSHINI V

RegisterNumber: 25010872

**RTL**

<img width="1920" height="1080" alt="Screenshot (20)" src="https://github.com/user-attachments/assets/3e5de3a8-d5dc-4e68-aa87-6bc008a2d104" />

<img width="1920" height="1080" alt="Screenshot (22)" src="https://github.com/user-attachments/assets/c1d01e77-32c3-4af7-8549-f4354c538d0d" />


**Timing Diagram**

<img width="1920" height="1080" alt="Screenshot (39)" src="https://github.com/user-attachments/assets/b3ab7471-3727-4987-9056-0b8782793308" />

<img width="1920" height="1080" alt="Screenshot (40)" src="https://github.com/user-attachments/assets/978497dd-fec7-453f-8fa1-ecfa43e92545" />

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

