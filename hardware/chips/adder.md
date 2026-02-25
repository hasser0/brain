+ [Half adder](/hardware/chips/half_adder.md)
+ [Full adder](/hardware/chips/full_adder.md)
+ [Unsigned binary](/hardware/arithmetic/unsigned_binary.md)
+ [Two's complement](/hardware/arithmetic/twos_complement.md)
+ [Ripple](/hardware/arithmetic/ripple.md)
+ [Carry look ahead](/hardware/arithmetic/carry_look_ahead.md)
+ [Combinational](/hardware/chips/combinational.md)

## Multibit adder

Multibit adder, unlike half adder and full adder, perform arithmetic
addition on more than one bit handling being able to handle carry and overflow
in some context.

The simplest implementation is using chained full adders, but this is slow since
carry propagantion is done one bit at a time. A more performant implementation
would be a carry look ahead adder.

