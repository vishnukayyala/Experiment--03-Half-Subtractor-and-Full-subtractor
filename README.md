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
Developed by: 
RegisterNumber:  
*/

## Output:
## HALF SUBTRACTOR
![hal sub pro](https://github.com/vishnukayyala/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/151489368/971d53c7-4278-427c-af55-a9b7c7cd4b83)

## FULL SUBTRACTOR
![ful sub pro](https://github.com/vishnukayyala/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/151489368/1409f145-4e3e-4dbb-bd5c-f8f875581baf)

## Truthtable

## HALF SUBTRACTOR
![TT SUB HAL](https://github.com/vishnukayyala/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/151489368/8610e613-b91d-419a-a30f-f5760e7bf5fd)

## FULL SUBTRACTOR
![TT SUB FULL](https://github.com/vishnukayyala/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/151489368/ca4e08fa-5789-4065-a2cd-135c86832e9b)

##  RTL realization

## HALF SUBTRACTOR
![RTL SUB HAL](https://github.com/vishnukayyala/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/151489368/a70e93cf-7466-4775-bbed-3d81d08e9086)

## FULL SUBTRACTOR
![RTL FULL SUB](https://github.com/vishnukayyala/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/151489368/551f5d59-aa89-4fc4-a4af-e4ed06b8b4f8)

## Timing diagram 
## HALF SUBTRACTOR
![TIME SUB HAL](https://github.com/vishnukayyala/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/151489368/459270be-08cf-4027-b4bf-4910a4ad1566)

## FULL SUBTRACTOR
![TIME SUB FULL](https://github.com/vishnukayyala/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/151489368/3257b815-5a4a-4040-a38c-6e1a6f40a4e5)

## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
