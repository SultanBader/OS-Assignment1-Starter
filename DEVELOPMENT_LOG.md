# Development Log

## Instructions
Document your development process as you work on the assignment. Add entries showing:
- What you worked on
- Problems you encountered
- How you solved them
- Time spent

**Requirements**: Minimum 5 entries showing progression over time.

---

## Example Entry Format:

### Entry 1 - [April 1, 2026, 2:30 PM]
**What I did**: Forked the repository and set up my student ID

**Details**: 
- Created GitHub account with university email
- Forked the starter repository
- Changed student ID on line 92 to my actual ID (441234567)
- Compiled and ran the program successfully

**Challenges**: Had to install JDK first because javac wasn't recognized

**Solution**: Downloaded JDK 17 from Oracle website and set PATH variable

**Time spent**: 30 minutes

---

## Your Development Log:

### Entry 1 - [1 april , 4 pm ]
**What I did**: Started working on the assignment and explored the starter code

**Details**: Opened the project and understood the structure of the code
- Analyzed Process class and SchedulerSimulation class
- Ran the program to observe the output

**Challenges**: Understanding how threads execute and how scheduling is simulated


**Solution**: Reviewed lecture notes and studied how Runnable and threads work

**Time spent**: 2 hours

---

### Entry 2 - [2 april , 3 pm ]
**What I did**: Implemented Feature 1 (Process Priority)

**Details**: Added priority variable to Process class
Modified constructor to include priority
Created getter method for priority
Updated output to display priority in ready queue

**Challenges**: Updating constructor without breaking object creation

**Solution**: Carefully updated all Process creation lines in main method

**Time spent**: 2 hours 

---

### Entry 3 - [2 april , 5 pm]
**What I did**: Implemented Feature 2 (Context Switch Counter)

**Details**: Added static variable to count context switches
Incremented counter before thread.start()
Printed total context switches at the end

**Challenges**: Finding the correct place to increment the counter

**Solution**: Analyzed the scheduler loop and placed it before thread execution

**Time spent**: 1 hour 

---

### Entry 4 - [2 april , 5:30 pm ]
**What I did**: Implemented Feature 3 (Waiting Time)

**Details**:  Added arrivalTime and waitingTime variables
 Calculated waiting time inside run()
 Updated arrival time when process is re-added to queue
 Added getter method for waiting time

**Challenges**: Calculating waiting time accurately

**Solution**: Used System.currentTimeMillis() and tested step by step

**Time spent**: 1 hours 

---

### Entry 5 - [2 april , 7 pm ]
**What I did**: Tested the program and verified all features

**Details**: 
 Ran the simulation multiple times
 Checked output for correctness
 Ensured all features work together without errors


**Challenges**: Ensuring no conflicts between features

**Solution**: Debugged the code and tested each feature separately

**Time spent**: 1 hours 

---

### Entry 6 - [Optional - Date and Time]
**What I did**: 

**Details**: 

**Challenges**: 

**Solution**: 

**Time spent**: 

---

## Summary

**Total time spent on assignment**: [8 hours ]

**Most challenging part**: 
Implementing the waiting time calculation correctly
**Most interesting learning**: 
Understanding how threads are scheduled using Round-Robin algorithm
**What I would do differently next time**: 
Start earlier and test each feature more frequently
