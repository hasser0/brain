+ [Adjacency matrix](/dsa/data_structure/implementations/adjacency_list.md)
+ [Shortest path](/dsa/problems/shortest_path.md)
+ [DP](/dsa/techniques/dynamic_programming.md)

## Floyd-Warshall algorithm

Floyd's algorithm is used to find the shortest path of all pairs in a graph.

Previous to the algorithm, all nodes are numbered so an order is created. Let
$$
W[i,j]^k = \min\Big(W[i,j]^{k-1},W[i,k]^{k-1} + W[k,j]^{k-1}\Big)
$$
where $W[i,j]^k$ is the shortest distance from node i to node j passing through
edges not beyond k. Iterating from 1 to n(number of nodes) we end up with $W^n$
being the matrix with the shortests distances passing through all nodes,
therefore the shortest distance matrix. The path is only recoverable if at the
same time a parent matrix mantained.

