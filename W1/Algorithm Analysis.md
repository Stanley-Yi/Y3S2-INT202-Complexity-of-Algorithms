## Algorithm Analysis

- **Primary interest**: Running **time** (time-complexity) of the algorithm and the operations on datastructures.
- **Secondary interest**: **Space** (or "memory") usage (space-complexity).

***

### Two ways of algorithm analysis

#### 1. Experimental Analysis
Analysis algorithm by take possible inputs.

Running-time depends on both the **size and instance of input** and the **algorithm** used, as well as the **software and hardware environment** on which it is run.

#### 2. Theoretical Analysis

When we analyze an algorithm in this fashion, we aim to associate a function f (n) to each algorithm, where f (n) characterizes the running-time in terms of some measure of the input-size, n.

Typical functions include: n, log n, n<sup>2</sup>, n log n, 2<sup>n</sup>, ...

*Algorithm A runs in time proportional to n.*

### Average-vs. Worst-CaseComplexity

![image](D:/Files/Learning%20Materials/Y3/Semester-2/INT202/Note/Screenshot%202021-03-06%20185218.png)

- **Average-case complexity** refers to running time as an average taken over all inputs of the same size.
- **Worst-case complexity** refers to running time as the maximum taken over all inputs of the same size.
***
![image](D:/Files/Learning%20Materials/Y3/Semester-2/INT202/Note/Screenshot%202021-03-06%20192041.png)
