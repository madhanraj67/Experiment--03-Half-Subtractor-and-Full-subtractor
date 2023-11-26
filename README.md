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
## TRUTH TABLE:
HALF SUBTRACTOR
![image](https://github.com/madhanraj67/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150319515/e4b5682f-d282-496b-bd92-923bf4d7f40f)
FULL SUBTRACTOR
![image](https://github.com/madhanraj67/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150319515/6f7033a3-7299-4d00-990d-f6c5c9203ad4)
## RTL realization:
HALF SUBTRACTOR
![image](https://github.com/madhanraj67/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150319515/7002a8cb-66b1-4a05-bbdf-fc1ca478a6d9)
FULL SUBTRACTOR
![image](https://github.com/madhanraj67/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150319515/13cf5b69-8ad5-4f3a-95fb-ce97d38500e7)
## Timing diagram:
Half subtractor
![image](https://github.com/madhanraj67/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150319515/617bbae2-1f74-4c2f-b456-678ea8410c87)
FULL SUBTRACTOR
![image](https://github.com/madhanraj67/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150319515/53c51a48-02cf-4f44-8146-cd4b90bad505)
## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
