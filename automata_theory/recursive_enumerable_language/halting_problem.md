+ [Turing machine](/automata_theory/recursive_enumerable_language/turing_machine.md)
+ [Acceptance](/automata_theory/recursive_enumerable_language/acceptance.md)
+ [Halt](/automata_theory/recursive_enumerable_language/halt.md)

## Halting problem

For a Turing machine $M$ and string $w$, either it accepted and halts, it is
rejects or never halts.

A Turing machine $H$ such that

1. $H$ accepts $(P,w)$ when $w$ halts $P$
2. $H$ rejects $(P,w)$ when $w$ never halts $P$

doesn't exists, otherwise exists $H_2$ such that

1. $H_2$ accepts $P$ when $H$ rejects $(P,P)$
2. $H_2$ never halts with $P$ when $H$ accepts $(P,P)$.

since

1. $H$ accepts $(H_2,H_2)$ means $H_2$ halts $H_2$, but by the definition of
   $H_2$ that means $H_2$ never halts with $H_2$.
2. $H$ rejects $(H_2,H_2)$ means $H_2$ never halts $H_2$, but by the defintion
   of $H_2$ that means $H_2$ accepts $H_2$ and therefore halts.

