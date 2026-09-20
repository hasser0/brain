+ [Virtualization](/computer_systems/os/virtualization.md)
+ [CPU](/computer_systems/hardware/architecture/cpu.md)
+ [Program](/computer_systems/os/program.md)
+ [Machine state](/computer_systems/os/cpu_virt/machine_state.md)
+ [Context switch](/computer_systems/os/cpu_virt/context_switch.md)
+ [Schedule policy](/computer_systems/os/cpu_virt/scheduler.md)
+ [Process list](/computer_systems/os/cpu_virt/process_list.md)
+ [Process state](/computer_systems/os/cpu_virt/process_state.md)

## Process

Process is an abstract concept used by the operating system that virtualize the
CPU. Multiple process share the CPU splitting the total time, scheduled by the
main process(the operating system) that among other tasks do a context switch to
replace the old process with the new process that the schedule policy indicates.

The operating system maintains a data structure called process list to manage
the orchestration of these and keeping the process state during this task

