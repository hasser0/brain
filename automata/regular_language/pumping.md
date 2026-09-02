+ [Regular languages](/automata/regular_language/regular_language.md)

## Pumping lemma

For any language $L$ there is a constant $n$ such that for all strings $w\in L$
such that $|w| \ge n$ $w=xyz$ where

1. $y\neq \varepsilon$
2. $|xy| \le n$
3. For all $k\ge 0$ $xy^kz\in L$

Proof.

Let $n$ be the number of states of the automata corresponding to $L$ and
$w\in L$ such that $|w|=m>n$ then by the pigeon hole principle exists
$1\le i\neq j\le n$ such that
$$
\delta(p_0,w_1\cdots w_i) = \delta(p_0, w_1\cdots w_j)
$$
and $w = w_1\cdots w_i\cdots w_j\cdots w_n = xw_i\cdots w_j z = xyz$
and for any $k\ge 0$ $xy^kz\in L$

