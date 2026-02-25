+ [Unsigned binary](/hardware/arithmetic/unsigned_binary.md)
+ [Two's complement](/hardware/arithmetic/twos_complement.md)

## Full adder

A full adder is chip that computes the sum of three bits and the carry of the sum.
It is similar to half adder except that it accepts three bits as input instead
of two, so that the carry from previous sum in multi bit addition is taken into
account

| a | b | c | carry | sum |
|---|---|---|-------|-----|
| 0 | 0 | 0 |   0   |  0  |
| 0 | 0 | 1 |   1   |  1  |
| 0 | 1 | 0 |   0   |  1  |
| 0 | 1 | 1 |   1   |  0  |
| 1 | 0 | 0 |   0   |  1  |
| 1 | 0 | 1 |   1   |  0  |
| 1 | 1 | 0 |   1   |  0  |
| 1 | 1 | 1 |   1   |  1  |

