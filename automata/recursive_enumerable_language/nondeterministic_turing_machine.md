+ [Turing
  machine](/automata/recursive_enumerable_language/turing_machine.md)
+ [Instantaneous
  descriptions](/automata/recursive_enumerable_language/instantaneous_description.md)
+ [NFA](/automata/regular_language/nondeterministic.md)

## Nondeterministic Turing machine

A non deterministic Turing machine is almost the same as the classical Turing
machine except for the transition function $$ \delta: Q\times\Gamma\mapsto
\mathcal{P}\big(Q\times\Gamma\times\{L,R\}\big) $$ And works similar to the
nondeterministic finite automata.

Although this is more expressive and apparently more powerful, it is not since
every nondeterministic TM has an equivalent classic TM.

### Equivalence with deterministic Turing machines

Given a NTM $N$ define a DTM $D$ with two tapes:

1. instantaneous descriptions $I_1|I_2|\dots|I_N$ with the current description
   marked with X. All descriptions at the left of X are already processed
2. auxiliary tape

At each iteration

1. The current description is copy to the auxiliary tape
2. If the current description meets acceptance conditions then $D$ accepts and
   halts
3. Otherwise append new descriptions at the end of the first tape according to
   the rules for $\delta$ at the current state and current head symbol
4. Move the mark X to the next description and return to the first step

Let $m$ be the maximum number of instantaneous descriptions that $\delta$ may
create for any input. For any string $w$ accepted by $N$ exists a derivation of
$k$ steps. For $D$ all the instantaneous descriptions from the initial
description with less than $k$ steps are discovered on an upper bound of
$\sum_{i=0}^k m^i$ iterations and therefore $D$ halts

