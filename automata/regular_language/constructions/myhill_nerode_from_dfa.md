+ [DFA](/automata/regular_language/deterministic.md)
+ [Quotient set](/foundations/set_theory/equivalence_relation/quotient_set.md)
+ [Myhill Nerode relation](/automata/regular_language/constructions/myhill_nerode_relation.md)

## MN relation from DFA

Given a DFA $M=\langle Q,\Sigma,\delta,q_0,F\rangle$ we can construct the
relation $\equiv_M$ over the set $\Sigma^*$ as
$$
x\equiv_M y \quad \triangleq \quad \delta(q_0,x)\in L(M)\Leftrightarrow
\delta(q_0,y)\in L(M)
$$
This is a Myhill Nerode equivalence relation over $L(M)$

