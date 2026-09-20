+ [Axiom](/math_foundations/formal_theory/axioms.md)
+ [Direct consequence](/math_foundations/formal_theory/direct_consequence.md)
+ [Well formed formulas](/math_foundations/formal_theory/well_formed_formula.md)
+ [Formal theory](/math_foundations/formal_theory/formal_theory.md)

## Consequence

Given a set of wffs $\Gamma=\{\gamma_1,\dots,\gamma_n\}$ called hypothesis and
$\alpha$ called consequent, it is said that $\alpha$ is a consequence of
$\Gamma$ in a formal theory iff exists a sequence of wff
$\langle w_1,\dots,w_n \rangle$ such that $w_n=\alpha$ and for all elements of
the sequence:

1. $w_i$ is an axiom of the formal theory
1. $w_i\in\Gamma$ is a wff in the hypothesis
3. $w_i$ is a direct consequence of a subset of the previous wffs
   $\{w_1,\dots,w_{i-1}\}$

