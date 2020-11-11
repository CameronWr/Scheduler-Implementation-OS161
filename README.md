
Cameron Wright\
Dr. Ribeiro\
CSE4001 Sect. 01\
13th of November 2020

<h2><p align="center">
Implement Scheduler Assignment
</p></h2>

### Design:
I decided to implement a FIFO (First In First Out) or FCFS (First Come First Serve) scheduler that works by running each process in the order they arrive.

![](FIFO-Diagram.png)\
FIFO is the simplest scheduler implementation and has sub-optimal turn around times in general compared to others such as SJF (Shortest Job First). An SJF scheduler runs the shortest of all the threads in the run queue first, often resulting in a quicker turn around time (see diagram).

![](SJF-Digram.png)

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
