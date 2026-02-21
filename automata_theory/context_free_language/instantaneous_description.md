+ [Pushdown automata](/automata_theory/context_free_language/pushdown_automata.md)

## Instantaneous description
Given a pushdown automata $P$ the instantaneous description is the tuple
$$
(p, w, \gamma)
$$
where $p$ is the current state, $w$ is the remaining string and $\gamma$ is
the content of the stack, with the leftmost being the top.

For $\alpha,\beta\in\Gamma^*$, $X\in\Gamma$, $p,q\in Q$, $a\in\Sigma$, a transition
$$
(q,sw,X\beta)\vdash (p,w,\alpha\beta)
$$
means $(p,\alpha)\in\delta(q, s, X\beta)$

