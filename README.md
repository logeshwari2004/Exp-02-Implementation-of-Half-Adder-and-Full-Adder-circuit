# Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit

# Implementation-of-Half-Adder-and-Full-Adder-circuit
### AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

### Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
Theory
Adders are digital circuits that carry out addition of numbers.

### Half Adder
Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

### Full Adder
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin

 ![DE3A](https://user-images.githubusercontent.com/94211349/228434466-0e51721a-700f-4fcd-bb18-d891fd55908c.png)


#### Figure -01 HALF ADDER 
![DE3B](https://user-images.githubusercontent.com/94211349/228434493-0b263730-ff4b-4435-a02e-43f3d11fb39c.png)

#### Figure -02 FULL ADDER 
### Procedure
Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
### 
Program:
/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: LOGESHWARI.P
RegisterNumber: 212221230055 
*/
Logic symbol & Truthtable
RTL realization

### Output:
![DE3C](https://user-images.githubusercontent.com/94211349/228434788-814ea11a-8a0a-4c16-ae92-6888e168176f.png)

### RTL
![DE3D](https://user-images.githubusercontent.com/94211349/228434851-16840605-e74f-43ec-9cc8-1bf0a503793c.png)

### TIMING DIAGRAM
![DE3E](https://user-images.githubusercontent.com/94211349/228434950-63727fd1-7e0d-40f7-a7a4-b4d323553ce0.png)

![DE3G](https://user-images.githubusercontent.com/94211349/228434973-80947ddb-94f4-4a5c-bd7c-4936d2deb145.png)

![DE3H](https://user-images.githubusercontent.com/94211349/228434984-8682db5c-e74d-4e8e-bc27-65be6f44f272.png)

### TIMING DIAGRAM

![DE3I](https://user-images.githubusercontent.com/94211349/228435013-aa3fd8fc-62cb-45c2-b801-ea827ab3e8bd.png)

### Result:
Thus, a half adder and full adder circuit is designed to verify its truth table in Quartus using Verilog programming.
