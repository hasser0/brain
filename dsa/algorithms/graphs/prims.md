+ [MST](/dsa/problems/minimum_spanning_tree.md)
+ [Greedy](/dsa/techniques/greedy.md)

## Prim's algorithm

Prim's algorithm for MST consist of incrementally adding the smallest edge that
from the spanning tree to a node not in the MST, until all nodes are connected
to this.

For each node a boolean flag for already visited nodes is used, as well as the
smallest distance to the node which is used to select the next insertion

