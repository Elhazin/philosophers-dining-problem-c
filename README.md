# Philosophers-Dining-problem-C
<br>
<h5>The Philosophers' Dining Problem is a classic problem in computer science and concurrency control that deals with coordination between multiple processes or threads. It was first introduced by <a href="https://en.wikipedia.org/wiki/Edsger_W._Dijkstra">Edsger Dijkstra</a> in 1965.<br>

In the problem, there are n philosophers sitting around a table, each with their own plate and fork. The philosophers alternate between thinking and eating, and they need to use two forks to eat. The problem is to ensure that each philosopher can eat without getting into a <a href="https://en.wikipedia.org/wiki/Deadlock">deadlock</a> or a starvation situation.<br>

The solution to this problem involves using a lock or a <a href="https://en.wikipedia.org/wiki/Semaphore_(programming)">semaphore</a> to control the access to the forks, ensuring that no two philosophers are able to pick up the same fork at the same time.</h5><br>

 ## What is Deadlock ? 
  <h5><em>
A deadlock is a state in computer programming where two or more <a href="https://www.gnu.org/software/libc/manual/html_node/Processes.html">processes</a> are blocked and unable to continue executing because each process is waiting for the other to release a resource that it holds. This creates a situation where both processes are stuck and can no longer make progress, resulting in a "deadlock" where neither process can proceed. This can lead to a system hang, causing the affected processes and potentially the entire system to become unresponsive. Deadlocks can occur in multi-process or multi-threaded systems, and are a common synchronization problem in computer science.</em></h5>
 <br>

 
 ##   What is Datarace ?
  <h5>
 A data race is a condition in computer programming where multiple threads attempt to access and modify a shared piece of data concurrently, leading to unpredictable results. It occurs when the execution order of operations on the shared data is not well defined, leading to a race between the threads to access and modify the same memory location. This can result in data inconsistencies, errors, and crashes, making data races a major concern in multithreaded programming.</h5>
 
 <br>
 
 ##  What is <a href="https://www.geeksforgeeks.org/multithreading-in-c/">thread</a> ?
 
 <h5>
 A thread in C can be thought of as a tiny, independent piece of a puzzle that helps to complete a larger picture. Think of a puzzle with multiple pieces, each piece represents a thread and each thread is unique in its own way, contributing to the overall solution. Just like a puzzle piece, a thread performs a specific task and works in harmony with other threads to complete the program efficiently.</h5>
