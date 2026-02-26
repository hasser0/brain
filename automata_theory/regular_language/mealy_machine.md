+ [Transducer](/automata_theory/basics/transducer.md)
+ [DFA](/automata_theory/regular_language/deterministic.md)
+ [Moore machine](/automata_theory/regular_language/moore_machine.md)

## Mealy machine

A Mealy machine, similar to Moore machine, is a transducer that creates and
output on each transition.

Formally, a Mealy machine is a tuple
$$
M_e=\langle Q,\Sigma,\Theta,\delta,\lambda,q_0\rangle
$$
similar to Moore machine, except for $\lambda: Q\times\Sigma\rightarrow Q$ that
is not attached to states but to transitions as $\delta$ transition function
does.

