+ [Nullable productions](/automata_theory/context_free_language/chomsky_normal_form/nullable_symbol.md)
+ [Useful symbols](/automata_theory/context_free_language/chomsky_normal_form/useful_symbol.md)
+ [Unary productions](/automata_theory/context_free_language/chomsky_normal_form/unary_production.md)
+ [Context free grammar](/automata_theory/context_free_language/context_free_grammar.md)

## Chomsky normal form

A context free grammar $G$ is in Chomsky normal form iff every rule is of the
form

1. $A\rightarrow BC$
2. $A\rightarrow a$
3. $S\rightarrow \varepsilon$

where

1. $a\in T$, $a\neq\varepsilon$
2. $A,B,C\in V$
3. $B,C\neq S$

For terminal symbol we can produce $a_V\rightarrow a$ and replace this variable
in all productions. Then all productions $A\rightarrow X_1\dots X_n$ can be
chain as $A\rightarrow X_1A_1$, $A_1\rightarrow X_2A_3$ up to
$A_{n-2}\rightarrow X_{n-1}X_n$

## Algorithm

Given a grammar $G$, exists a grammar $G^*$ without

+ Nullable productions
+ Unary productions
+ Useless symbols

such that $L(G) - \{\varepsilon\} = L(G^*)$.

1. Removing from nullable productions only delete $\varepsilon$ of the language
2. Removing unary productions only creates productions with the same bodies of
   its original language
3. Removing useless symbols only deletes productions

