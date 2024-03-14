### study-of-basic-gates
## Developed by:SUJITHRA.K
## Register number:212223040212

##AIM:##

To study and verify the truth table of logic gates in Quartus II using Verilog programming.

## Equipments Required:

Software – Quartus prime 

## Theory:

Introduction Logic gates are the basic building blocks of any digital system. Logic gates are electronic circuits having one or more than one input and only one output. The relationship between the input and the output is based on a certain logic. Based on this, logic gates are named as

AND gate OR gate NOT gate NAND gate NOR gate Ex-OR gate Ex-NOR gate

## AND gate:

The AND gate is an electronic circuit that gives a high output (1) only if all its inputs are high. A dot (.) is used to show the AND operation i.e. A.B or can be written as AB
Y= A.B

## OR gate:

The OR gate is an electronic circuit that gives a high output (1) if one or more of its inputs are high. A plus (+) is used to show the OR operation.
Y= A+B

## NOT gate:

The NOT gate is an electronic circuit that produces an inverted version of the input at its output. It is also known as an inverter. If the input variable is A, the inverted output is known as NOT A. This is also shown as A' or A with a bar over the top, as shown at the outputs.
Y= A'

## NAND gate:

This is a NOT-AND gate which is equal to an AND gate followed by a NOT gate. The outputs of all NAND gates are high if any of the inputs are low. The symbol is an AND gate with a small circle on the output. The small circle represents inversion.
Y= (AB)’

## NOR gate:

This is a NOT-OR gate which is equal to an OR gate followed by a NOT gate. The outputs of all NOR gates are low if any of the inputs are high. The symbol is an OR gate with a small circle on the output. The small circle represents inversion.
Y= (A+B)’

## Ex-OR gate:

The 'Exclusive-OR' gate is a circuit which will give a high output if either, but not both of its two inputs are high. An encircled plus sign (⊕) is used to show the Ex-OR operation.
Y= A⊕B

## Ex-NOR gate:

The 'Exclusive-NOR' gate circuit does the opposite to the EX-OR gate. It will give a low output if either, but not both of its two inputs are high. The symbol is an EX-OR gate with a small circle on the output. The small circle represents inversion.
Y= A⊕B

## Procedure:

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


## PROGRAM:
```
module exp1(a,b,y1,y2,y3,y4,y5,y6,y7);
input a,b;
output y1,y2,y3,y4,y5,y6,y7;
and (y1,a,b);
or (y2,a,b);
not(y3,a);
nand (y4,a,b);
xor (y5,a,b);
xnor (y6,a,b);
nor (y7,a,b);
endmodule

```
## RTL realization Output:
![Screenshot 2024-03-14 210028](https://github.com/Suji-90/study-of-basic-gates/assets/150884148/c0f9be90-028f-4cf2-ab7a-3d8dc073ca23)

## Truth table:
![Screenshot 2024-03-14 212820](https://github.com/Suji-90/study-of-basic-gates/assets/150884148/9a7f1088-0d46-41a6-ad38-4c9ab9d3deb7)


## Timing diagram:
![Screenshot 2024-03-14 210129](https://github.com/Suji-90/study-of-basic-gates/assets/150884148/bcb8c9e7-ec90-48b5-97c9-d9f253e52fdb)


## Result:
Thus the different digital IC's are studied and the truthtable for different logic gates 


