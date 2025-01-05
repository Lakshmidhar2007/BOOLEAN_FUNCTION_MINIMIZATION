# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**
![WhatsApp Image 2024-10-29 at 10 50 38_223cff67](https://github.com/user-attachments/assets/a2c3a876-d6ab-45db-b918-1c4e72757a0f)


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

### Developed by: LAKSHMIDHAR N  
### RegisterNumber: 24900046

      module exp2(a,b,c,d,f1,f2,w,x,y,z);
      
      input a,b,c,d,w,x,y,z;
      
      output f1;
      
      output f2;
      
      assign f1 =((~b & ~d)|(~a&b&d)|(a&b&~c));
      
      assign f2 =((~y&z)|(x&y)|(w&y));
      
      endmodule

**RTL realization Output:**
![exp2](https://github.com/user-attachments/assets/d59990f6-9b65-48a7-ae80-db5b9e77c257)

**Timing Diagram**
![WhatsApp Image 2024-10-29 at 11 12 59_80cf5da5](https://github.com/user-attachments/assets/32917131-24a3-4759-aa3b-d61bebcc8714)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

