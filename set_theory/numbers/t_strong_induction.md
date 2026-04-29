+ [Natural](/set_theory/numbers/naturals.md)
+ [Well order principle](/set_theory/numbers/t_well_order.md)
+ [Inductive set](/set_theory/numbers/inductive_set.md)

## Strong induction

Any set $A$ with the property that, $n<k\rightarrow n\in A$ implies $k\in A$,
is an inductive set and $A=\omega$

### Proof

The set $\omega - A$ is a subset of $\omega$ that doesn't comply with such
property, so it has a least element $\alpha$, since it is the minimum of the
set, any element $n<\alpha$ is in $A$, but by the definition of the set $A$ this
implies $\alpha\in A$ so $\omega-A$ is empty

