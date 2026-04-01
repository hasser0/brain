+ [States equivalences](/automata/regular_language/minimization/states_equivalence.md)

## Automata equivalences

Two automatas $A$ and $B$ are equivalent iff their initial states are
equivalent.

To test the equivalence of two automatas we can construct the transition table
of the product automata, starting from the initial state of both $(q_A, q_B)$
and checking whether or not the states $\delta_A(q_A, w)$ and $\delta_B(q_B, w)$
are equivalent for each transition
