+ [Virtualization](/operating_system/virtualization.md)
+ [Process](/operating_system/cpu_virt/process.md)
+ [Context switch](/operating_system/cpu_virt/context_switch.md)
+ [LDE](/operating_system/cpu_virt/limited_direct_execution.md)
+ [Scheduler](/operating_system/cpu_virt/scheduler.md)

## CPU Virtualization

On earlier computer systems, programs used to be orchestrated and switched by a
human that needed to await until some program ended to allocate another one. At
the same time a single program running on the CPU get into an IDLE state when it
issues an IO operations, which is a waste of CPU resources that could be used on
other programs.

On that basis, a program that handle program switch on IO operations to
distribute resources among **processes** as efficient is desirable. One
possibility for such program would be to **context switch** different processes
when IO operations were needed. However, multiple processes running at the same
unrestricted on the same resources is dangerous so some kind of protection from
one an another so other mechanism such as **LDE** were created to isolate them.

The decision of whether a process should be switch impacts directly on the
efficiency of the system and creating a realistic and efficient policy is aimed
by different **schedulers**

