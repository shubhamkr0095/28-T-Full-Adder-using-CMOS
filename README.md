# 28-T-Full-Adder-using-CMOS
## Abstract
The project to design a 28-T full adder circuit by
using CMOS (Complementary metal oxide semiconductor).
Which is a combinational arithmetic circuit comprising of two
half adders but to overcome the limitation of half adder that
can add only two 1-bit number, also the power consumption is
high and speed is slow. Requirement is to reduce the number of
transistors from traditional approach of 40-T to 28-T. So, it can
be used as part of many larger circuits like ripple carry adder,
Arithmetic Logic Unit/ALU, Graphics Processing Unit. This
can help to achieve to integrate large number of components on
smaller area of chip. It makes robust to supply voltage scaling
due to low consumption of static power. That makes 28-T full
adder circuit faster compare to previous 40-T full adder circuit
## Keywords 
28-T full adder, ALU, CMOS, Graphics Processing
Unit.
## Introduction
The 28-T full adder circuit consist of three one-bit value
as input, which is usually expressed as A, B, and Cin, where
A and B are operands and Cin is carry bit from previous,
less-significant stage. As we know from basics, for pull up
network we required pMOS and for pull down we required
nMOS transistor. In traditional circuit sum output is given by
A exor B exor Cin and carry output as Cout. But by this
conventional method give rise in number of transistors like
for sum it required 30-T and for Cout it required 10-T. This
will increase the cost as well as affect speed of operation. So,
we go for this design in which we implement sum as a
function of A, B, Cin and Cout [1]. For carry output we follow
previous expression. This will reduce the requirement of
number of CMOS transistor in the sum circuit. Thus, lead to
low power requirement and increase in operational speed as
well as cost of the product. As we know, CMOS circuits
always give inverted output, so we need to add two inverter
circuits for both sum and Cout. Hence, we require two more
pMOS and nMOS to invert each output. Fig. 1 shows that
for sum it required 16-T and for Cout it required 12-T which
includes both the inverter circuit [2]. Fig. 2 shows the
required waveform obtain by implementing this 28-T full
adder using CMOS [2].
## Implemented Circuit 
![circuit](https://user-images.githubusercontent.com/100314081/155971655-68200dd3-9941-405f-b805-69bad9bbab50.png)
## Implemented Circuit Symbol
![symbol](https://user-images.githubusercontent.com/100314081/155971891-41dfe6c5-23aa-49e5-8192-62c40ff1de2e.png)
## Implemented Circuit Block
![Full_Adder](https://user-images.githubusercontent.com/100314081/155972150-85340afd-ac5c-4bde-9344-0f899b090c57.png)
## Implemented Circuit Waveform
![waveform](https://user-images.githubusercontent.com/100314081/155972344-6ef8b8ca-9203-46d4-b2c9-544cb7b80e28.png)
## Reference
[1] A. K. Yadav, B. P. Shrivatava and A. K. Dadoriya, "Low
power high speed 1-bit full adder circuit design at 45nm
CMOS technology," 2017 International Conference on
Recent Innovations in Signal processing and Embedded
Systems (RISE), pp. 427-432, 2017.

[2] Sung-MO Kang, Yusuf Leblebici, “CMOS Digital
Integrated Circuits”, Second Edition, pp.08-19, 2003.





