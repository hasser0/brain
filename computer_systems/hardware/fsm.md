+ [Sequential](/computer_systems/hardware/chips/sequential.md)
+ [Mealy machine](/theory_of_computation/regular_language/mealy_machine.md)
+ [Moore machine](/theory_of_computation/regular_language/moore_machine.md)

## Finite state machine

Synchronous sequential circuits are generally represented using FSM. A FSM is
conceptually composed of

+ Inputs
+ State
+ Outputs

On each rising edge, current state changes to the next state based on

+ Current state(Moore machine)
+ Current state and inputs(Mealy machine)

States are represented by a binary encoding, stored at the circuit's registers

