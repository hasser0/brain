+ [Sequential](/hardware/chips/sequential.md)
+ [Combinational](/hardware/chips/combinational.md)
+ [Register](/hardware/chips/register.md)

## Synchronous circuit

Sequential circuits with cyclic paths might suffer from race conditions or
unstable sequences; this makes circuits hard to design and debug. Race
conditions emerge on faster or slower cyclic paths in the circuit, therefore
a set of registers synchronized to a single clock signal is often used to
differentiate cycles and identify current from next states.

Synchronous circuits is a subset of sequential circuit such that

+ Every component is combinational or a register
+ Every cycle contains a register that handles loop backs

