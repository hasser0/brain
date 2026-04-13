+ [Maximum flow](/dsa/problems/network_flow.md)

## Matching bipartite

Given a graph $G=\langle V, E\rangle$, a matching is a subset of the edges such
that each vertex is at most once in any edge.

For a bipartite graph G with groups L and R, the matching bipartite problem
seeks for the largest subset of edges that is a matching.

Matching bipartite can be solved as a subproblem of maximum flow, where s node
is connected to all elements of L group and t node to all elements of R group.
Each edge's weight is equal to 1 and the matching is found by the maximum flow
from s to t.

