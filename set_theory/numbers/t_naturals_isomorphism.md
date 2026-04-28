+ [Recursion theorem](/set_theory/numbers/t_recursion.md)
+ [Peano system](/set_theory/numbers/peano_system.md)
+ [Naturals](/set_theory/numbers/naturals.md)
+ [Bijective](/set_theory/functions/bijective.md)

## Peano systems - naturals

Any Peano system $\langle N, S, e\rangle$ is isomorphic to
$\langle \omega, \sigma, 0\rangle$. There is a biyection
$h:\omega\mapsto N$

1. $h(0) = e$
2. $h(n^+) = S(h(n))$

### Proof

By the recursion theorem, such a function $h$ exists for the function $S$ and it
is biyective
