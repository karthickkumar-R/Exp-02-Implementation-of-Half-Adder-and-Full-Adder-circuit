# NAME    :KARTHICKKUMAR.R

# ROLL NO :23012023


# Exp 03 Implementation of Half Adder and Full Adder circuit

# AIM:

To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

# Equipments Required

Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
Theory
Adders are digital circuits that carry out addition of numbers.

# THEORY

# Half Adder

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

# Full Adder

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin

 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)

# Figure -01 HALF ADDER 


![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)

# Figure -02 FULL ADDER 

# Procedure

Connect the supply (+5V) to the circuit Switch ON the main switchIf the output is 1, then the led glows.

# Program:

# HALF ADDER

module experiment3(A,B,sum,carry);
input A,B;
output sum,carry;
xor(sum,A,B)
or(carry,A,B);
endmodule

# FULL ADDER

module experiment 3(a,b,c,Sum,Carry);
input a,b,c;
output Sum,Carry;
assign Sum=((a^b)^c);
assign Carry=((a&b)|(b&c)|(c&a));
endmodule

# RTL REALIZATION

HALF ADDER

![WO3 LH](https://github.com/vasanthkumarch/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150005103/4a1baa10-9d2c-48c2-a543-4de2ab55255d)

FULL ADDER

![WO3 LF](https://github.com/vasanthkumarch/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150005103/0672fc1d-e09c-430d-ae68-bfe4f66386c5)

 # TRUTH TABLE

 HALF ADDER

![WO3 TTH](https://github.com/vasanthkumarch/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150005103/12422138-6af1-4f8a-9b52-2f50142c2646)

 FULL ADDER

![WO3 TT F](https://github.com/vasanthkumarch/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150005103/b87de6cd-4dab-4782-ba9b-1458835c8bf1)

# TIMING DIAGRAM

HALF ADDER

![WO3 TD H](https://github.com/vasanthkumarch/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150005103/a9d3aa1b-c13f-41af-bd91-a6a9c417b1c7)

FULL ADDER

![WO3 TD F](https://github.com/vasanthkumarch/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150005103/488d4288-e606-4f4b-895b-81df0dc2f86b)

# Result:

Half Adder is a combinational logic circuit that adds two 1-bit digits.The half adder produces a sum of the two inputs.A full adder is a combinational logic circuit that performs an addition operation on three one-bit binary numbers.The full adder produces a sum of the three inputs and carry value. 
