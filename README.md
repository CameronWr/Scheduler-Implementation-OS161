
Cameron Wright\
Dr. Ribeiro\
CSE4001 Sect. 01\
13th of November 2020

<h2><p align="center">
Implement Scheduler Assignment
</p></h2>

### Design:
To properly measure the effectiveness of my design against others, simple metrics need to be defined. The first of these metrics is turnaround time, which is a measure of performance and is the average time it takes each thread to complete. Thus, the longer threads have to wait in the queue, the worse the turnaround time will be. The second metric is response time, which measures reactivity and is the time between scheduling (executing) each thread. Thus, the longer the time between thread scheduling, the worse the response time. Now that there are defined metrics, I can compare my design to others.

I decided to implement a FIFO (First In First Out) or FCFS (First Come First Serve) scheduler that works by running each process in the order they arrive.

![First In First Out](FIFO-Diagram.png)\

FIFO is the simplest scheduler implementation, as it's just a simple queue. Thus it has sub-optimal turnaround times, in general, compared to others such as SJF (Shortest Job First) or STCF (Shortest Time to Completion First). Both of these scheduler implementations attempt to run the shortest of all the threads in the run queue first, resulting in equal or quicker turn around times than FIFO (see diagrams below).

![Shortest Job First](SJF-Digram.png)\
![Shortest Time to Completiton First](CTCF-Diagram.png)\
While turn around time is important in measuing 

### Implementation:

### Benchmark:

<h4><p align="center">
Default Scheduler [Round Robin]
</p></h4>

![](Default-Hog.png)\
![](Default-Farm.png)\
![](Default-Pong.png)

<br />

<h4><p align="center">
Implemented Scheduler [FIFO]:
</p></h4>

![](FCFS-Hog.png)\
![](FCFS-Farm.png)\
![](FCFS-Pong.png)

#### Sources:
*All scheduler diagrams are from [Operating Systems: Three Easy Pieces (Arpaci-Dusseau)](http://pages.cs.wisc.edu/~remzi/OSTEP/ "E-Book")*.
