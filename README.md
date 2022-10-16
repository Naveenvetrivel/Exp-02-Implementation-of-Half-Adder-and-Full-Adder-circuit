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

 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)

#### Figure -01 HALF ADDER 


![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)

#### Figure -02 FULL ADDER 

### Procedure

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
### 
## Program:
/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by:NAVEENKUMAR V 
RegisterNumber:  21221230068
*/
#### Logic symbol & Truthtable
## HALF ADDER:
![image](https://user-images.githubusercontent.com/94165322/196046635-379e68de-7742-440a-a547-c66f0882ec90.png)
## FULL ADDER:
![image](https://user-images.githubusercontent.com/94165322/196046646-87ddb8e9-aa71-464f-98b9-75af2360c78b.png)


### Output:
### RTL
## HALF ADDER:
![image](https://user-images.githubusercontent.com/94165322/196046709-f17e10b5-8772-4185-87b8-93e6209e5a1e.png)
## FULL ADDER:
![image](https://user-images.githubusercontent.com/94165322/196046722-6fb35c99-99a8-4925-b347-2417867317ae.png)

### TIMING DIAGRAM
## HALF ADDER:
![image](https://user-images.githubusercontent.com/94165322/196046733-4ca7c862-1a04-4428-b9f5-bcc70e5f47bf.png)
## FULL ADDER:
![image](https://user-images.githubusercontent.com/94165322/196046745-efd81a86-150f-4952-a8ac-6a4689355833.png)

### Result:
Designing of a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming is sucessfully done.
