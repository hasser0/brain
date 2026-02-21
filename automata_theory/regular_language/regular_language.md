+ [Deterministic](/automata_theory/regular_language/deterministic.md)
+ [Nondeterministic](/automata_theory/regular_language/nondeterministic.md)
+ [Epsilon](/automata_theory/regular_language/epsilon.md)
+ [Regular expression](/automata_theory/regular_language/regex.md)
+ [Homomorphism](/automata_theory/basics/homomorphism.md)

## Regular language

A regular language is a set of strings represented by a finite automata $A$

+ Deterministic
+ Nondeterministic
+ Epsilon nondeterministic
+ Regular expression

## Closure properties

+ $L\cup M$ is regular language
+ $L^c$ equals to $\Sigma^* - L$ is regular language
+ $L\cap M$ equals to $(L^c\cup M^c)^c$ is regular language
+ $L - M$ equals to $L\cap M^c $ is regular language
+ $L^R$, the language reversing all $L$ strings, is a regular language

Let $h:\Sigma\mapsto T^*$ be an homomorphism

+ $h(L)=\{h(w)\in T^*|w\in L\}$ is a regular language
+ $h^{-1}(L)=\{x\in\Sigma^*|h(x)\in L\}$ is a regular language

