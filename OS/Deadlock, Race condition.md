When 2 or more threads are fighting for the resources but none of them getting the resources.
In this situation, none of the processes gets executed since the resource it needs is held by some other process which is also waiting for some other resource to be released.

**How deadlock is achieved:** Deadlock happens when Mutual exclusion, hold and wait, No preemption and circular wait occurs simultaneously.

Necessary Conditions for deadlock:

1. Mutual Exclusion
2. Hold and Wait
3. No preemption
4. Circular Wait

By eliminating 1 of these 4 conditions can break deadlock. 

## Race condition
When multiple threads are trying to access the shared resources occur race condition.
Means fight between different thread for resources and other thread are not getting the resources and that thread dies.