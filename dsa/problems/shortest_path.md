## Shortest path

Given a graph, shortest path is a problem that consists on finding the shortest
path between two pair of points. Most algorithms take advantage of a property of
any shortest path from s to t and is that
$$
\text{dist}(s,t) = \min_{v\in V} \Big( \text{dist}(s,v) + \text{dist}(v,t) \Big)
$$
That means that any decomposition of the path in subparts are also shortest
paths

