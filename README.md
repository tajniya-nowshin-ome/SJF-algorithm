# SJF-algorithm

Lab Report: Shortest Job First (SJF) Algorithm

Objective:
The objective of this lab report is to understand and analyze the Shortest Job First (SJF) scheduling algorithm, which selects processes based on their burst times for execution.

Algorithm Overview:
SJF (Shortest Job First) selects the process with the smallest execution time to execute next.
It can be preemptive or non-preemptive.

Characteristics:
Minimizes average waiting time.
Greedy algorithm.
May cause starvation (solved using aging).
Requires accurate burst time estimates.
Practical in specialized environments.


Steps for Non-Preemptive SJF :
Input:
Arrival time and burst time for each process.

Sort Processes:
Sort processes by arrival time.

Execution:
Execute the process with the minimum burst time.
If a process arrives during execution, add it to the pool.
Select the next process from the pool with the minimum burst time.

Metrics:
Completion time: Time when a process completes.
Turnaround time: Completion time minus arrival time.
Waiting time: Turnaround time minus burst time

Conclusion:
The SJF algorithm efficiently schedules processes based on burst times, minimizing waiting time. It is useful in scenarios with accurate burst time estimates.
