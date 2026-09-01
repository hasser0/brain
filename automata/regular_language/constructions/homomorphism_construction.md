+ [DFA](/automata/regular_language/deterministic.md)
+ [Homomorphism](/automata/basics/homomorphism.md)

Let $h:\Sigma^* \mapsto\Gamma^*$ be an homomorphism.

Define
$$
M=\langle Q,\Gamma,\delta,s,F\rangle
$$
and from this define another DFA
$$
N=\langle Q,\Sigma,\delta',s,F\rangle
$$
where
$$
\delta'(q,a) = \delta(q,h(a))
$$
N is a DFA, the question is whether $L(N) = L(h^{-1}(M))$. Is a good idea to
prove that
$$
\hat{\delta'}(q,xy) = \hat{\delta}(q,h(x)h(y))
$$

