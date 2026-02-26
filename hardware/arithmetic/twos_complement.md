+ [Signed binary](/hardware/arithmetic/signed_binary.md)
+ [Unsigned binary](/hardware/arithmetic/unsigned_binary.md)

## Two's complement

Two's complement is a signed binary encoding. For any decimal number $d$ such
that its unsigned binary representation contain $n$ bits. We calculate its
two's complement as
$$
\bar{d} = 2^n - d
$$
Note that $\bar{d} + d = 2^n$ **for a fixed value n**.

For example, let $d=5$ so

+ $0101$ is the binary representation with 4 bits
+ $0000\_0101$ is the binary representation with 8 bits

and

+ For $n=4$, $\bar{d}_4=16-5=11$ written as $1011$ in binary
+ For $n=8$, $\bar{d}_8=256-5=251$ written as $1111\_1011$ in binary

When we add $0101 + 1011 = 1\_0000$ or $0000\_0101 + 1111\_1011 = 1\_0000\_0000$
we got an overflow and therefore seems like they result in 0. This property
makes two's complement an efficient method to represent and manipulate negative
numbers

