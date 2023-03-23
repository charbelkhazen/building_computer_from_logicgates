# Building Computer from Logic Gates

## Introduction
I am building a 16-bit computer from logic gates, specifically NAND gates, as part of a course called Nand to Tetris. I am using the book CODE by Charles Petzold as a reference and a guide. I coded the gates using HDL and ran them on a hardware simulator program that executes HDL files.

---

## Step 1: Building Basic Gates
Given a NAND gate, I built the following gates using HDL:
- Not
- And
- Or
- Xor
- Mux
- DMux
- Not16
- And16
- Or16
- Mux16
- Or8Way
- Mux4Way16
- Mux8Way16
- DMux4Way
- DMux8Way

See: [01](01)

---

## Step 2: Building Arithmetic Logic Unit (ALU)
The goal is to build a CPU. I must first build an essential component of the CPU, the Arithmetic Logic Unit (ALU). I will do this by building the following gates:
- HalfAdder
- FullAdder
- Add16
- Inc16

Note: "Inc" is an incrementer gate, and "16" indicates 16 bits.

See: [02](02)

---

## Step 3: Building RAM
To build the RAM, I need to build the following gates:
- Bit (a 1-bit register)
- Register
- RAM8
- RAM64
- RAM512
- RAM4K
- AM16K
- PC

Note: the gates are built given a built-in data flip-flop gate (DFF).

See: [03a](03a) for the building blocks, and [03b](03b) for the RAM.

---

I will update the page as soon as I finish a new module.

