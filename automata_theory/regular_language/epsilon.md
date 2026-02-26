+ [Regular language](/automata_theory/regular_language/regular_language.md)
+ [Nondeterminisitic](/automata_theory/regular_language/nondeterministic.md)
+ [State](/automata_theory/basics/state.md)
+ [Acceptor](/automata_theory/basics/acceptor.md)

## Epsilon nondeterministic finite automata

Epsilon transitions is an extension of nondeterministic automata that allow to
jump to other states without a symbol entry. Given a set $S$ of states, the
closure of $S$ is defined by
$$
C(S) = S \cup \bigcup_{q\in S} \delta(q,\varepsilon)
$$
With this in mind the initial set of states is $C(\{q_0\})$ and the transition
function ends being $\tau(S,a) = C(\delta(q, a))$

The acceptance criteria of a string is the same of the nondeterministic automata
