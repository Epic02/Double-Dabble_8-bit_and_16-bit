# Double-Dabble_8-bit_and_16-bit
## A binary to BCD converter for 8 bit and 16 bit numbers

This code is an assembly language implementation of the double dabble algorithm or the shift-and-add-3 algorithm for 8051 microcontrolers.

### 8-bit binary to BCD
To convert an 8-bit binary number to BCD use the DouDab.asm file. 
In the code load the binary number to register-0 and run the code. 
The BCD representation will be stored in register-1 and register-2. 
The ones digit is lower nibble of register-1. The tens digit is the upper nibble of register-1. The hundreds digit the lower nibble of register-2.

### 16-bit binary to BCD
To convert an 16-bit binary number to BCD use the DouDab16.asm file. 
In the code load the lower 8 bits of the binary number to register-0 and upper 8 bits of the binary number to register-1 and run the code. 
The BCD representation will be stored in register-2, register-3 and register-4. The ones digit is the lower nibble of register-2. The tens digit is the upper nibble of register-2. The hundreds digit is the lower nibble of register-3. The thousands digit is the upper nibble of register-3. The ten thousands digit is the lower nibble of register-4.
