+ [Symbol](/automata_theory/basics/symbol.md)
+ [Context free grammar](/automata_theory/context_free_language/context_free_grammar.md)

## Reachable symbol

Given a grammar $G$, a symbol $X$ is reachable iff for the initial symbol $S$
$S\Rightarrow\alpha X\beta$

Given a grammar $G$, the inductive definition of a reachable symbol $X$ of $G$

+ Base case: The symbol $S$ is reachable since $S\rightarrow S$
+ Inductive step: Given a rule $A\rightarrow \alpha X\beta$ then $X$ is
  reachable if $A$ is reachable

