### NAME: LAKSHMEN PRASHANTH R
### REG NO: 24007066
### EXPERIMENT 4: IMPLEMENTATION OF FULL ADDER AND FULL SUBTRACTOR



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

**Truthtable:**:


![Screenshot 2024-12-12 052352](https://github.com/user-attachments/assets/ed8481c3-8f2f-4f2b-9324-64b01628fc9a)


![Screenshot 2024-12-12 052457](https://github.com/user-attachments/assets/090a0693-12f4-45f3-8400-efd6c8cd0bd5)



**Procedure:**
1. Open Quartus II and create a new project.
2. Use schematic design entry to draw the full adder circuit. 
3. The circuit consists of XOR, AND, and OR gates. 
4. Compile the design, verify its functionality through simulation. 
5. Implement the design on the target device and program it.

For Full Subtractor

1. Follow the same steps as for the full adder. 
2. Draw the full subtractor circuit using schematic design. 
3. The circuit includes XOR, AND, OR gates to perform subtraction. 
4. Compile, simulate, implement, and program the design similarly to the full adder.



**Program:**

![exp4](https://github.com/user-attachments/assets/586d5b00-370b-4bf1-bb2d-680c7ff9af57)


![Screenshot 2024-12-12 051700](https://github.com/user-attachments/assets/5dc443d8-1e2e-4509-bdcc-ea74ee5d17ed)




/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. 
*/

**RTL Schematic:**
![image](https://github.com/user-attachments/assets/daa48cbc-c32d-492a-b26c-1bb336d9dec3)
![image](https://github.com/user-attachments/assets/f393180f-f140-4aec-a257-b6f4d81a49de)



**Output Timing Waveform:**
![Screenshot 2025-01-06 133125](https://github.com/user-attachments/assets/5ae67b55-065a-4156-9ba3-f42458c6dfef)
![Screenshot 2025-01-06 133212](https://github.com/user-attachments/assets/8a769bc3-72df-4c0c-83a7-f314622cf0be)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



