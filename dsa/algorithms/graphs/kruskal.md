+ [MST](/dsa/problems/minimum_spanning_tree.md)
+ [Union find](/dsa/data_structure/implementations/union_find.md)
+ [Greedy](/dsa/techniques/greedy.md)

## Kruskal's algorithm

The Kruskal algorithm is an algorithm for the minimum spanning tree problem that

1. Sorts the edges of the graph increasingly by weight
2. Initialize a union find data structure with as many sets as elements
3. Iteratively selects the smallest edge and test whether both nodes of the edge
   are on the same disjoint set or not. If both are on different sets, the edge
   is inserted in the MST and both sets are merged

