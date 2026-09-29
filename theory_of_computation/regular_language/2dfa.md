+ [DFA](/theory_of_computation/regular_language/deterministic.md)

## Two way DFA

Let $\Sigma'=\Sigma\cup\{\vdash,\dashv\}$. Two way DFA is an octect
$$
M=\langle Q,\Sigma,\vdash,\dashv,s,t,r,\delta\rangle
$$
where

+ $\vdash,\dashv\notin\Sigma$
+ $s,t,r\in Q$ such that $t\neq r$
+ $\delta: Q\times\Sigma'\mapsto Q\times\{L,R\}$

For every string $x$ declare $x'=\vdash x\dashv$. Then at each step, $\delta$
is in some state $p$ and reads symbol $s\in\Sigma'$ and returns another state
with a moving direction $\{L,R\}$.

The only constrains on $\delta$ are that

+ it cannot go beyond the limits of $\vdash, \dashv$
+ whenever it enters state $t$ or $r$ it stays the same and move to the right if
  possible
+ $M$ accepts $x$ iff $(s,0)R_x^*(t,i)$ for any i
+ $M$ rejects $x$ iff $(s,0)R_x^*(r,i)$ for any i

See the following section

## Configurations

A configuration is a tuple $(p,i)\in Q\times\mathbb{N}$. This is not attach to
a particular $M$ yet, however the intuition is that $(p,i)$ corresponds to a
moment in the processing of $x'$ where it is reading $x_i$ in state $p$.

Define inductively $R_x^n$ as follows

For the base case $(p,i)R_x^0(q,j)$ iff $p=q, i=j$

For $n+1$ suppose it is defined $R_x^n$. Further suppose $(p,i)R_x^n(q,j)$
and $\delta(q,x_j)=(r,\square)$ then

1. If $\square=L$ then $(p,i)R_x^{n+1}(r,j-1)$
2. If $\square=R$ then $(p,i)R_x^{n+1}(r,j+1)$

Define
$$
R_x^* = \bigcup_{k=0}^\infty R_x^k
$$


