+ [Shortest path](/dsa/problems/shortest_path.md)
+ [BFS](/dsa/algorithms/graphs/bfs.md)
+ [Greedy](/dsa/techniques/greedy.md)

## Dijkstra's algorithm

Dijkstra's shortest path algorithm that finds the shortest path from a single
vertex to all the other points. Traversing the graph using BFS at each node we
process all the edges updating distances and parents when a faster path than the
current is found.

However, Dijkstra only works as expected when the edge's weights are all
positive, when a negative edge is found it might create a loop on the path

