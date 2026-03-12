+ [Signed](/hardware/arithmetic/signed_binary.md)
+ [Unsigned](/hardware/arithmetic/unsigned_binary.md)
+ [Sign magnitude](/hardware/arithmetic/sign_magnitude.md)
+ [Radix complement](/hardware/arithmetic/twos_complement.md)

## Fixed point

Fixed point is a binary representation of fractional numbers. Similar to decimal
numbers, values beyond the point are considered fractional. Suppose
$$
B_n\dots B_1B_0b_1\dots b_m
$$
is the fixed point representation of a number where $B_i$ is the integer part
and $b_j$ is the fractional part, it's decimal value is
$$
\sum_{i=0}^n 2^i B_i + \sum_{j=1}^m \frac{b_j}{2^j}
$$

Fixed point can be signed(sign-magnitude or radix complemtent) or unsigned

