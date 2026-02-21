+ [Symbol](/automata_theory/basics/symbol.md)
+ [Generator symbol](/automata_theory/context_free_language/chomsky_normal_form/generator_symbol.md)
+ [Reachable symbol](/automata_theory/context_free_language/chomsky_normal_form/reachable_symbol.md)
+ [Context free grammar](/automata_theory/context_free_language/context_free_grammar.md)

## Useful symbol

Given a grammar $G$, a symbol $X$ is usefull iff it is reachable and generator,
that means in a single line that $S\Rightarrow \alpha X\beta\Rightarrow w$,
where $S$ is the initial symbol an $w$ is a string of terminals

### Algorithm to remove useless symbols

To remove useless symbols:

1. Remove all not generator symbols and productions with at least one not
   generator symbol in its body
2. Remove all not reachable symbols and productions with its head equals a not
   reachable symbol

### Result

Every grammar $G$ and its result with the previous algorithm $G^*$ yields the
same language

