## Isolation

Isolation asserts that every transactions and its data views are not affected by
other transactions. This includes reads and writes.

There are many known problems that may arise from isolation

+ Dirty reads
+ Dirty writes
+ Read skew
+ Write skew
+ Lost updates
+ Phantom reads

Some approaches solve some of the previous problems and are known as **weak
isolation**

+ Read uncommitted
+ Read committed
+ Reapetable read
+ Snapshot isolation

Other approaches solve all of them simulating actual serialization and are known
as **strong isolation**

+ Actual serial execution
+ Two phase locking(2PL) or pessimistic locking
    + Share locks
    + Exclusive locks
+ Serializable snapshot isolation or optimistic locking

