+ [DFA](/automata/regular_language/deterministic.md)

## Ultimately periodic automata

Let $A\subseteq \{a\}^*$. Then A is regular language iff the set
$\{m:a^m\in A\}$ is ultimately periodic.

Ultimately periodic set $U$ means there exists numbers $n, p$ such that
for any $n\leq m$, $m\in U$ implies $m+p\in U$

The reason for the previous theorem is that all states have a single direction
so it eventually hit a repeated state and enter a cycle

