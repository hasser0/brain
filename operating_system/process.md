+ [Virtualization](/operating_system/virtualization.md)
+ [CPU](/hardware/architecture/cpu.md)
+ [Program](/operating_system/program.md)
+ [Machine state](/operating_system/machine_state.md)
+ [Context switch](/operating_system/context_switch.md)
+ [Schedule policy](/operating_system/schedule/schedule_policy.md)
+ [Process list](/operating_system/process_list.md)
+ [Process state](/operating_system/process_state.md)

## Process

Process is an abstract concept used by the operating system that virtualize the
CPU. Multiple process share the CPU splitting the total time, scheduled by the
main process(the operating system) that among other tasks do a context switch to
replace the old process with the new process that the schedule policy indicates.

The operating system maintains a data structure called process list to manage
the orchestration of these and keeping the process state during this task

