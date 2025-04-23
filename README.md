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
```
First program:
module EXP2(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b&~d|a&b&~c|~a&b&d));
endmodule

Second program:
module EXP2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y&z|x&y|w&y));
endmodule
```


**Developed by:SHARON CLARA A**                                                                                                                                                              
**RegisterNumber:212224040310**    
**DATE:12/03/2025**

**Truth table & symbol:**
![WhatsApp Image 2025-03-19 at 10 05 17_ad83ae6d](https://github.com/user-attachments/assets/15d06142-3516-4f1d-b305-e357e0d11347)
![WhatsApp Image 2025-03-19 at 10 09 34_9e0567b5](https://github.com/user-attachments/assets/d3adca37-8a49-4400-88d3-f651ea706b37)                                                                                                 

**RTL realization Output:**                                                                                                                                                                                           ![image](https://github.com/user-attachments/assets/a5932a20-a600-42ae-b20f-1372db585113)
 ![image](https://github.com/user-attachments/assets/7cd3dc12-37a9-454b-aafe-abb678604d72)



**Timing Diagram**
![image](https://github.com/user-attachments/assets/91f40222-e8d2-432a-a6bd-039ddb523fff)
![image](https://github.com/user-attachments/assets/ed7b78f8-f477-45a1-84c6-65074c7c3bec)





**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

