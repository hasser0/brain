+ [State machines](/computer_systems/hardware/state_machines/fsm.md)
+ [MUX](/computer_systems/hardware/chips/mux.md)

## State entry control

State entry control memory is composed of

+ Test: binary encoding of entries in multiplexor
+ True next state: next state in case test is true
+ False next state: next state in case test is false
    + Qx
+ True outputs: outputs in case test is true
+ False outputs: outputs in case test is false

Entries are selected using a multiplexer with selector **test**. The result of
this operation determines the **next state** and its **outputs** which are
passed to the register in the following clk rising edge.

Note that this architecture allow only one entry to be tested on each cycle. If
no entry is needed **Qx** should be should which has a constant value.

