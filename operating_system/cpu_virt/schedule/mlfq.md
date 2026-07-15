+ [Scheduler](/operating_system/cpu_virt/scheduler.md)
+ [SFJ](/operating_system/cpu_virt/schedule/sjf.md)

## Multi Level Feedback Queue

MLFQ is a more complex scheduler that introduces multiple new concepts such as

+ Multiple queues: each with different allotment and quantum time
+ Allotment time: time that a job can spend at a queue
+ Quantum time: fixed amount of time elapsed between context switch
+ Priority boost: operation that sets all jobs to the highest priority

The following rules specify its behaviour

1. Jobs within the same queue run on a Round Robin fashion
2. Queues could put jobs with IO operations at the begin or not
3. Each job stays at the same queue if
    + Either it consistently yields control within a time lower than allotment
      time
    + Or if its accumulated time is lower than the allotment time
4. The next running job is that at the front of the highest priority queue
5. From time to time a priority boost is done to avoid starving jobs

This schedule policy is similar to SJF but do not suppose run times are known

