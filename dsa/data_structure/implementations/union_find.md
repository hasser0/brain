+ [Contiguous](/dsa/data_structure/contiguous.md)
+ [Disjoint set](/dsa/data_structure/adt/disjoint_set.md)

## Union find

A union find is an implementation of a disjoint set that uses an array of size
equals to the number of elements in the entire set such that each index stores a
pointer to another element in the array. Each disjoint set is conceptually
stored in a tree where each node points to its parent and the root points to
itself.

Merging two disjoint sets implies connecting all the elements of one set to any
of the elements of the other set as parents.

Testing whether two elements are on the same set is done with the root element
of the test. When the root of both elements is the same, both are in the same
set

