Build a Modern Computer from First Principles: From Nand to Tetris I and II 
About
This is the first part of a two-part course in which students learn how to construct a modern +general-purpose computer from the ground up. The first part starts with Boolean algebra and the universal NAND gate and from this build the other elementary logic gates, a Central Processing Unit, a memory system, and a hardware platform. This is done using a simple, but effective, Hardware Description Language and a hardware simulator.

Different versions of this course have been taught at Harvard, Stanford, Chicago and 100+ universities and high schools all over the world. Both parts are currently available online for self-study through coursera.org, and all course material and information can be found at nand2tetris.org.

These are my solutions to the course's six projects. I hope that it will help someone else taking the course, but please do not copy solutions - being stuck is part of learning and there is much to learn by overcoming problems and finding solutions on your own. Note that there are often several ways to solve a problem, and I am open to suggestions/questions!

Subham Majumdar, 2025 👩‍💻

Projects
Project 1: Elementary Logic Gates
This project includes building and simulating 15 elementary logic gates, starting from only a given NAND gate. Provided by the instructors are .tst-files and .cmp-files for testing the chips using the hardware simulator.

Complete chip-set
Project 2: ALU
The goal of the second project is to build "the centerpiece of the CPU", by which we mean the Arithmetic Logic Unit, or ALU. This chip performs many different arithmetic and logical operations, we provide our ALU with abilities to add, subtract numbers, and perform basic logic on 16-bit inputs. Other functionality, such as multiplication, division and floating point arithmetic is not implemented in the hardware, but will instead be added later at a higher level.

Complete chip-set
Project 3: RAM
In the third project the RAM unit of the Hack computer is built. We now move on from the previous combinational logic, to the sequential logic of clocked chips. The entire memory chip-set is built in steps, starting from a primitive data flip-flop gate all the way up to n-bit registers and a complete set of RAM chips.

Complete chip-set
Project 4: Machine Language Introduction
The purpose of this project is to become familiar with the Hack machine language, called assembly, by writing a few simple programs using the assembly language, translate them into binary code and execute them using the given Assembler and the CPU emulator. For this purpose, we assume the computer and the machine language is already built.

Programs
Project 5: Hack Computer Architecture
In this project all the previously built parts come together to finally form the complete architecture of the 16-bit Hack hardware platform. The Memory chip is built with the complete address space of the Hack computer, containing a RAM unit with 16K registers, a Screen with 8K registers and a Keyboard with 1 register. Then the CPU is built, containing an instruction memory and a data memory from which it can fetch, operate on, and modify data. Lastly, the topmost chip is built by assembling the CPU, the instruction memory ROM32K and the data memory Memory.

Complete chip-set
