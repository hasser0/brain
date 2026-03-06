+ [Sequential](/hardware/chips/sequential.md)

## Latch

Latch gates is a family of circuits known to be **transparent** or **level
sensitive**; whenever the "clock signal" is high the output is the same as the
"data signal". Clock and data signals are different for each case, but on each
case, input changes are propagated as long as clock is enabled

+ SR latch: sets and resets output on signal and remember previous value if none
  is high
+ D latch: propagated D signal when clock signal is high

SR latch implementation is based on NAND/NOR crossed signals. D latch is
implemented by a wrapped SR latch and extra logic before S and R signals

