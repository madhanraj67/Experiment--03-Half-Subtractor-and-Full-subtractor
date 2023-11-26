# Experiment--03-Half-Subtractor-and-Full-subtractor
## Implementation-of-Half-subtractor-and-Full-subtractor-circuit
## AIM:
To design a half subtractor and full subtractor circuit and verify its truth table in Quartus using Verilog programming.

## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime
## Theory
Subtractor circuits take two binary numbers as input and subtract one binary number input from the other binary number input. Similar to adders, it gives out two outputs, difference and borrow (carry-in the case of Adder). There are two types of subtractors.

## Half Subtractor Full Subtractor
## Half Subtractor
The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed.
![half-subtractor9](https://user-images.githubusercontent.com/36288975/166112538-58c3bc7c-ee5d-4e6a-ac8d-8e8328efe27a.png)


Sum = X'Y+XY' = X ⊕ Y
Carry=X'Y

## Full Subtractor
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow. 
![full-subtractor6](https://user-images.githubusercontent.com/36288975/166112541-24c68359-3de8-4674-ae22-8272ffc385ed.png)


Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin

## Procedure



Write the detailed procedure here 


## Program:
/*
Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by: MADHANRAJ P
RegisterNumber:  23013616
*/

## Truthtable:
HALF SUBTRACTOR:
![image](https://github.com/madhanraj67/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150319515/beac2ff0-9644-4c84-876e-55773f90ba9c)


FULL SUBTRACTOR
![image](https://github.com/madhanraj67/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150319515/582fe009-bff9-4b8f-ac25-5d98454dd5f3)


## RTL realization:
HALF SUBTRACTOR:
![image](https://github.com/madhanraj67/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150319515/5c584335-1451-4c4d-8a3f-8df1ff8f375b)



FULL SUBTRACTOR:
![image](https://github.com/madhanraj67/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150319515/0af61da0-5159-4e87-91d2-23a3b24245b2)


## Timing diagram:
Half subtractor:
![image](https://github.com/madhanraj67/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150319515/890368c7-bd39-486a-962e-76ca18bdcfca)



FULL SUBTRACTOR:
![image](https://github.com/madhanraj67/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150319515/3a250959-a050-471f-a9c6-dd3ab46660b6)


## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.

