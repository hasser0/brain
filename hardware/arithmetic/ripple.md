+ [Full adder](/hardware/chips/full_adder.md)
+ [Adder](/hardware/chips/adder.md)
+ [ALU](/hardware/chips/alu.md)

## Ripple addition

Ripple addition is design method, particularly used for adders and ALUs. This
design is simple, but has performance issues since the propagation of the carry
from previous bits is slow and sequential.

The procedure consists of chaining full adders and propagating the carry to the
next.

