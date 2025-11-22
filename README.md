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

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**

**Procedure**

Write the detailed procedure here

**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.

<img width="913" height="271" alt="Screenshot 2025-11-18 221919" src="https://github.com/user-attachments/assets/142d51f9-079e-43ed-b935-9d78b0185a98" />

<img width="723" height="239" alt="Screenshot 2025-11-19 205309" src="https://github.com/user-attachments/assets/3ce2e8aa-4e98-43ee-ab46-3e6183094a34" />

Developed by:Menaka M S
RegisterNumber:25015729
*/
**RTL Schematic**

<img width="1721" height="974" alt="Screenshot 2025-11-18 221620" src="https://github.com/user-attachments/assets/e356774f-172d-4665-b9ed-a638267b950f" />

<img width="1749" height="835" alt="Screenshot 2025-11-19 205250" src="https://github.com/user-attachments/assets/04393968-9aa0-407c-bbe3-eac859cb8c48" />

**Output Timing Waveform**

<img width="1688" height="170" alt="Screenshot 2025-11-18 221903" src="https://github.com/user-attachments/assets/aac6c143-bb93-41af-ad12-bf69cac03cb0" />

<img width="1707" height="227" alt="Screenshot 2025-11-19 205434" src="https://github.com/user-attachments/assets/001602e7-b868-429a-a98b-3c04950987c7" />


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



