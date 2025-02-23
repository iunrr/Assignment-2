This was an old assignment from my class, CMPT295: Introduction to Computer Systems.

The goal was create an emulator that is able to execute a subset of the RISC-V ISA using C.
RISC-V is a form of Assembly, instructions include add, mul, sub, and load/store operations.

The files that contain my code are part1.c, part2.c, and utils.c.

utils.c contains various helper functions, mainly the instruction code parsing function.
part1.c is responsible for decoding the instruction and executing the proper functions to parse the operation.
part2.c contains the functions necessary for instruction execution.
