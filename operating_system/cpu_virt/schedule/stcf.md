+ [Scheduler](/operating_system/cpu_virt/scheduler.md)
+ [Preemptive](/operating_system/cpu_virt/schedule/preemptive.md)
+ [SJF](/operating_system/cpu_virt/schedule/sjf.md)

## Shortest Time to Completion First

STCF is the preemptive version of SJF. That means that whenever a new job is
created, a context switch is made if the new job is shorter than the remaining
of the current process. This again suposse times are known by the OS.

