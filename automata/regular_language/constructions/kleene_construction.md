+ [Deterministic](/automata/regular_language/deterministic.md)
+ [Regular expression](/automata/regular_language/regex.md)

## Kleene's construction

Given a DFA $M$ with $Q=\{q_1,\dots,q_n\}$ and $\Sigma = \{a_1,\dots,a_k\}$ we
define inductively the regex $R_{ij}^k$ as the following.

Base case $R_{ij}^0$ depends entirely on M, which could include $\varepsilon$,
one or more symbols of the language.

The inductive step
$$
R_{ij}^k = R_{ij}^{k-1} + R_{ik}^{k-1}(R_{kk}^{k-1})^*R_{kj}^{k-1}
$$

Paths that take $q_i$ to $q_j$ passing zero times through $q_k$ are describe in
the first term. Other paths passing one or more times are described in the
second term.

$R_{ij}^k$ is the regex that passes M from $q_i$ to $s_j$ passing through
$q_1,\dots,q_k$ only. The semantics of these are proved by induction and yields
the regex of M as
$$
\sum_{p\in F} R_{q_1p}^n
$$
where $q_1$ is supposed the initial state

