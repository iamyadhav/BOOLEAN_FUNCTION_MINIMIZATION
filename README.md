# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Logic Diagram**

![exp 2](https://github.com/user-attachments/assets/5217c311-ac29-448f-8b6d-12e2bad89a08)

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
Developed by: NETHRA.K  RegisterNumber:  (212224230184)
~~~
module exp2a(a,b,c,d,F1);
intput a,b,c,d;
output F1;
assign F1=((~b&~d)|(~a&b&d)|(a&b&~c));
endmodule



module exp2b(w,x,y,z,F2)
intput w,x,y,z;
output F2;
assign F2=((~y&z)|(x&y)|(w&y));
endmodule
 ~~~
 */


**RTL realization Output:**

![Screenshot 2025-04-09 105742](https://github.com/user-attachments/assets/47cdcef2-3066-413a-a7bd-1a43e803e107)

![Screenshot 2025-04-09 110953](https://github.com/user-attachments/assets/363f17d9-044a-43b6-b452-9c27b12b41e9)


**RTL Timing Diagram:**

![Screenshot 2025-04-09 110314](https://github.com/user-attachments/assets/78a66db3-52cd-4d14-9f5c-a28e2d2081f7)

![Screenshot 2025-04-09 111245](https://github.com/user-attachments/assets/12e7e638-1133-4e9f-ae64-4462f3f1b69e)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Logic Diagram**

![exp 2](https://github.com/user-attachments/assets/5217c311-ac29-448f-8b6d-12e2bad89a08)

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
Developed by: NETHRA.K  RegisterNumber:  (212224230184)
~~~
module exp2a(a,b,c,d,F1);
intput a,b,c,d;
output F1;
assign F1=((~b&~d)|(~a&b&d)|(a&b&~c));
endmodule



module exp2b(w,x,y,z,F2)
intput w,x,y,z;
output F2;
assign F2=((~y&z)|(x&y)|(w&y));
endmodule
 ~~~
 */


**RTL realization Output:**

![Screenshot 2025-04-09 105742](https://github.com/user-attachments/assets/47cdcef2-3066-413a-a7bd-1a43e803e107)

![Screenshot 2025-04-09 110953](https://github.com/user-attachments/assets/363f17d9-044a-43b6-b452-9c27b12b41e9)


**RTL Timing Diagram:**

![Screenshot 2025-04-09 110314](https://github.com/user-attachments/assets/78a66db3-52cd-4d14-9f5c-a28e2d2081f7)

![Screenshot 2025-04-09 111245](https://github.com/user-attachments/assets/12e7e638-1133-4e9f-ae64-4462f3f1b69e)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

