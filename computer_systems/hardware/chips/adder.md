+ [Combinational](/computer_systems/hardware/chips/combinational.md)
+ [Half adder](/computer_systems/hardware/chips/half_adder.md)
+ [Full adder](/computer_systems/hardware/chips/full_adder.md)
+ [Unsigned binary](/computer_systems/hardware/arithmetic/unsigned_binary.md)
+ [Two's complement](/computer_systems/hardware/arithmetic/twos_complement.md)
+ [Ripple](/computer_systems/hardware/arithmetic/ripple.md)
+ [Carry look ahead](/computer_systems/hardware/arithmetic/carry_look_ahead.md)

## Multibit adder

Multibit adder, unlike half adder and full adder, perform arithmetic
addition on more than one bit handling being able to handle carry and overflow
in some context.

The simplest implementation is using chained full adders, but this is slow since
carry propagantion is done one bit at a time. A more performant implementation
would be a carry look ahead adder.

