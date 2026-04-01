+ [Grammar](/automata/grammar/grammar.md)

## Derivation tree

Given a grammar $G = \langle V, T, P, S\rangle$ a derivation tree for the
grammar $G$ is any tree with the following conditions.

1. Every internal node is tagged with a variable of $V$
2. Every leaf node is tagged with a variable, a terminal or $\varepsilon$(only
   in when it is the unique child of the parent node)
3. If an internal node is tagged with $A$ an its children are tagged with
   $X_1,X_2,\dots,X_k$ respectively from the left, then
   $A\rightarrow X_1X_2\cdots X_k$ is a production of $P$

Intuitivelly and formally any derivation tree can be thought as a production of
the form $X\rightarrow X_1X_2\cdots X_n$ where $X_1X_2\cdots X_n$ is the
concatenation of the leaf nodes from left to right in order.

