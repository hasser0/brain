+ [Graph](/dsa/data_structure/adt/graph.md)
+ [Graph traversal](/dsa/problems/graph_traversal.md)
+ [BFS](/dsa/algorithms/graphs/bfs.md)
+ [Stack](/dsa/data_structure/adt/stack.md)

## DFS

Depth first search is similar to BFS, but instead of pushing new nodes to a
queue, elements are pushed onto a **stack** so that newer elements are processed
first and as a result, the algorithm goes as deep as possible.

DFS has an interesting property on undirected graphs and is that the tree formed
has only two types of edges

+ Tree edges: Are part of the tree
+ Back edges: Connects a node with an ancestor exclusively

and also for directed graphs there are four cases

+ Tree edges
+ Forward edges: from ancestor to child
+ Backward edges: from child to ancestor
+ Cross edges: cousin connection

