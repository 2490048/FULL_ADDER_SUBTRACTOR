# FULL_ADDER_SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**Full Adder and Full Subtractor**

**Full Adder**

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin

![{0C227EB6-1BA3-4D54-A0F2-C8FB6EC9E48B}](https://github.com/user-attachments/assets/51aafcf7-e7b1-4c2c-879b-f1338a29349c)


Carry = AB + ACin + BCin

![{871D8575-50CC-447E-A49C-4E1ED932847C}](https://github.com/user-attachments/assets/ca6fdc23-f1a0-41ab-9c1c-dcb3df6f7207)
![{42BB6D1E-F7FF-4A10-B524-A473421BEA10}](https://github.com/user-attachments/assets/30042cde-da87-4825-ba8d-4ebd996b1a6c)
![{FE1D6D57-251B-4C4E-B6A1-75373934D536}](https://github.com/user-attachments/assets/16d8721f-a044-42db-b9d1-9fa252c55509)






**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![{8F72EC12-C6E2-4E9A-BC44-DC07D25F748A}](https://github.com/user-attachments/assets/3fb6f8c6-a21a-44c2-ba43-360335043d15)
![{178508F0-EE0C-48E8-BA94-FC0E436FCFE5}](https://github.com/user-attachments/assets/8f981087-fab4-4194-bd5b-7eca90c5f77e)
![{1593B0CA-77AC-4BD7-BBC3-BB1EDE605801}](https://github.com/user-attachments/assets/3ca088e6-f23e-494c-be40-9e3c648dbffa)
![{F54707BA-413D-48ED-9655-728E8A2E06A2}](https://github.com/user-attachments/assets/6bc842f5-5d80-4d7d-bba8-9d3fa59ffdb8)







Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**

**Procedure**

Write the detailed procedure here

**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by: RAHUL RP
RegisterNumber:24900488
*/

**RTL Schematic**

**Output Timing Waveform**

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



