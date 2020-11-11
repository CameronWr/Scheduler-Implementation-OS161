
Cameron Wright\
Dr. Ribeiro\
CSE4001 Sect. 01\
13th of November 2020

<h2><p align="center">
Implement Scheduler Assignment
</p></h2>

### Design:
I decided to implement a FIFO (First In First Out) or FCFS (First Come First Serve) scheduler that works by running each process in the order they arrive.

![First In First Out](FIFO-Diagram.png)\
*First In First Out*

FIFO is the simplest scheduler implementation as it's just a simple queue and thus it has sub-optimal turn around times, meaning the average time it takes to run a task, in general compared to others such as SJF (Shortest Job First) or STCF (Shortest Time to Completiton First). Both of these scheduler implamentations attempt to run the shortest of all the threads in the run queue first, resulting in equal or a quicker turn around times than FIFO (see diagrams below).

![Shortest Job First](SJF-Digram.png)\
*Shortest Job First*\
![Shortest Time to Completiton First](CTCF-Diagram.png)\
*Shortest Time to Completiton First*

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
