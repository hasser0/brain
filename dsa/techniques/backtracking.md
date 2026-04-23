+ [Recursion](/dsa/techniques/recursion.md)
+ [DFS](/dsa/algorithms/graphs/dfs.md)

## Backtracking

Backtracking is an special case of recursion that solves a subproblem by finding
the best decision among all current possibilities and whenever no solution is
possible for the path, backtrack and tries a different path.

Backtracking is similar to **DFS**. The root is the initialized data for the
problem. At each step, if the current state is a solution the node is processed,
otherwise new candidates are created and traversed as DFS, yielding a recursive
structure. While traversing the different possibilities, the solution structure
is changed according to the current candidate and unchanged when moving to
another possibility at the same level of the tree.

