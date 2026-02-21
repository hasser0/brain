+ [State](/automata_theory/basics/state.md)

## States equivalences

Let $a$, $b$ be states of $A=\langle Q_A,\Sigma_A,\delta_A,q_A,F_A\rangle$ and
$B=\langle Q_B,\Sigma_B,\delta_B,q_B,F_B\rangle$. This applies to different
automatas or the same automata at the same time. They are equivalent iff for
every word $w$, including the $\varepsilon$ string
$$
\delta(a, w)\in F_A \leftrightarrow \delta(b, w)\in F_B
$$
This relation between states is an equivalence relation, since it is symmetric,
reflexive and transitive
