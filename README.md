# NAME   :KARTHICKKUMAR.R

# ROLL NO:23012023

# Exp 03 Implementation of Half Adder and Full Adder circuit


### AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

### Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
Theory
Adders are digital circuits that carry out addition of numbers.

### Half Adder
Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

### Full Adder
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin

 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)

#### Figure -01 HALF ADDER 


![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)

#### Figure -02 FULL ADDER 

### Procedure

Connect the supply (+5V) to the circuit Switch ON the main switch If the output is 1, then the led glows.

### Program:

HALF ADDER

![w03p h](https://github.com/vasanthkumarch/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150005103/121cd793-fdb9-4405-bdac-bad054d66700)

FULL ADDER

![wo3 pf](https://github.com/vasanthkumarch/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150005103/5e8d2613-ac42-4515-9e53-ddecb3f08966)



# RTL realization

HALF ADDER

![WO3 LH](https://github.com/vasanthkumarch/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150005103/7ffaf712-e17a-4fa3-ae1f-0944b35d4465)


FULL ADDER

![WO3 LF](https://github.com/vasanthkumarch/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150005103/99eb057f-d04f-4efc-9cd3-ca249e9d7ca8)


### TIMING DIAGRAM

HALF ADDER

![WO3 TD H](https://github.com/vasanthkumarch/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150005103/02259ec5-5bf9-479e-9b2e-7370d7eb5bb3)

FULL ADDER

![WO3 TD F](https://github.com/vasanthkumarch/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150005103/7f5ad432-fbd4-4f9a-8ef7-7dfe7565bfda)

### TRUTH TABLE 

HALF ADDER

![WO3 TTH](https://github.com/vasanthkumarch/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150005103/c72e4df8-6a07-4d57-a645-d918e707df26)

FULL ADDER

![WO3 TT F](https://github.com/vasanthkumarch/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150005103/1da263fb-a957-4bf6-9aef-797947be11bf)

### Result:

Half Adder is a combinational logic circuit that adds two 1-bit digits. The half adder produces a sum
of the two inputs. A full adder is a combinational logic circuit that performs an addition operation
on three one-bit binary numbers. The full adder produces a sum of the three inputs and carry value.
