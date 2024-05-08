# FULL_ADDER_SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit

## AIM:

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

## Equipments Required:

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

## Full Adder and Full Subtractor

## Full Adder

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

## Full Subtractor

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin


## Procedure

1.Follow the same steps as for the full adder.
2.Draw the full subtractor circuit using schematic design.
3.The circuit includes XOR, AND, OR gates to perform subtraction.
4.Compile, simulate, implement, and program the design similarly to the full adder.

## Program:
```
Program to design a half subtractor and full subtractor 
circuit and verify its truth table in quartus using Verilog programming.
Developed by: Sanjev R M
RegisterNumber: 212223040186
```
## Full Adder
### Program
![image](https://github.com/sanjevrm/FULL_ADDER_SUBTRACTOR/assets/155142423/3b15d6f6-0f22-424c-b3ae-a8c2c6660cc0)

### RTL Schematic
![image](https://github.com/sanjevrm/FULL_ADDER_SUBTRACTOR/assets/155142423/e6c7d2d8-582d-4a63-a6c6-abf167eef014)

### Truth Table
![image](https://github.com/sanjevrm/FULL_ADDER_SUBTRACTOR/assets/155142423/caa27398-05cb-4bbb-a84c-a261ff0dd186)

### Output Timing Waveform
![image](https://github.com/sanjevrm/FULL_ADDER_SUBTRACTOR/assets/155142423/ab8d7660-1d0a-40e5-8d33-fbaa6c9dec73)

## Full Subtractor
### Program
![image](https://github.com/sanjevrm/FULL_ADDER_SUBTRACTOR/assets/155142423/34f4c28e-3f66-4be2-a5b4-5c1c42e69e4e)

### RTL Schematic
![image](https://github.com/sanjevrm/FULL_ADDER_SUBTRACTOR/assets/155142423/48218629-6766-4b75-a7f6-e3bada096618)

### Truth Table
![image](https://github.com/sanjevrm/FULL_ADDER_SUBTRACTOR/assets/155142423/c2597337-a2a4-4c1d-8a44-6830023ede26)

### Output Timing Waveform
![image](https://github.com/sanjevrm/FULL_ADDER_SUBTRACTOR/assets/155142423/dfd841b4-d437-4ced-a2a0-03fcf441afbb)


## Result:

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



