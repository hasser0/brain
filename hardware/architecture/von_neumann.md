+ [Stored procedure](/hardware/architecture/stored_procedure.md)
+ [Universal Turing](/automata/recursive_enumerable_language/universal_turing.md)
+ [CPU](/hardware/architecture/cpu.md)
+ [Memory mapped IO](/hardware/architecture/memory_mapped_io.md)
+ [Port mapped IO](/hardware/architecture/port_mapped_io.md)

## Von Neumann architecture

The Von Neumann architecture is a computer blueprint with the stored procedure
in mind. The main goal of the architecture is to provide a framework to build
general purpose computers. The elements of this architecture are

+ Central Processing Unit
+ Memory
+ Input and output devices

### CPU

The CPU is responsable of fetching instructions, understand them and assure that
instructions are processed correctly.

### Memory

Memory stores not only data, but **instructions** and since data and instruction
space is the same, they share a **single buffer** to communicate; since a single
buffer is used to read instructions and data, a performance issue arise called
**Von Neumann bottleneck**.

### IO devices

The CPU interact with IO devices that in turn interact with the outside world
using either memory mapped IO or port mapped IO

