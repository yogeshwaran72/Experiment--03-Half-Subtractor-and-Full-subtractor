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
Developed by: PRAVEENKUMAR R
RegisterNumber:212223050037  
*/
CODE;

HALF SUBTRACTOR:

![293238036-d6fcdadc-caa4-4ea5-8222-823badd84583](https://github.com/yogeshwaran72/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/153492924/fe0c2b90-b8be-44a1-8730-c742c0e0e93f)

FULL SUBTRACTROR:
![293238072-bdf3710a-4e37-4e42-a0f9-ab9dcfa0a39d](https://github.com/yogeshwaran72/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/153492924/ea2b45c6-e4b0-4936-b17f-aa18c6f4c48f)

## Output:

## Truthtable:
HALF SUBTRACTOR:
![293238107-6c603a5d-b569-4a08-a549-8a40c270652d](https://github.com/yogeshwaran72/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/153492924/f7f3fccb-bf4f-40bc-a445-d3349ff1cc52)

FULL SUBTRACTOR:
![293238176-2e4d3819-4ff0-4cba-beff-f54dc3f1f5b8](https://github.com/yogeshwaran72/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/153492924/beddf158-dece-4b9a-a8b4-3a362785a6d4)

##  RTL realization
HALF SUBTRACTOR:

![293238230-d793f787-ded7-46f9-8437-9e1faaf22017](https://github.com/yogeshwaran72/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/153492924/caebe523-354f-4138-be54-d6cdac60628e)
FULL SUBTRACTOR:

![293238270-0711c5e4-3549-4c23-8d28-2dd70ce3c5b1](https://github.com/yogeshwaran72/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/153492924/3cfa3a04-95b0-47f8-a8f7-f4b692d9939f)


## Timing diagram
HALF SUBTRACTOR:
![293238356-04dfb7f5-bee0-4927-b322-26f78daa9075](https://github.com/yogeshwaran72/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/153492924/e30ff2d3-3c14-4562-9486-e1d370fb30d6)
FULL SUBTRACTOR:
![293238390-7b42a039-ba1f-4d06-9482-2881c8aeefe5](https://github.com/yogeshwaran72/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/153492924/0dd51a9f-a5bb-48ec-ae25-9f3d2bb3c62e)


## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
