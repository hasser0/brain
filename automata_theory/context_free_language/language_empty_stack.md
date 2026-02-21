+ [Pushdown automata](/automata_theory/context_free_language/pushdown_automata.md)
+ [Instantaneous description](/automata_theory/context_free_language/instantaneous_description.md)

## By empty stack
Given a pushdown automata $G=\langle Q,\Sigma,\Gamma,\delta_N,q_0,Z_0\rangle$,
its language by empty stack is the set
$$
\{w|(q_0,w,Z_0)\vdash(p,\varepsilon,\varepsilon)\}
$$
where $p\in Q$, but the stack and string is empty

