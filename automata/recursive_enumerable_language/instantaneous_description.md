+ [Turing machine](/automata/recursive_enumerable_language/turing_machine.md)

## Instantaneous description

Given a Turing machine $M$ the instantaneous description specifies its strip and
state at a given point. Take the sequence $X_1\dots X_n$ as the symbols of the
strip where $X_1$ and $X_n$ are the leftmost and rightmost non blank symbol
respectively. At any given point we need to point at a certain point of the
strip, then for the current state $p$ and its head $X_i$ the machine state is

$$
X_1\dots X_{i-1}pX_i\dots X_n
$$

In case the head is not pointing at a symbol between $X_1$ and $X_n$ we use one
or multiple $B$ for the blank cells before and after. For the previous
instantaneous description if $\delta(p,X)=(q,Y,\rightarrow)$ then

$$
\dots X_{i-1} p X_i \dots\ \vdash \dots Y p X_{i+1} \dots
$$

