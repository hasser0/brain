+ [Symbols](/math_foundations/formal_theory/symbols.md)
+ [Expressions](/math_foundations/formal_theory/expressions.md)

## Well formed formula(wff)

A well formed formula is an expression that satisfies a set of rules of the
formal language that it is part of. For example, for the case of propositional
logic, the set of well formed formulas is inductively defined by:

1. If $x$ is an statement letter symbol then it is a wffs
2. If $\alpha, \beta$ are wffs then $(\neg\alpha)$ is a wff
3. If $\alpha, \beta$ are wffs then $(\alpha \lor \beta)$ is a wff
4. If $\alpha, \beta$ are wffs then $(\alpha \land \beta)$ is a wff
5. If $\alpha, \beta$ are wffs then $(\alpha \Rightarrow \beta)$ is a wff
6. If $\alpha, \beta$ are wffs then $(\alpha \Leftrightarrow \beta)$ is a wff

