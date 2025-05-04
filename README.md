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

**FIGURE -1 FULL ADDER**

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)



**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**FIGURE-2 FULL SUBTRACTOR**

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)


**Truthtable**

FULL ADDER: 

![image](https://github.com/user-attachments/assets/df87383d-2ba9-4f5a-8e13-9eb3b98e1421)

FULL SUBTRACTOR:


![image](https://github.com/user-attachments/assets/fadb2296-6660-4511-96cb-9e26a76b71ef)



**Procedure**

![image](https://github.com/user-attachments/assets/a1417f1e-f24d-466a-86c3-9c65bbcd026e)


**Program:**

FULL ADDER:

![image](https://github.com/user-attachments/assets/e67a3483-11b8-4708-a5ec-df2312e7bb13)

FULL SUBTRACTOR:

![image](https://github.com/user-attachments/assets/8203f205-86a1-4803-868c-43992038b302)


**RTL Schematic**

FULL ADDER:

![image](https://github.com/user-attachments/assets/0a08319b-e7d8-418c-bc79-012a04cb3524)

FULL SUBTRACTOR:

![image](https://github.com/user-attachments/assets/cb389bf1-a63f-4629-bd25-ebde023b570d)


**Output Timing Waveform**

FULL ADDER:

![image](https://github.com/user-attachments/assets/7ebf79e7-9b7c-4346-be49-e9039edf096d)


FULL SUBTRACTOR:

![image](https://github.com/user-attachments/assets/2dd46d65-82c4-45bb-90fe-1c82091e8a34)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



