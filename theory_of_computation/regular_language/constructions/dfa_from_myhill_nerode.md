+ [DFA](/theory_of_computation/regular_language/deterministic.md)
+ [Quotient set](/math_foundations/set_theory/equivalence_relation/quotient_set.md)
+ [Myhill Nerode relation](/theory_of_computation/regular_language/myhill_nerode_relation.md)

## DFA from MN relation

Given a Myhill Nerode relation over a set $A\subseteq \Sigma^*$ denoted as
$\equiv$ the following construction is a DFA

1. $Q = \{[x]: x\in \Sigma^*\}$ (the quotient set)
2. $q_0 = [\varepsilon]$
3. $F = \{[x]: x\in A\}$
4. $\delta([x],a) = [xa]$

