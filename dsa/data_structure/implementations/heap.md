+ [Data structure](/dsa/data_structure/data_structure.md)
+ [Priority queue](/dsa/data_structure/adt/priority_queue.md)

## Heap

A heap is a contiguous array representing a binary tree, which implements a
partial order where each root element is smaller than its children. Any element
of the $l$ level is in the range of $2^{l-1}$ to $2^l$ indexes. For any given
index $k$ we can find its children in $2k$ and $2k+1$ indexes and its parent at
$\lfloor{k/2}\rfloor$.

+ Insertion is at the last index of the array and bubbling up
+ Search minimum is constant time since it is at the first index
+ Removing the top element is done by inserting the last index at the top and
  bubble down
