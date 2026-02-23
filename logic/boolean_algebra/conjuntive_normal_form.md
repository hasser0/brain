+ [Boolean expression](/logic/boolean_algebra/boolean_expression.md)
+ [Truth table](/logic/propositions/truth_table.md)
+ [Maxterm](/logic/boolean_algebra/maxterm.md)

## Conjuntive normal form (CNF)

Given a boolean expression $\alpha$ with $n$ variables, the conjuntive normal
form is the equivalent expression of the form
$$
\prod_{j} \sum_{i=1}^n f_j(x_i)
$$
where $x_i$ is the ith variable in the expression and $f_j$ is the function that
maps each variable to $x_i$ or $\bar x_i$ based on the truth value for the $j$
entry of $\alpha$ truth table. The sum is calculated over the entries $j$ such
that $f_j(\alpha)=0$

Also called

+ Product of sums
+ Product of maxterms
+ Maxterm expansion

