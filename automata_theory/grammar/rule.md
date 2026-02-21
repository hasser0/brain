+ [Non terminal symbol](/automata_theory/grammar/non_terminal.md)
+ [Terminal symbol](/automata_theory/grammar/terminal.md)

## Production rule

Given a set of terminals $T$ and a set of non terminals $V$, a production rule
is a relation $\alpha\rightarrow\beta$ such that $\alpha\in(V\cup T)^*V(V\cup T)^*$
and $\beta\in(V\cup T)^*$

For a given set of production rules of $G$ the relation $\rightarrow$ can be
generalized to $\Rightarrow$ such that
$$
\alpha\Rightarrow\beta\equiv\alpha\rightarrow\gamma_1\cdots\gamma_n\rightarrow\beta
$$

