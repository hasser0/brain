+ [Graph](/dsa/data_structure/adt/graph.md)
+ [Tree](/dsa/data_structure/adt/tree.md)
+ [Queue](/dsa/data_structure/adt/queue.md)

## Breadth first search

BFS is an algorithm that **traverses a unweighted graph** starting from a root
node. The traverse is done on amplitude meaning that at each node, all the
adjacent nodes are processed before further nodes; for that reason it is used to
**find the shortest path** from one node to the rest.

The algorithm identifies three states for nodes

+ Undiscovered: Has not been found by other node and has not parent yet
+ Discovered: Has been found by other node, has a parent assigned, but its
  adjacent nodes has not been enqueued
+ Processed: Has been found, has a parent assigned and adjacent nodes has been
  enqueued

This states helps to create a **tree** from the graph such that each node has
one and only one parent, except for the root. During the algorithm, node's parent
and state are kept

BFS is used as the basis to more complex algorithms, to find the connected
components of a graph and discover whether a graph is bipartited or not

