+ [Regular language](/theory_of_computation/regular_language/regular_language.md)
+ [Alphabet](/theory_of_computation/basics/alphabet.md)
+ [State](/theory_of_computation/basics/state.md)
+ [Acceptor](/theory_of_computation/basics/acceptor.md)

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
$q\in F$

