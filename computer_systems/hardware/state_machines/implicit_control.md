+ [State machine](/computer_systems/hardware/state_machines/fsm.md)
+ [Entry state control](/computer_systems/hardware/state_machines/state_entry_control.md)

## Implicit control

Implicit control is similar to entry state control. However it assumes one of
the paths is always equal to the following address $N+1$ so that the memory is
only composed of

+ Test
+ Next state jump
+ TF
+ Outputs

In this case **test** works similarly, but the resulting signal is compared
using a **xor** gate with **TF** and the result determines whether the next
state is the **incremented address** or a **jump** to another.

When TF == Qs then a jump is performed and the **next state jump** is passed enabled
in the register to load, otherwise an increment is perform

