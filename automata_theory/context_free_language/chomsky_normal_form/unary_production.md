+ [Context free grammar](/automata_theory/context_free_language/context_free_grammar.md)

## Unary production

Given a grammar $G$, a production of $G$ is unary iff it is of the form
$A\rightarrow B$ where $A, B$ are variables

A pair of variables (A,C) is unary iff $A=C$ or (A,B) is an unary pair and(A,B)
is an unary pair and $B\rightarrow C$ is a production rule

### Algorithm

To remove all unary production rules

1. Find all unary pairs using the recursive definition
2. For each unary pair $(A,B)$, create all the productions $A\rightarrow\alpha$
   such $\alpha$ is the body of a production $B\rightarrow\alpha$

### Result

Given a grammar $G$ and the resulting grammar of the previous algorithm $G^*$
then $L(G) = L(G^*)$

