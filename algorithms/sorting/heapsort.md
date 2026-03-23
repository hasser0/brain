+ [Selection sort](/algorithms/sorting/selection_sort.md)
+ [Priority queue](/algorithms/data_structure/adt/priority_queue.md)
+ [In-place algorihtm](/algorithms/algorithms/inplace.md)

## Heapsort

Heapsort improves selection sort by using a priority queue to reduce the
algorithmic time to search and delete the min element. Particularly uses the
heap implementation of a priority queue.

The heap can be created from the bottom up calling bubble down on each subtree.
The last $n/2$ elements are already sorted heaps. Then bubbling down from $n/2$
towards $1$ we create the heap.

Heapsort can be implemented as an in-place algorithm since the last element of
the sorted array and the top of the heap overlap, but extra care of the heap
structure is needed on each iteration to update the root.
