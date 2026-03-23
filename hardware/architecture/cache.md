+ [SRAM](/hardware/architecture/sram.md)
+ [Memory hierarchy](/hardware/architecture/memory_hierarchy.md)

## Cache

Since CPU needs to interact with memory constantly, by the time CPU got faster
than memory and so the interaction become a bottleneck. Cache is a memory
section implemented with SRAM so it is fast, but due its cost it is usually
small, ranging from KB to a few MB. Cache stores only part of the main memory
that might be used soon due **spatial and temporal locality**; to identify the
part of the main memory that is being used we use **mappings**

+ Direct: Each part of the main memory has a unique possible position in
  cache
+ N-associative: Each part of the main memory has N possible positions
  in cache
+ Fully associative: Each part of the main memory can be at any position in
  cache

Cache is usually divided into levels such as L1, L2 and L3 but the mechanism
remain the same across different memory types.

Other concepts are

+ Capacity: size of the cache
+ Sets: cache locations used as a whole to associate
+ Associativity: number of locations in cache a main memory address can occupy
+ Blocks: Minimal unit of memory that is moved from main memory to cache

