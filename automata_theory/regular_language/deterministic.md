+ [Regular language](/automata_theory/regular_language/regular_language.md)
+ [Alphabet](/automata_theory/basics/alphabet.md)
+ [State](/automata_theory/basics/state.md)

## Deterministic finite automata

A deterministic finite automata is defined by
$$
\langle Q, \Sigma, \delta, q_0, F \rangle
$$
where

1. Set of states $Q$
2. Alphabet $\Sigma$
3. Transition function
    + $\delta(q, a): Q\times\Sigma\mapsto Q$
    + $\hat{\delta}(q, w): Q\times\Sigma^*\mapsto Q$
4. Initial state $q_0$
5. Final states $F$

The string $w$ is accepted by the deterministic automata if the state reached
$q$ is in $F$

