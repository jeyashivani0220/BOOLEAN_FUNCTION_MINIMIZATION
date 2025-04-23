# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
```
Developed by:Jeya shivani.S
RegisterNumber:24010976
```
```python
Function 1:

    module funct1(a,b,c,d,f1);
    input a,b,c,d;
    output f1;
    assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
    endmodule


Function 2:

    module funct2(w,x,y,z,f2);
    input w,x,y,z;
    output f2;
    assign f2=((~y & z)|( w & y )|(x & y));
    endmodule
```
**Truth table**

![IMG-20241203-WA0039](https://github.com/user-attachments/assets/3166a064-80c9-47d1-8d23-6c6bbb738dee)

![IMG-20241203-WA0038](https://github.com/user-attachments/assets/c27a3fc0-a51e-4bcd-a7fd-eaf05a3a96c1)

**Output**
![op functions](https://github.com/user-attachments/assets/3e9d24ab-ac12-48a3-8c2c-5811715dc07d)

![OP fun2](https://github.com/user-attachments/assets/5abf3f3d-c0f6-4aeb-8faa-33b288dd9080)



**RTL**

![logic diagram](https://github.com/user-attachments/assets/8104046c-7357-4dee-bc6a-f07cccf165e0)
![LOGIC DIA FUN2](https://github.com/user-attachments/assets/5e7a3067-dfaa-4dbc-9668-b4dee94c609f)


**Timing Diagram**
![op functions](https://github.com/user-attachments/assets/f4a38d31-33f8-4587-a889-1a9f17e40601)

![OP fun2](https://github.com/user-attachments/assets/98f03472-02cf-4f1b-b299-5fb44acaa15a)

**K-map**

![IMG-20241203-WA0040](https://github.com/user-attachments/assets/69e0c663-2406-4560-948b-dfd3200b4e01)
![IMG-20241203-WA0042](https://github.com/user-attachments/assets/73050ec6-3d41-4d9d-91c0-94f56ccd3291)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

