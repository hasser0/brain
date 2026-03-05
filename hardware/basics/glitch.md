+ [Circuit](/hardware/basics/chip.md)
+ [Timing](/hardware/basics/timing.md)

## Glitch

A glitch is a temporary output signal in a circuit that is incorrect due
contamination delays; because the circuit has different paths from input to
output and some of them are longer than other, some changes are reflected before
others.

Glitches can be dangerous depending on downstream components. For example, it
could cause a reset in a finite state machine, undesirable race conditions, etc.

