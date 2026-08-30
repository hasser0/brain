+ [Epsilon](/automata/regular_language/epsilon.md)
+ [Nondeterministic](/automata/regular_language/nondeterministic.md)

## Epsilon closure construction

Given an epsilon nondeterministic finite automata, we can construct a
nondeterministic finite automata.

1. For each state compute its epsilon closures. These will be the states of our
   nondeterministic automata.
2. For each epsilon closure determine the transition function by applying the
   original transition function on the closure, followed by the closure.
3. The final states are those containing at least one final state of the
   original epsilon automata
4. The initial state is the initial state closure $S_0=C(\{q_0\})$

