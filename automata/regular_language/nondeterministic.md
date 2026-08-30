+ [Regular language](/automata/regular_language/regular_language.md)
+ [DFA](/automata/regular_language/deterministic.md)
+ [State](/automata/basics/state.md)
+ [Acceptor](/automata/basics/acceptor.md)

## Nondeterministic finite automata

A nondeterministic finite automata is a variation of a deterministic finite
automata defined by $\langle Q, \Sigma, \Delta, Q_0, F \rangle$
where

1. Set of states $Q$
2. Alphabet $\Sigma$
3. Transition function:
    + $\Delta(q, a): 2^Q\times\Sigma\mapsto 2^Q$
4. Initial state $Q_0$ is a set of states
5. Final states $F$

The string $w$ is accepted by the nondeterministic automata if set reached
$S$ intersected with $F$ is not empty

