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

 **FIGURE-1 FULL ADDER**

   
![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)



**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin



**FIGURE-2 FULL SUBTACTOR**


![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**

FULL ADDER:

![image](https://github.com/user-attachments/assets/e0dcc6df-2428-4da5-a7df-25b1e5328d1f)

FULL SUBTRACTOR:

![image](https://github.com/user-attachments/assets/a68e257f-7de4-418b-9508-882d211a6418)


**Procedure**

![image](https://github.com/user-attachments/assets/e6395776-88f2-4a63-a21c-2c0a7fe6342c)

**Program:**


FULL ADDER:

![image](https://github.com/user-attachments/assets/cf30ea89-631d-4927-b786-e44730d8a01a)

FULL SUBTRACTOR:

![image](https://github.com/user-attachments/assets/04dd83f7-24ca-4bcd-9bab-ad817da56816)


**RTL Schematic**

FULL ADDER:

![image](https://github.com/user-attachments/assets/e5180430-db72-474c-9f82-a6f9aee0466c)

FULL SUBTRACTOR:

![image](https://github.com/user-attachments/assets/0fc9dbae-b4bf-4266-a3b4-44141978e894)



**Output Timing Waveform**

FULL ADDER:

![image](https://github.com/user-attachments/assets/0a5cc044-2a61-43d9-87a4-cb1a83348f9a)

FULL SUBTRACTOR:

![image](https://github.com/user-attachments/assets/f5317b71-8005-49f8-8e42-ba7eb57e86c9)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



