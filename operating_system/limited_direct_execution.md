+ [Mechanism](/operating_system/mechanism.md)
+ [Syscalls](/operating_system/syscalls.md)
+ [Trap table](/operating_system/trap_table.md)
+ [Kernel and User mode](/operating_system/kernel_user_mode.md)

## Limited Direct Execution

Limited Direct Execution is a mechanism used by operating systems to time share
the CPU among many processes by running them directly on hardware and limiting
dangerous operations.

Code loaded directly on the CPU either runs as kernel or user mode; **kernel
mode** is allowed to perform any operations, while **user mode** is only allowed
to perform operations on registers. LDE handle security on IO operations by
restricting them to kernel mode only and exposing a set of **syscalls** which
allow users to interact with peripherals. Syscalls are associated with a number
in a **trap table** that is set at boot time to prevent malicious changes.
