+ [CPU](/hardware/architecture/cpu.md)
+ [Memory](/hardware/chips/memory_array.md)
+ [IO devices](/hardware/architecture/io_devices.md)
+ [Port mapped IO](/hardware/architecture/port_mapped_io.md)

## Memory mapped IO

Memory mapped IO is a technique used to connect the CPU with IO devices using
memory banks, mainly in RAM, as interfaces. Memory mapped devices has a **range
of address** in memory which are used to interact with the CPU; for input
devices, that memory area ensures to communicate the internal state, for output
devices that memory area is used as a buffer to send data.

Memory mapped is easier to implement, more reliable and scalable than port
mapped; even though port mapped is faster, memory mapped IO is the standard due
its simplicity and flexibility

