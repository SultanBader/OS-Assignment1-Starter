# Reflection Questions

## Instructions
Answer the following questions about your learning experience. Each answer should be **at least 5-7 sentences** and show your understanding.

---

## Question 1: What did you learn about multithreading?

** I learned that multithreading lets a single program run more than one task at the same time, which makes it faster and more efficient. This assignment taught me how to make threads with the Runnable interface and how each thread runs on its own. I also learned about the different states of a thread's life cycle, such as New, Runnable, Running, Waiting, and Terminated. I learned that threads use scheduling algorithms like Round-Robin to share CPU time. I also learned how to use methods like start() and join() to control how threads run. This task also taught me how operating systems handle many processes at once. Overall, my understanding of multithreading became much clearer through practical implementation. **

[Write your answer here. Discuss specific concepts like thread creation, thread states, how threads execute concurrently, what surprised you, etc.]

---

## Question 2: What was the most challenging part of this assignment?

** The hardest part of this task was getting the waiting time feature to work right. During scheduling, it took a lot of knowledge to know how processes move in and out of the ready queue. It was hard for me to find the right place in the code to figure out how long people had to wait without changing how the program worked. Also, working with System. time calculations.At first, currentTimeMillis() was hard to understand. Debugging multithreaded behavior was also harder because mistakes weren't always easy to see. Another problem was making sure that all the features worked together without any problems. These problems, on the other hand, helped me learn more about how scheduling works. **

[Describe the specific challenge. Was it understanding the code? Implementing a feature? Using Git? Explain what made it difficult and how it relates to the course concepts.]

---

## Question 3: How did you overcome the challenges you faced?

** I was able to get through the problems by breaking them down into smaller, more manageable steps. Before I made any changes, I carefully looked at the existing code to see how each part works. I also used debugging methods like printing out intermediate values to see how the program was working. Going over the lecture notes and looking at the textbook helped me remember important ideas. I made sure that everything worked by testing each feature on its own before putting them all together. I also looked for examples and explanations to help me understand the hard parts better. I was able to solve the problems with time and practice. **

[Describe your problem-solving approach. Did you read documentation? Ask for help? Debug systematically? What resources did you use? What strategies worked?]

---

## Question 4: How can you apply multithreading concepts in real-world applications?

** Many real-world applications use multithreading to make things run faster and respond better. For instance, web browsers use multiple threads to load different tabs at the same time without making the interface freeze. Threads are used in video streaming apps to play back and buffer video at the same time. Multithreading is also used by games to handle graphics rendering, physics calculations, and user input all at the same time. Threads are used by mobile apps to do background tasks while keeping the user interface responsive. These examples show how multithreading can make things better for users. This task helped me see how these ideas work in real systems. **

[Give specific examples from real applications you use (web browsers, games, mobile apps, etc.). Explain why threads are useful in those scenarios. Connect to what you learned in this assignment.]

---

## Additional Reflections (Optional)

### What would you like to learn more about?

I want to learn more about advanced scheduling algorithms like multilevel feedback queues and priority scheduling. It looks like these algorithms are important for making the system work better and more fairly. I am also interested in learning about synchronization problems like deadlocks and race conditions. It would be very helpful to know how to find and fix these problems. I also want to learn more about how operating systems work with large-scale concurrent systems. It would help me understand these ideas better if I learned about how they work in the real world. In general, I want to learn more about more advanced operating system topics.

[Any topics related to threading, concurrency, or operating systems that you're curious about?]

---

### How confident do you feel about multithreading concepts now?

I would say that I have an intermediate level of understanding of multithreading concepts. I now know how to make threads and how they run at the same time in a program. I know how to do basic thread operations like start() and join(). But I still need to practice more with advanced scheduling and complex synchronization. Some ideas, like race conditions and deadlocks, need more study. I think my confidence will grow if I get more practice. In general, I feel better than I did before, but I still have room to grow.


[Rate yourself and explain: Beginner / Intermediate / Confident]

[Explain your rating - what do you understand well? What needs more practice?]

---

### Feedback on the assignment

This task really helped me understand multithreading in a real-world way. It let me use what I learned in class about theory to write real code. The tasks were hard but doable, which helped the learning process work. Adding features one at a time helped people understand things better over time. Using GitHub also helped me get better at version control. But some parts needed more explanation, especially for people who were new to it. In general, it was a useful and enriching experience.

[Any comments about the assignment? Was it helpful? Too easy/hard? Suggestions for improvement?]
