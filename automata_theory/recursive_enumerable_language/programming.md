+ [Turing machine](/automata_theory/recursive_enumerable_language/turing_machine.md)

## Turing machine extensions

The following extensions are not extensions in the sense that they are more
powerful than simple turing machines, but they are easier for programming and
more expressive

### Memory at control unit

We can emulate memory at control unit using $[p,R_1,\dots,R_n]$ as states where
each $R_i$ is a register in the control unit. This can be converted to a
classical TM creating a new state per $[p,R_1,\dots,R_n]$ combination

### Multiple tapes

We can emulate multiple tapes using $[X_1,\dots,X_n]$ as strip's head. This can
be converted to a classical TM creating a new symbol per $[X_1,\dots,X_n]$
combination

### Subrutines

We can create subrutines $S$ that are also Turing machines a use the in multiple
places as function calls. This can be converted to a classical TM replacing the
subroutine call with the current implemenation

