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

**Procedure**

1.Type the program in Quartus software.

2.Compile and run the program.

3.Generate the RTL schematic and save the logic diagram.

4.Create nodes for inputs and outputs to generate the timing diagram.

5.For different input combinations generate the timing diagram.
Write the detailed procedure here

**Program:**

Developed by: ADITHYA M

RegisterNumber: 212224230008

![Screenshot 2025-05-05 221127](https://github.com/user-attachments/assets/522672c1-6054-4b05-809f-23182d565ebc)

**Truthtable**

![Screenshot 2025-05-05 221240](https://github.com/user-attachments/assets/37206950-66f7-43c4-80a3-5d92b2551d14)

![Screenshot 2025-05-05 221253](https://github.com/user-attachments/assets/5a264998-901c-4313-977e-fd528f1f076d)

**RTL Schematic**

![Screenshot 2025-05-05 221325](https://github.com/user-attachments/assets/d7f39242-6ccc-4c0d-9b8d-0f01eb64db9e)

**Output Timing Waveform**

![Screenshot 2025-05-05 221410](https://github.com/user-attachments/assets/37fbbfd8-eca9-4c92-8e62-cf268e2f0a28)


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



