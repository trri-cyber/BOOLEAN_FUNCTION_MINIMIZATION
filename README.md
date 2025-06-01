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

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. */
```
Developed by:  Rishab p doshi
RegisterNumber: 212224240134
```

```
module exp2(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
endmodule
```
```
module exp22(x,y,z,w,f2);
input x,y,z,w;
output f2;
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```


**Output:**
### F1

![image](https://github.com/user-attachments/assets/decef45d-be08-44a9-9746-42b5c3dc8cbc)

### F2
![image](https://github.com/user-attachments/assets/177af588-334c-4389-a571-2fd559c5da90)


**RTL**
### F1

![image](https://github.com/user-attachments/assets/868ffca8-a2f3-44e8-a8b8-3bfed328b452)

### F2
![image](https://github.com/user-attachments/assets/fa2da9bc-1018-4092-9851-79395262902d)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

