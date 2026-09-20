+ [Terminal](/theory_of_computation/grammar/terminal.md)
+ [Variable](/theory_of_computation/grammar/variable.md)
+ [Rule](/theory_of_computation/grammar/rule.md)
+ [Language](/theory_of_computation/basics/language.md)
+ [Derivation](/theory_of_computation/grammar/derivation.md)
+ [Recursive inference](/theory_of_computation/grammar/recursive_inference.md)

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

