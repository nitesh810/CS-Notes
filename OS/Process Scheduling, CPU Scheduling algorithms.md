- Process scheduling is a task of the operating system (OS) that removes a running process from the CPU and selects another process to run.
- It schedules processes into different states, such as ready, waiting, and running.
- Process scheduling is a key part of multiprogramming operating systems.

Process scheduling: 
- Removes a running process from the CPU
- Selects another process to run
- Schedules processes into different states
- Keeps the CPU busy all the time

![[Pasted image 20231121064724.png]]

-------------------------------------------------------------------------------
## CPU Scheduling algorithms

1. **Preemptive process-**
	These processes are based on the process priority.
	
2. **Non-preemptive process-**
	In these algorithms, if any process is assigned CPU, it will execute entirely. There is no process priority in this.


- ***Preemptive process
	
	1. **SJF** : The process who's burst time is less will execute first. ( ***Shortest Job First*** ) {can also be non-preemptive}.
	2. **RR** : Each process is assigned a fixed time slot. If a process does not complete its execution within its time, it is temporarily moved to the back of the queue, and the next process in the queue is given a chance to execute. ( ***Round Robin )
	3. **SRTF** : Selects the process with the shortest remaining burst time for execution.                   ( ***Shortest Remaining Time First)
	
- ***Non-preemptive process
	
	1. **FCFS** : The process that arrives first is executed first completely. ( ***First come, first serve )
	2. **Priority Scheduling** : the process with the highest priority is selected for execution first. {can algo be preemptive}.