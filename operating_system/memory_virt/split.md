+ [Mechanism](/operating_system/mechanism.md)
+ [Free list](/operating_system/memory_virt/free_list.md)

## Split

Split is a memory management mechanism used to mantain **free lists**. When a
new incoming process needs more memory, either by assigning or by extending, it
needs to find a free chunk of memory and split it into the needed part and the
remaining one.

