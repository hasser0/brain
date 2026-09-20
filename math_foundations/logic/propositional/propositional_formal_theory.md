+ [Formal theory](/math_foundations/formal_theory/formal_theory.md)
+ [Connectors](/math_foundations/logic/propositional/connector.md)
+ [Axioms](/math_foundations/formal_theory/axioms.md)
+ [Inference rules](/math_foundations/formal_theory/inference_rules.md)
+ [Statement letters](/math_foundations/logic/propositional/statement_letter.md)
+ [Statement forms](/math_foundations/logic/propositional/statement_form.md)

## Propositional formal theory

Propositional logic has many different formal theories, which area all
equivalent in content. However this one is an standard approach

Let $\Sigma=\{(,),\neg,\Rightarrow,A_1,A_2,\dots\}$ be the set of symbols of the
formal theory, where $A_i$ are the non logical symbols called **statement letters**
and the rest are the logical symbols.

For wffs $\alpha, \beta$ define $\epsilon_\neg(\alpha) = (\neg \alpha)$ and
$\epsilon_\Rightarrow(\alpha,\beta)=(\alpha\Rightarrow\beta)$ as the generating
rules for all the well formulas. Other known connectors are defined as
abbreviations on top of these.

The axioms of this formal theory are

1. $A\Rightarrow(B\Rightarrow A)$
2. $(A\Rightarrow(B\Rightarrow C))\Rightarrow((A\Rightarrow B)\Rightarrow(A\Rightarrow C))$
3. $(\neg A\Rightarrow \neg B)\Rightarrow((\neg A\Rightarrow B)\Rightarrow A)$

The only inference rule is Modus ponens

