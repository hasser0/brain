+ [Terminal](/automata/grammar/terminal.md)
+ [Variable](/automata/grammar/variable.md)
+ [Rule](/automata/grammar/rule.md)
+ [Language](/automata/basics/language.md)
+ [Derivation](/automata/grammar/derivation.md)
+ [Recursive inference](/automata/grammar/recursive_inference.md)

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

