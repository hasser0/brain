+ [State machine](/computer_systems/hardware/state_machines/fsm.md)
+ [Implicit control](/computer_systems/hardware/state_machines/implicit_control.md)

## Sequencer control

The logic of a sequencer is similar to **implicit control**, however an
**instruction** is added. This instruction also allows jumps, however it allow
to load from different parts such as

+ Micro PC: the increment of the previous address
+ Interrupt register: an external register for interruptions enabled using VECT
+ Transform register: another external register for custom loaded addresses
+ Next state from memory:

The available instructions are

+ Continue: Always take the next address using **Micro PC**
+ Conditional Jump: Similar to **implicit control**
+ Transform Jump: Always take the next address from **Transform register**
+ Conditional Interrupt Jump: Similar to **Conditional Jump** but on jump it takes
  from **Interrupt register**

The component in charge of coordinating registers based on the instructions
control the following signals

+ PL: Enables next state from memory
+ VECT: Enables **Interrupt register**
+ MAP: Enables **Transform register**
+ Selector: Selects either D or mPC, where D is a shared buffer with Interrupt,
  Transform and Next State registers.

Note: jumps are conditionally done based on TF xor Qs

