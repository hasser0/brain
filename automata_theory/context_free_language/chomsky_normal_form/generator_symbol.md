+ [Symbol](/automata_theory/basics/symbol.md)
+ [Context free grammar](/automata_theory/context_free_language/context_free_grammar.md)

## Generator symbol

Given a grammar $G$, a symbol $X$ is generator iff exists a string of terminals
$w$ such that $X\Rightarrow w$

For a grammar $G$, the inductive definition of a generator symbol $X$ of $G$ is
+ Base case: For all terminal $a$, $a\Rightarrow a$ so it is generator
+ Inductive step: Given a production $A\rightarrow \alpha$ then $A$ is inductive
  if every symbol of $\alpha$ is generator.

