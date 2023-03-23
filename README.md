# building_computer_from_logicgates
## Building a 16bits computer using logical gates. 
I am building a 16bits computer from logic gates. Notably NAND gates.
This is part of a course called nand to tetris (that I am following online).
And I am using the book CODE by charles Petzold as a reference and a guide. 
## Note: I coded the gates using hdl. And ran them on a hardware simulator program that executes hdl files.

--- 


step1:
Given a Nand gate, I built Not, And, Or, Xor, Mux, DMux, Not16, And16, Or16, Mux16, Or8Way, Mux4Way16, Mux8Way16, DMux4Way, DMux8Way gates. 
see : [01](01)

-- 

step2:
The goal is to build a CPU.
I must first build an essential compenent of the CPU the "arithmetic logic unit" (ALU).
I will do it by building the following gates: HalfAdder,FullAdder,Add16, Inc16 . ( Inc is an incrementer gate ; and "16" indicates 16bits)

see:[02](02)

--

step3:
Buildin the RAM.
This is gone by building the following gates: Bit, Register, RAM8, RAM64, RAM512, RAM4K, AM16K, PC.
Note:Bit is a 1bit regsiter. Also note that the gates are built given a data flip flop gate (DFF).

see:[03](03)

---
I will update the page as soon as I finish a new module 
