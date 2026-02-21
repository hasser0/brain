+ [Regular language](/automata_theory/regular_language/regular_language.md)
+ [DFA](/automata_theory/regular_language/deterministic.md)
+ [State](/automata_theory/basics/state.md)

## Nondeterministic finite automata

A nondeterministic finite automata is a variation of a deterministic finite
automata defined by $\langle Q, \Sigma, \delta, q_0, F \rangle$
where

1. Set of states $Q$
2. Alphabet $\Sigma$
3. Transition function:
    + $\delta(q, a): Q\times\Sigma\mapsto \mathcal{P}Q$
    + $\hat\delta(S, a): \mathcal{P}Q\times\Sigma\mapsto \mathcal{P}Q$
4. Initial state $q_0$
5. Final states $F$

the extended transition function is defined by
$$
\hat{\delta}(S, a) = \bigcup_{q\in S} \delta(q, a)
$$

The string $w$ is accepted by the nondeterministic automata if set reached
$S$ intersected with $F$ is not empty

