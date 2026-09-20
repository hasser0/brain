+ [States equivalence](/theory_of_computation/regular_language/minimization/states_equivalence.md)
+ [Automata equivalence](/theory_of_computation/regular_language/constructions/equivalences.md)

## Minimization

Let $A$ be an automata, then its states and the equivalence of states are an
equivalence relation. By definition, for any states $p\equiv q$ and any word
$w$, the acceptance of $w$ is the same. Therefore we can construct an smaller
but identical automata:

1. Delete unreachable states
2. Find partitions and deleting redundant states within them.

For the second part, we can create a table and cross any pair of states that are
not equivalent. The rest are equivalent and therefore within the same partition
with each others.
