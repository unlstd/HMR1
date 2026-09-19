> This repo documents my progress in creating my first fully functional 16-bit computer. At first, it wasn't even supposed to be public. I made it public mainly to make it easier to work on the project across different devices and to get quicker help from my friends. Because of that, please consider this project more as a documentation of someone's progress rather than a fully documented architecture.

With that being said, I can now introduce you to the project and what I'm trying to achieve.

HMR1 is a 16-bit, non-pipelined computer running at 4 MHz with 8 GPRs.

It contains the following components:

* ALU with two 16-bit special registers for latching operands
* MAR
* MDR
* SP
* HP
* 8 × 16-bit GPRs
* FR
* PC (also known as IP)
* Internal 4 MHz clock and reset signal generator
* CU

The computer itself is still a work in progress, but most of it is already done.

You can track the progress using the checklist below:

* [x] ALU
* [x] MAR
* [x] MDR
* [x] SP
* [x] HP
* [x] GPRs
* [x] FR
* [x] PC
* [ ] Motherboard
* [ ] CU
* [ ] Internal 4 MHz clock and reset signal generator
