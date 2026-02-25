+ [Adder](/hardware/chips/adder.md)
+ [Ripple](/hardware/arithmetic/ripple.md)

## Carry look ahead adder

Carry look ahead is an improved version of ripple method that solves the slow
carry propagation by calculating the carry of each pair of bits in parallel and
before performing bit to bit addition.

Given two sequences of n-bits $A$, $B$, then ith bit either generates or
propagates a carry.

+ Generate: $G_i = A_i B_i$
+ Propagate: $P_i = A_i + B_i$

Therefore each carry is calculated based on the recurrent formula
$$
C_i = G_{i-1} + C_{i-1}P_{i-1}
$$
which is can be transformed to only depend on $G_i$ and $P_i$ by replacing
recursively $C_i$ and with the fact that $C_0$ is the given base case.

