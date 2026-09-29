+ [DFA](/theory_of_computation/regular_language/deterministic.md)
+ [2DFA](/theory_of_computation/regular_language/2dfa.md)
+ [Myhill Nerode relations](/theory_of_computation/regular_language/myhill_nerode_relation.md)
+ [Myhill Nerode theorem](/theory_of_computation/regular_language/myhill_nerode_theorem.md)
+ [Equivalence class](/math_foundations/set_theory/equivalence_relation/equivalence_class.md)

## 2DFA is equivalent to DFA

Given a DFA, a 2DFA is simply constructed from.

Notion: The string $xz$ might be view with $z$ an agent that sends different
states $q$ to $x$ to get new information from it. The resulting state is new
information and this map is $T_x$(defined below). When $T_x=T_y$ then $xz$ and
$yz$ are identical in some sense.

Let $M$ be a 2DFA, then for any string $x\in\Sigma^*$ with $|x|=n$, define the function
$$
T_x:Q\cup\{\bullet\}\mapsto Q\cup\{\perp\}
$$
such that

+ $T_x(\bullet) = \perp$ iff $\langle(s,0),(q,n+1)\rangle\notin R_x^*$
+ $T_x(\bullet) = p$ iff $\langle(s,0),(q,n+1)\rangle\in R_x^k$ where $k$ is the
  smallest value with such a property
+ $T_x(q)=p$ iff $\langle(q,n),(p,n+1)\rangle\in R_x^k$ where $k$ is the
  smallest value with such a property

The equality relation for functions on this set of functions is an equivalence
relation that is also a Myhill Nerode relation; therefore $L(M)$ is regular set

1. There is a finite number of such functions, therefore there is only a finite
   number of equivalence classes
2. This is right congruent, so that $T_x=T_y$ implies $T_{xa}=T_{ya}$
3. This is a refinement of $L(M)$

