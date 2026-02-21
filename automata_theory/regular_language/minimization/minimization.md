+ [States equivalence](/automata_theory/regular_language/minimization/states_equivalence.md)
+ [Automata equivalence](/automata_theory/regular_language/minimization/automata_equivalence.md)

## Minimization

Let $A$ be an automata, then its states and the equivalence of states are an
equivalence relation. By definition, for any states $p\equiv q$ and any word
$w$, the acceptance of $w$ is the same. Therefore we can construct an smaller
but identical automata by

1. Deleting isolated states
2. Find partitions and deleting redundant states within them.

For the second part, we can create a table and cross any pair of states that are
not equivalent. The rest are equivalent and therefore within the same partition
with each others.
