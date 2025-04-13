### What is a Distributed System?
A distributed system is a network that stores data on more than one node (physical or virtual machines) at the same time. Another way to state that, a distributed system is a collection of independent computers (or nodes) that work together as a single system to achieve a common goal. These computers communicate and coordinate with each other over a network. It is essential to understand the CAP theorem when designing an app so that we can choose a data management system that delivers the characteristics our application needs most.

### What is the CAP Theorem?
The CAP theorem is a fundamental principle of distributed systems. It postulates three potential system attributes: Consistency, Availability, and Partition Tolerance. However, a distributed system cannot guarantee all three attributes simultaneously.

### Visual Representation
![CAP Theorem](https://github.com/sharminshanta/system-design/blob/85bed68cea77e6a88da1d4ded6eef8e7ce869f6c/images/CAP_Theorem.png)

### The Three Attributes: Consistency, Availability, and Partition Tolerance(CAP)

### Consistency(C): 
All nodes in the system have the same data at the same time, and any data written to the system is immediately visible to all nodes.

### Availability(A): 
Every request makes to the system receives a response, either with the requested data or an error message.

### Partition Tolerance(P): 
The system continues to operate – ensuring both C and A as defined above – despite network partitions (i.e., messages lost or the failure of part of the network).

