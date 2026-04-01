+ [State](/automata/basics/state.md)
+ [Alphabet](/automata/basics/alphabet.md)
+ [Symbol](/automata/basics/symbol.md)

## Turing machine

A Turing machine $M$ is a tuple $\langle Q,\Sigma,\Gamma,\delta,q_0,B,F\rangle$
where

1. $Q$ is the set of states
2. $\Sigma\subseteq\Gamma$ is the control unit alphabet
3. $\Gamma$ is the strip's alphabet
4. $\delta$ is the transition function
5. $q_0\in Q$ is the initial state
6. $B\in\Gamma$ is the blank symbol
7. $F\subseteq Q$ is the set of final states

where $\delta(p,X)=(q,Y,D)$ such that

+ $p,q\in Q$
+ $X,Y\in\Gamma$
+ $D\in\{\leftarrow,\rightarrow\}$

Other definitions substitute $F$ with a single $q_f$ as the unique final state

