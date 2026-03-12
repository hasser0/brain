+ [Fixed point](/hardware/arithmetic/fixed_point.md)

## Floating point

Floating point is a representation for real numbers with a versatile position
for the point that separates decimal part from integral part, similar to
scientific notation.

To convert a decimal number to floating point, first convert it to fixed point
notation and then to a scientifc notation. Suppose $-101100.101$ is the fixed
point representation
$$
\begin{align}
(-101100.101)_2 &= (-1.01100101)_2 \cdot (2^5)_{10}\\
&= (-1.01100101)_2 \cdot (10^{101})_2
\end{align}
$$
The floating point representation according to IEEE 754 consist of a bit sign, a
bias exponent and a mantisa. The bit sign equals 0 when the number is positive
or 1 otherwise, the bias exponent adds constant B in binary to the exponent and
the mantisa is the part after the dot, since the first 1 is redundant.

|               | Double precision | Single precision |
|---------------|------------------|------------------|
| Mantisa bits  | 52               | 23               |
| Exponent bits | 11               | 8                |
| Bias          | 127              | 1023             |

Number zero, either positive or negative, is represented with an exponent of all
zeros. Infinite, either positive or negative, is represented with an exponent of
all ones and a mantisa of all zeros. NaN values are represented with an exponent
of all ones and a mantisa different from zero

