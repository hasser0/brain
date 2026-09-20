+ [DFA](/automata/regular_language/deterministic.md)
+ [Minimization](/automata/regular_language/minimization/minimization.md)
+ [Equivalent states](/automata/regular_language/minimization/states_equivalence.md)
+ [Equivalence relation](/foundations/set_theory/equivalence_relation/equivalence_relation.md)
+ [Equivalence class](/foundations/set_theory/equivalence_relation/equivalence_class.md)
+ [Quotient class](/foundations/set_theory/equivalence_relation/quotient_set.md)

## Quotient construction

Suppose $M=\langle Q,\Sigma,\delta,q_0,F\rangle$ is a DFA. Notice that the
definition of **equivalence states** $R$ is also an **equivalence relation**.

Define a second DFA
$$
N = \langle Q/R,\Sigma,\Delta,[q_0],F'\rangle
$$
where
+ $Q/R$ is the quotient set
+ $[q_0]$ is the equivalence class of the initial state
+ $F'$ is the set of all equivalences classes of final states in $F$
$$
\Delta([p],a) = [\delta(p,a)]
$$

This construction creates an equivalent, but smaller, automata.

+ If $[p] = [q]$, are $\Delta([p],x)$ and $\Delta([q],x)$ equal?
+ Is it possible to apply this construction indefinely and get smaller
  automatas?

