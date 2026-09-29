+ [Finite state machines](/computer_systems/hardware/state_machines/fsm.md)

## Path control

Path control is the simplest memory fsm design methodology. Its memory is
composed of

+ Next state
+ Outputs

In terms of architecture it is only compose of memory and program counter
register, which holds the address for the next state and asks memory for its
content on each state, sending output signals to the corresponding buffer.

Next state signals are combined with entries signals to calculate the next
address.

