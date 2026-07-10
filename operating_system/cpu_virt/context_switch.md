+ [Mechanism](/operating_system/mechanism.md)
+ [Machine state](/operating_system/cpu_virt/machine_state.md)

## Context switch

The context switch is a mechanism used to swap the current running process which
involves

1. Storing the running process machine state
2. Changing the state of the previously deschedule process
3. Loading into memory and into the CPU the machine state of the new process
4. Delegate running to the new scheduled process

