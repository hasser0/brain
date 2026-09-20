+ [Combinational](/computer_systems/hardware/chips/combinational.md)
+ [Chip](/computer_systems/hardware/basics/chip.md)

## Shifter

A shifter is a combinational chip that receives N ordered bits and moves them to
the right or to the left

+ Logical: fill empty spaces with zeros
+ Arithmetic: fill empty spaces with a copy of previous values

They are usually implemented using multiplexors, where the input values are the
bits from the N ordered bits and the selectors is an encoded binary number

