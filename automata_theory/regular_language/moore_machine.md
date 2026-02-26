+ [DFA](/automata_theory/regular_language/deterministic.md)
+ [Transducer](/automata_theory/basics/transducer.md)

## Moore machine

A Moore machine is a transducer machine that is similar to DFA machine in that
they process data solely based on the current state, and so doesn't provide
memory mechanisms.

Formally, a Moore machine is a tuple
$$
M_o=\langle Q,\Sigma,\Theta,\delta,\lambda,q_0\rangle
$$
where

1. $Q$ is a set of states
2. $\Sigma$ is a set of input symbols
3. $\Theta$ is a set of output symbols
4. $\delta: Q\times\Sigma\rightarrow Q$ is a transition function
5. $\lambda: Q\rightarrow \Theta$ is an output function
6. $q_0$ is the initial state

Note that the output is attached to a state and the behaviour of Moore machines
is identical to DFA, however instead of halting it outputs or transforms input
into output

