+ [Terminal](/automata_theory/grammar/terminal.md)
+ [Variable](/automata_theory/grammar/variable.md)
+ [Rule](/automata_theory/grammar/rule.md)
+ [Language](/automata_theory/basics/language.md)
+ [Derivation](/automata_theory/grammar/derivation.md)
+ [Recursive inference](/automata_theory/grammar/recursive_inference.md)

## Grammar

A grammar is a tuple $G=\langle V, T, P, S\rangle$ where

1. $V$ is a set of non terminal symbols
2. $T$ is a set of terminal symbols
3. $P$ is a set of production rules
4. $S$ is an initial symbol

Each grammar defines a language $L(G)$ which is the set of all strings $w$ that
can be verified, by derivation or recursive inference. Formally
$$
L(G) = \{w\in T^*: S\Rightarrow w\}
$$

