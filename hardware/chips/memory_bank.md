+ [Sequential chip](/hardware/chips/sequential.md)
+ [Register](/hardware/chips/register.md)

## Memory bank

A memory bank is chip able to read and write multiple registers using an address
location. As inputs it has

+ Read flag
+ Write flag
+ Address
+ Input bits for write operations

as output it has only the output digits from the address. Memory banks has two
parameters

+ Register's word size
+ Address size

Both determine the size of each element and the number of elements that the chip
can handle

