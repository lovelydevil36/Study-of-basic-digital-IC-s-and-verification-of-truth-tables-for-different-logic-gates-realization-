# Study of basic digital logic gates and verification of truth tables for different logic gates realization
## AIM:
To study about the different digital IC’s and to verify the truth table in Quartus for the basic logic gates using Verilog programming.

## Components Required:
1.Hardware – PCs, Cyclone II , USB flasher

2.Software – Quartus prime

## Theory:
1.Logic gates are the basic building blocks of any digital system. Logic gates are electronic circuits having one or more than one input and only one output. The relationship between the input and the output is based on a certain logic. Based on this, logic gates are named as

2.AND gate OR gate NOT gate NAND gate NOR gate Ex-OR gate Ex-NOR gate

3.AND gate The AND gate is an electronic circuit that gives a high output (1) only if all its inputs are high. A dot (.) is used to show the AND operation i.e. A.B or can be written as AB
Y= A.B

4.OR gate The OR gate is an electronic circuit that gives a high output (1) if one or more of its inputs are high. A plus (+) is used to show the OR operation.
Y= A+B

5.NOT gate The NOT gate is an electronic circuit that produces an inverted version of the input at its output. It is also known as an inverter. If the input variable is A, the inverted output is known as NOT A. This is also shown as A' or A with a bar over the top, as shown at the outputs.
Y= A'

6.NAND gate This is a NOT-AND gate which is equal to an AND gate followed by a NOT gate. The outputs of all NAND gates are high if any of the inputs are low. The symbol is an AND gate with a small circle on the output. The small circle represents inversion.
Y= (AB)’

7.NOR gate This is a NOT-OR gate which is equal to an OR gate followed by a NOT gate. The outputs of all NOR gates are low if any of the inputs are high. The symbol is an OR gate with a small circle on the output. The small circle represents inversion.
Y= (A+B)’

8.Ex-OR gate The 'Exclusive-OR' gate is a circuit which will give a high output if either, but not both of its two inputs are high. An encircled plus sign (⊕) is used to show the Ex-OR operation.
Y= A⊕B

9.Ex-NOR gate The 'Exclusive-NOR' gate circuit does the opposite to the EX-OR gate. It will give a low output if either, but not both of its two inputs are high. The symbol is an EX-OR gate with a small circle on the output. The small circle represents inversion.
Y= A⊕B

## Procedure:
1.Connect the supply (+5V) to the circuit.

2.Switch ON the main switch.

3.Press the switches for inputs “A” and “B”. The switch is ON state when 1 is pressed. The switch is OFF state when 0 is pressed.

4.If the output is 1, then the bulb glows.

5.Check all the gates following the same procedure.

## Program:

Program to verify the truth table in quartus for the basic logic gates using Verilog programming.

Developed by: Abdul Hameed.J

RegisterNumber: 21222050001
```

module nachi(a,b,yand,yor,ynot,yxor,ynand,ynor,yxnor); 
input a,b;
output yand,yor,ynot,yxor,ynand,ynor,yxnor;
and(yand,a,b);
or(yor,a,b);
not(ynot,a);
xor(yxor,a,b);
nand(ynand,a,b);
nor(ynor,a,b);
xnor(yxnor,a,b);
endmodule
RTL diagram:
DE EXP 1
```
## Truthtable:
![image](https://github.com/lovelydevil36/Study-of-basic-digital-IC-s-and-verification-of-truth-tables-for-different-logic-gates-realization-/assets/123564624/b686a457-333a-4293-9e58-7c5d45229193)



## Output waveform:
![image](https://github.com/lovelydevil36/Study-of-basic-digital-IC-s-and-verification-of-truth-tables-for-different-logic-gates-realization-/assets/123564624/a9b5841c-f12d-458c-8556-cf2134efaeb6)

# RTL realization:
![image](https://github.com/lovelydevil36/Study-of-basic-digital-IC-s-and-verification-of-truth-tables-for-different-logic-gates-realization-/assets/123564624/36ed770e-f86d-4938-a661-83276a76ce6e)


## Result:
Thus the different digital logic gates are studied and the truth table for different logic gates are verified.
