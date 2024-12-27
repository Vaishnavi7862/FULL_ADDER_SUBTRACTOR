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
![Screenshot 2024-12-27 204730](https://github.com/user-attachments/assets/7eb3b054-5744-49cd-a78a-0d0a115d191e)
![Screenshot 2024-12-27 204740](https://github.com/user-attachments/assets/e0bb81a0-e92c-47d4-bae2-df898b3f3ab2)

**Procedure**

Write the detailed procedure here

**Program:**
![Screenshot 2024-12-27 204813](https://github.com/user-attachments/assets/533dda06-e982-46da-ab99-de002cc33315)
![Screenshot 2024-12-27 204822](https://github.com/user-attachments/assets/ab148063-1f5b-4a1f-8f51-47c25ea8d455)

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by:VAISHNAVI.D RegisterNumber:24900005
*/

**RTL Schematic**
![Screenshot 2024-12-27 204832](https://github.com/user-attachments/assets/cbf73b38-f1c0-44af-8c65-87a44755a0b1)
![Screenshot 2024-12-27 204841](https://github.com/user-attachments/assets/fa64cf7e-a8c6-41b2-951e-e2ee5da7e0dc)

**Output Timing Waveform**
![Screenshot 2024-12-27 204909](https://github.com/user-attachments/assets/b97abfda-1d59-45ff-8440-ddc7a8c88c11)
![Screenshot 2024-12-27 204909](https://github.com/user-attachments/assets/a2759b46-5908-4b7e-90c9-449a8e2545f6)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



