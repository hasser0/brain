+ [Sequential](/hardware/chips/sequential.md)
+ [Rising edge](/hardware/timing/rising_edge.md)
+ [Latch](/hardware/chips/latch.md)

## Flip flop

A flip flop is a rising edge gate; that means that "data signal" is
propagated to the output only at the rise of the "clock signal"

+ D flip flop: propagate D signal previous to rising edge and remember current
  cycle value the rest of the time
+ Enable flip flop: similar to D flip flop but D propagates when both clock and
  enable signal are high
+ Reset flip flop: similar to D flip flop with an extra input that resets the
  saved value to a known constant when activated

D flip flop is implemented with two chained D latches with inverted clock
signals that acts as a semaphore
