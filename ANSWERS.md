# Assignment Questions

## Instructions
Answer all 4 questions with detailed explanations. Each answer should be **3-5 sentences minimum** and demonstrate your understanding of the concepts.

---

## Question 1: Thread vs Process

**Question**: Explain the difference between a **thread** and a **process**. Why did we use threads in this assignment instead of creating separate processes?

**Your Answer: A thread is a smaller part of a process that runs on the same memory as the process itself. A process is a separate program that has its own memory and system resources. Processes are harder to make and run than other things. On the other hand, threads are light and quick to make. It's easier for threads to talk to each other because they share the same memory space. Threads were used in this task to efficiently simulate concurrent execution. Using processes instead would add extra work that isn't needed. So, threads are better for this kind of simulation. **

[Write your answer here. Consider: What is a process? What is a thread? How do they differ in terms of memory, resources, creation overhead? Why are threads more suitable for this simulation?]

---

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from your program output.

**Your Answer: With Round-Robin scheduling, if a process doesn't finish in the time it was given, it goes back to the ready queue. This gives other processes a chance to use the CPU. The scheduler keeps going through the queue until all of the processes are done. This behavior makes sure that all processes are treated fairly. It stops one process from taking over the CPU. Every process has the same chance to run. This is a very important part of Round-Robin scheduling. **

[Write your answer here. Describe the specific behavior - where does the process go? When does it run again? Give an example from your actual program output showing a process that was re-queued.]

Example from my output:
P1 completed quantum 4000ms  
Remaining time: 3139ms  
P1 yields CPU for context switch  
P1 added to ready queue 
```
[Paste a relevant snippet from your program output here showing a process being re-queued]
```

**Explanation of example: This shows that P1 did not finish execution within its time quantum. It still had remaining time, so it was returned to the ready queue. After that, other processes were allowed to execute. This demonstrates how Round-Robin scheduling maintains fairness. **
[Explain what's happening in the output snippet you pasted]

---

## Question 3: Thread States

**Question**: A thread can be in different states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (P1) from your simulation.

**Your Answer: During its life cycle, a thread goes through a number of different states. Before process P1 starts running, it is in the New state. When you call start(), it goes to the Runnable state, which means it's ready to run. When the CPU starts running it, it goes into the Running state. When Thread.sleep() is called, the thread goes into the Waiting state for a short time. Once it has finished executing and all of its time, it goes into the Terminated state. This lifecycle shows how threads are handled when they are scheduled. **

[Write your answer here. For each state, explain when P1 enters that state during the simulation. Use your understanding of the code to trace through the lifecycle.]

1. **New**:P1 is in this state when the thread object is created but not started yet. [When is P1 in New state?]

2. **Runnable**: P1 becomes Runnable when start() is called and it is ready for execution. [When does P1 become Runnable?]

3. **Running**: P1 is in Running state when it is actively executing on the CPU. [When is P1 Running?]

4. **Waiting**: P1 enters Waiting state when Thread.sleep() is called during execution. [When/why would P1 be Waiting?]

5. **Terminated**: P1 reaches this state when its remaining time becomes zero and execution finishes. [When is P1 Terminated?]

---

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. Explain why this scheduling algorithm works well for those scenarios.

**Your Answer:**

### Example 1: [Web Server Example 1  
A web server uses threads to handle multiple client requests at the same time. There is a separate thread for each request.  
Why Round-Robin is a good choice here: Round-Robin makes sure that everyone gets a fair amount of CPU time for their requests. It makes things more responsive and keeps requests from being delayed for too long.]

**Description**: 
[Describe the real-world scenario or application]

**Why Round-Robin works well here**: 
[Explain why Round-Robin scheduling is suitable. Consider fairness, responsiveness, predictability, etc.]

### Example 2: [Example 2: An app for streaming video  
Description: Threads are used by video streaming apps to handle playback, buffering, and user interaction all at the same time.  
Why Round-Robin works well in this case: Round-robin scheduling makes things run smoothly by giving each task an equal amount of CPU time. This makes sure that playback goes on without a hitch and that controls work right away.]

**Description**: 
[Describe the real-world scenario or application]

**Why Round-Robin works well here**: 
[Explain why Round-Robin scheduling is suitable. Consider fairness, responsiveness, predictability, etc.]

---

## Summary

**Key concepts I understood through these questions:**
1. Difference between threads and processes  
2. Round-Robin scheduling and ready queue behavior  
3. Thread lifecycle and execution states  

**Concepts I need to study more:**
1. Advanced scheduling algorithms  
2. Thread synchronization and deadlocks  
