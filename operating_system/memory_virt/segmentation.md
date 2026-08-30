+ [Fragmentation](/operating_system/memory_virt/fragmentation.md)

## Segmentation

Segmentation is a memory management technique that divides the address space
into different sections according to its purpose. Generally this sections are

+ Code
+ Stack
+ Heap

The division allows to allocate different memory parts into separated physical
address of variable size which means that there is an improvement in memory
utilization from the vanilla approach of a single contiguous block. However
variable size chunks come with the cost of fragmentation.

