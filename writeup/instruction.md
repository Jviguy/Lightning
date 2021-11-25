# Basic Instruction Format
All instructions will be assembled into one uint16_t (unsigned 16 bit integer).
## Format
The first four bits will be the instruction desginator e.g 0001 being designator 1 after being parsed into a uint16.

The next 12 bytes are dependent on the instruction.