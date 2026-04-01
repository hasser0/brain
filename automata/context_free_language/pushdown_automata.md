+ [Epsilon automata](/automata/regular_language/epsilon.md)
+ [State](/automata/basics/state.md)
+ [Alphabet](/automata/basics/alphabet.md)
+ [Symbol](/automata/basics/symbol.md)

## Pushdown automata

$P=\langle Q,\Sigma,\Gamma,\delta,q_0,Z_0,F\rangle$ is an pushdown automata where

1. $Q$ finite set of states
2. $\Sigma$ finite set of symbols
3. $\Gamma$ finite set of symbols(pushable onto the stack)
4. $\delta$ transtion function
$$
\delta:Q \times \Sigma_\epsilon \times \Gamma_\epsilon
\mapsto Q \times \Gamma_\epsilon^*
$$
5. $q_0$ initial state
6. $Z_0$ stack bottom symbol
7. $F$ set of final states

