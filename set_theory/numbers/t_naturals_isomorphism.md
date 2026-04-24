+ [Recursion theorem](/set_theory/numbers/t_recursion.md)
+ [Peano system](/set_theory/numbers/peano_system.md)
+ [Naturals](/set_theory/numbers/naturals.md)

## Peano systems - naturals

Any Peano system $\langle N, S, e\rangle$ is isomorphic to the natural triplet
$\langle \omega, \sigma, 0\rangle$. That means there exists a injective and
surjective function $h:\omega\mapsto N$ such that

1. $h(0) = e$
2. $h(n^+) = S(h(n))$

### Proof

By the recursion theorem, such a function $h$ exists for the function $S$.
Finally this function is surjective because every element $x\in N$ is the
successor of some number $h(n^+) = S(h(n)) = x$ and the functions domain is
$\omega$. It is injective since, by induction $h(n^+) = h(m^+)$ means
$S(h(n)) = S(h(m))$ and two successors are the same only if $h(n) = h(m)$; using
this argument in induction yields the results.

