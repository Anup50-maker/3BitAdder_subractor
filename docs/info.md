<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

Our project works on the basis of the Full adder formulae,
when we give inputs via signals A[0:3],B[0:3] the sum and carry out are generated using the formula :
Sum=A^B^Cin
Cout=(A&B)|(B&Cin)|(Cin&A)
When the Cin value is changed to 1:
Adder is transformed into Subractor the xor gate compute the two's  complement and add them 


## How to Use

Our project can be used in where Adder_Subractors are used  including addition/subraction upto 3 bits of binary numbers 

## External hardware

Our project includes usage of 4 leds which indicate the state of S[0:3]and Cout Signals from which output can be derived 
