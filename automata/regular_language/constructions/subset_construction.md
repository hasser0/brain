+ [Deterministic](/automata/regular_language/deterministic.md)
+ [Nondeterministic](/automata/regular_language/nondeterministic.md)

## Subset construction

Given a nondeterministic automata $M=\{Q,\Sigma,Q_0,\Delta,F\}$
its transition function $\Delta$ could be understood as

$$\Delta:2^Q \times \Sigma \mapsto 2^Q$$

We can construct a deterministic automata

$$N=\{Q^*,\Sigma,Q_0,\Delta,F^*\}$$

where $Q^* = \{x|x\in 2^Q\}$ and
$F^* = \{x|x\in 2^Q,\ x\cap F \neq \varnothing \}$

