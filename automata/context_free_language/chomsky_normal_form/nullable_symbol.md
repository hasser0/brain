+ [Symbol](/automata/basics/symbol.md)
+ [Context free grammar](/automata/context_free_language/context_free_grammar.md)

## Nullable symbol

Given a grammar $G$, a symbol $X$ is nullable iff $X\Rightarrow \varepsilon$
that is, when the symbol generates the empty string.

The inductive definition is

+ Base case: for any production $A\rightarrow \varepsilon$ the variable $A$ is
  nullable
+ Inductive case: for any production $A\rightarrow \alpha$ such that every
  symbol of $\alpha$ is nullable, then $A$ is nullable

### Algorithm to remove nullable productions

Given a grammar $G$, to remove all nullable productions

1. Find all nullable symbols
2. Remove productions $A\rightarrow\varepsilon$
3. For each nullable symbol $X$, find and replace each production where $X$
   appears on the right $A\rightarrow\alpha$ with all the productions
   that raise from either placing the ith $X$ or not for each index where $X$
   appears
4. Remove productions $A\rightarrow$

### Result

Every grammar $G$ and its result with the previous algorithm $G^*$ has the
following property $L(G) - \{\varepsilon\} = L(G^*)$

