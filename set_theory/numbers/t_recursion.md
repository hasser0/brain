+ [Inductive set](/set_theory/numbers/inductive_set.md)
+ [Function](/set_theory/functions/functions.md)
+ [Naturals](/set_theory/numbers/naturals.md)

## Recursion theorem

Given a set $A$, an initial element $a\in A$ and a function $F: A\mapsto A$
there exists a unique function $h: \omega\mapsto A$ such that

1. $h(0) = a$
2. $h(n^+) = F(h(n))$

### Implications

+ [Naturals and Peano systems isomorphism](/set_theory/numbers/t_naturals_isomorphism.md)

### Proof

The set of all functions that satisfy the above conditions $H$ is not empty
since $\{(0,a)\}\in H$. Let $h = \cup H$ then $h$ is a unique function such that
$\text{dom}\ h = \omega$ and satifies the above conditions

