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
module exp2(a,b,c,d,f1,w,x,y,z,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```

Developed by:Pavithra k   RegisterNumber:212224240112


**logic symbol & truth table:**
![Screenshot 2025-04-23 180137](https://github.com/user-attachments/assets/af4663fa-5551-4c49-aaed-f69248ab68f4)



![Screenshot 2025-04-23 180209](https://github.com/user-attachments/assets/53b9f195-969d-4852-bc05-1fece35bd12e)



**RTL**
![Screenshot 2025-04-23 174215](https://github.com/user-attachments/assets/f1e288c3-68f1-4fe6-8afe-75473fa5ade9)

**Timing Diagram**
![Screenshot 2025-04-23 174153](https://github.com/user-attachments/assets/705c860c-b0d9-47d0-a822-383709dced82)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

