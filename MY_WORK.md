# 📝 MY_WORK: Student Information, Development Log, Reflection & Answers

> This is the **only file** your instructor reads to grade Parts 3 and 4 (documentation and video). Everything you write here must be **in your own words**.

---

## 🛑 STOP: Read This Before You Do Anything Else

> ### 1️⃣ Read the whole `README.md` first
> The `README.md` in this repository contains the full instructions: class descriptions, feature specifications, question prompts and the video script. **If you skip it, you will lose marks.**
>
> ### 2️⃣ Understand the full code before answering any question
> Open `SchedulerSimulation.java` and read it **from top to bottom**. You must be able to explain what `Process`, `run()`, `runToCompletion()`, `addProcessToQueue()`, `Thread.start()`, `Thread.join()` and `Thread.sleep()` do **before** you write a single answer in Parts B and C. Run the program at least once and watch the output.
>
> ### 3️⃣ Commit many times, not once
> A single commit, or all commits made in the last hour, costs you **-0.5 mark**. See the [Commit Rules](#-commit-rules-mandatory) below.

**How to use this file:**
1. Fill in your **Student Information** (below) right now.
2. Follow the steps in the **Work Roadmap** in order.
3. Update the **Development Log** *every time* you work on the assignment, not at the end.
4. Do not delete any section header. Replace the `[...]` placeholders with your own text.

---

## 👤 Student Information

> ⚠️ **WARNING:** Fill this in first. Your name and ID must match the student ID you set in `SchedulerSimulation.java` (line 150) and the one you say in your video.

| Field | Your Answer |
|-------|-------------|
| **Full Name** | [Write your full name here] |
| **Student ID** | [Write your student ID here] |
| **University Email** | [yourid]@std.psau.edu.sa |
| **GitHub Username** | [your-github-username] |
| **Repository Link** | [Paste your repository link here] |
 
---

## 🎥 Video Link

**Video Link**: [Paste your video link here]

> ⚠️ **WARNING:** The video must be **publicly accessible** ("Anyone with the link can view") on **Google Drive**, **YouTube (Unlisted or Public)** or any other cloud file-sharing system. A private, restricted or broken link counts as a **missing video (-1 mark)**.
>
> 💡 **TIP:** Open the link in a **private/incognito window** before you submit. If it asks you to log in or request access, it is not public.
>
> 📌 **NOTE:** The link goes in **this file only** (`MY_WORK.md`), **not** in `README.md`. Name your video file `StudentID_Assignment1_Demo.mp4`. It must last **2 to 3 minutes**.

---

## 🗺️ Work Roadmap (follow in this order)

| Step | What to do | Where | Marks |
|:----:|------------|-------|:-----:|
| 0 | Read `README.md`, then read and run the full code | Your IDE | – |
| 1 | Fork, rename, keep the repo **PUBLIC**, set your student ID (line 150), **commit** | GitHub + code | Part 1 (1) |
| 2 | Feature 1: Process Priority, **commit** | Code | Part 2 (0.25) |
| 3 | Feature 2: Context Switch Counter, **commit** | Code | Part 2 (0.25) |
| 4 | Feature 3: Waiting Time Tracking, **commit** | Code | Part 2 (0.5) |
| 5 | Development Log (5+ entries, different dates) | This file, Part A | Part 3 (0.5) |
| 6 | Reflection (4 questions) | This file, Part B | Part 3 (0.5) |
| 7 | Technical Answers (4 questions) | This file, Part C | Part 3 (0.5) |
| 8 | Record the video, upload it, paste the link above | Video + this file | Part 4 (1.5) |
| 9 | Final check, then submit the repo link on Blackboard | Blackboard | – |

> 💡 **TIP:** Tick each step off as you go. Do not leave the log, the reflection or the video for the last day.

---

## 🔁 Commit Rules (MANDATORY)

> ### ⚠️ MANY COMMITS ARE REQUIRED. A single bulk commit is penalized (-0.5 mark).

**Minimum: 3 meaningful commits. Aim for 6 or more.**

| # | Commit | Example message |
|:-:|--------|-----------------|
| 1 | Student ID set | `Set my student ID: 441234567` |
| 2 | Feature 1: Priority | `Feature 1: Added priority field to Process class` |
| 3 | Feature 2: Context switches | `Feature 2: Implemented context switch counter` |
| 4 | Feature 3: Waiting time | `Feature 3: Added waiting time tracking and summary table` |
| 5 | Development log entries | `Docs: Added development log entries 1-3` |
| 6 | Reflection and answers | `Docs: Completed reflection and technical answers` |
| 7 | Video link | `Docs: Added demo video link` |

**Rules:**
- ✅ **One commit per feature.** Do not put all three features in one commit.
- ✅ **Commit after each work session**, and after each part of this file.
- ✅ **Spread your commits over different dates.** Not all in one day.
- ❌ **Do not make all commits in the last hour** before the deadline.
- ❌ **No vague messages** like `done`, `update` or `final version`.

> 💡 **TIP:** Your commit history is checked and you **show it in your video** (at least 3 commits visible). Your development log dates should match your commit dates.
>
> 💡 **TIP:** **Use VS Code** (see *Recommended Development Environment* in `README.md` for the full setup). Sign in to GitHub in VS Code, then commit from the Source Control panel (Ctrl+Shift+G) → stage → write a message → Commit → Sync/Push. You can edit and commit this file the same way. **Pushing** matters: commits that are not pushed to GitHub are invisible to the instructor.

---

# Part A: Development Log (0.5 mark)

> ⚠️ **WARNING:** Minimum **5 entries**, spread over **different dates**. Five entries written on the same day, or written all at once at the end, will lose marks and look like a copy. Entry dates should be **between the start of the assignment and the deadline (October 10, 2026)**.
>
> 💡 **TIP:** Write an entry at the **end of each work session**, while you still remember what happened. It takes 5 minutes.
>
> 💡 **TIP:** Be specific. "Worked on the code" is a weak entry. "Added a `static int contextSwitches` counter and incremented it before `currentThread.start()`" is a strong one.
>
> 📌 **NOTE:** Each entry needs: date and time, what you did, details, challenges, solution, and time spent. Real challenges are fine (and expected). Do not invent fake ones.

## Example Entry (do not copy it, write your own)

### Entry 1 - [September 22, 2026, 2:30 PM]
**What I did**: Forked the repository and set up my student ID

**Details**:
- Created GitHub account with university email
- Forked the starter repository and renamed it
- Changed student ID on line 150 to my actual ID (441234567)
- Compiled and ran the program successfully
- Committed and pushed: `Set my student ID: 441234567`

**Challenges**: Had to install JDK first because `javac` wasn't recognized

**Solution**: Downloaded JDK 17 and set the PATH variable

**Time spent**: 30 minutes

---

## Your Development Log

### Entry 1 - [October 5, 2026, 7:00 PM]
**What I did**:studied the assignment on CPU Scheduler Simulation.

**Details**:I went over the assignment specifications and looked into SchedulerSimulation's structure.Java. I concentrated on the scheduler loop, the time quantum, the ready queue, and the Process class. I also looked at how simulated processes are represented by Java threads.

**Challenges**:recognizing the distinction between a genuine Java thread and a simulated process.

**Solution**:I traced how a Process object is passed to new Thread(process) and how the scheduler starts and joins threads.

**Time spent**:1 hour

---

### Entry 2 - [October 8, 2026, 9:00 PM]
**What I did**: Implemented Feature 1: Process Priority.

**Details**:I included getter and setter methods, a priority field, and randomized priorities ranging from 1 to 10. Without altering the FIFO scheduling sequence, I modified the ready-queue output to show the priority of each task.

**Challenges**:ensuring that the Round-Robin scheduling behavior was unaffected by the priority value.

**Solution**:I just used priority as extra process information while maintaining the original queue operations.

**Time spent**:1 hour

---

### Entry 3 - [October 8, 2026, 10:00 PM]
**What I did**: Implemented Feature 2: Context Switch Tracking.

**Details**:Every time the scheduler initiated a new process execution, I added a static counter and increased it. After every procedure was finished, I printed the final counter. There were 29 context shifts in my recorded run.

**Challenges**:choosing the location of the counter's increment.

**Solution**:In order to count each scheduled execution, I put the increment in the scheduler loop before currentThread.start().

**Time spent**:1 hour

---

### Entry 4 - [October 9, 2026, 2:00 AM]
**What I did**: Implemented Feature 3: Waiting Time and Turnaround Time.

**Details**:I used System to add time-tracking fields and methods.currentTimeMillis(). When processes joined the ready queue, I noted the waiting intervals and totaled the waiting time prior to execution. Additionally, I printed a final summary table and saved the processes in allProcesses.

**Challenges**:calculating waiting time over several Round-Robin runs without accounting for CPU execution time as waiting time.

**Solution**:Every time a process reentered the ready queue and accrued waiting time prior to the subsequent execution, I reset the waiting interval.

**Time spent**:3 hour

---

### Entry 5 - [October 9, 2026, 4:00 PM]
**What I did**:evaluated the finished simulation and worked on the Part 3 documentation.

**Details**:I used a 5000 ms time quantum to examine the output for 13 processes. The simulation showed a waiting-time summary for each of the 13 processes as well as 29 context transitions. I confirmed that P1's turnaround time (92613 + 10197 = 102810 ms) matched the necessary formula. Using samples from my simulation output, I also worked on the technical answers, reflection questions, and development log.

**Challenges**:confirming the consistency of the scheduler output and summary values while providing a comprehensive explanation of the underlying ideas.

**Solution**:I verified the turnaround-time computations, compared the end table to the execution log, and supported my written responses with real output examples.

**Time spent**:2 hour

---

### Entry 6 - [Optional - Date and Time]
**What I did**:

**Details**:

**Challenges**:

**Solution**:

**Time spent**:

---

## Development Log Summary

> 💡 **TIP:** Fill this in **last**, after all entries are written.

**Total time spent on assignment**: [8 hours]

**Most challenging part**:monitoring the amount of time spent waiting for repeated entries into the ready queue.

**Most interesting learning**:Recognizing how a Round-Robin queue allows processes to run repeatedly and how Java threads may be utilized to mimic CPU scheduling.

**What I would do differently next time**:Instead of reconstructing it after the fact, I would prepare the code modifications and testing procedures in advance and maintain a development log while working.

---

# Part B: Reflection (0.5 mark)

> 🛑 **STOP:** Do **not** start this part until you have read the `README.md`, read the **entire** `SchedulerSimulation.java`, run it, and finished the three features.
>
> ⚠️ **WARNING:** Each answer must be **5 to 7 sentences**, in **your own words**. Copied or AI-generated answers without understanding get **0 marks for the whole assignment**. You may be asked to explain them in person.
>
> 💡 **TIP:** Mention concrete things you actually did: a method you wrote, an error you hit, a line of output you saw. Generic answers score low.
>
> 💡 **TIP:** Draft your answer in a few bullet points first, then turn them into sentences.

## Question 1: What did you learn about multithreading?

> 💡 **TIP:** Talk about thread creation (`Runnable`, `Thread.start()`), waiting with `Thread.join()`, simulating work with `Thread.sleep()`, and what surprised you.

**Your Answer:** *(5-7 sentences)*

[I discovered that a Java program may handle several threads within a single application thanks to multithreading. Every simulated process in this assignment was linked to a Java thread. I discovered that while Thread.join() causes the main thread to wait for a thread to finish, Thread.start() initiates a thread's execution. I also realized that Thread.sleep() can mimic how long a process runs without always utilizing the CPU. One significant finding was that the simulation's thread start order is determined by the ready queue. This made it easier for me to comprehend how CPU scheduling and Java threading are related.]

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

[Implementing the waiting-time calculation in Feature 3 was the most difficult aspect. Before its burst time is up, a process may enter the ready queue multiple times. As a result, a single calculation of waiting time would not accurately reflect all of its waiting periods. I had to know when a process was added to the queue and when it began running. Additionally, I had to refrain from adding execution time to the total waiting time. Compared to just showing priority or increasing a counter, this feature required more meticulous tracking.]

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

[I tackled the task by focusing on a single aspect at a time. Before determining where each modification belonged, I went over the pertinent sections of SchedulerSimulation.java. I separated waiting intervals from execution for the waiting-time functionality using markReadyQueueEntry() and recordWaitingTime(). After that, I checked the final output table after running the simulation. For instance, I confirmed that P1's turnaround time was 101959 ms, which is equal to its burst time of 10197 ms plus its waiting time of 91762 ms. I was able to verify whether the computations complied with the assignment requirements by testing the output following the code modifications.]

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

[Applications that must complete multiple tasks without becoming unresponsive can benefit from multithreading. For instance, several threads can be used by a web browser to manage user interactions and page loading. While reacting to user controls, a music application might keep playing music. The scheduler in my simulation chose which simulated process to run next by using a ready queue. This made it easier for me to comprehend how scheduling allows tasks to share processing opportunities. When creating applications that require responsive interfaces and background activities, I can use these concepts.]

### Optional: What would you like to learn more about?

[I'm interested in learning more about race scenarios, thread synchronization, and the actual context shifts that operating systems carry out.]

### Optional: How confident do you feel about multithreading concepts now?

[in the middle. I am aware of time quantum, basic scheduling, thread generation, and the function of start() and join(). I still need to work on my synchronization and concurrent thread execution skills.]

### Optional: Feedback on the assignment

[The assignment made it easier to relate Java code to operating system ideas. Observing process execution and re-queuing was made simpler by the scheduling output. Although it was difficult, tracking waiting time was helpful in comprehending Round-Robin scheduling.]

---

# Part C: Technical Answers (0.5 mark)

> 🛑 **STOP:** You cannot answer these questions without understanding the code. Re-read `SchedulerSimulation.java` and **run it** first. Your answers must reference **your own code and your own output** (your student ID makes your output unique).
>
> ⚠️ **WARNING:** Each answer must be **3 to 5 sentences**, with specific examples from your code or output. Use correct terms: thread, process, time quantum, ready queue, context switch, burst time.
>
> 💡 **TIP:** Keep your program output in a text file or screenshot so you can copy real snippets for Question 2.

## Question 1: Thread vs Process

**Question**: Explain the difference between a **thread** and a **process**. Why did we use threads in this assignment instead of creating separate processes? Mention at least **TWO** specific differences (e.g., memory sharing, creation overhead, communication speed), and reference relevant parts of `SchedulerSimulation.java`.

> 💡 **TIP:** Note that the class named `Process` in our code is a *simulated* process, and it is run by a real Java *thread*. Explain that distinction and point to the `new Thread(process)` line in `addProcessToQueue()`.

**Your Answer:** *(3-5 sentences)*

[While threads inside a single Java process share memory and resources, a process is an autonomous program execution with its own memory area. Compared to distinct operating-system processes, threads are typically less expensive to construct and interact between. Instead of representing an actual operating system process, SchedulerSimulation.java's Process class simulates a process. The Java thread that runs the simulated process is created by the addProcessToQueue() function using new Thread(process). This method enables the assignment to show scheduling behavior in a single Java program.]

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

[In Round-Robin scheduling,A process is moved back to the end of the ready queue if it does not complete within its time quantum. P1 had a burst time of 10197 ms and a time quantum of 5000 ms in my simulation. P1 was added back to the ready queue with 5197 ms left after its first execution. It was re-queued once more with 197 ms left after its second execution, for a total of two re-queues prior to completion. Because other waiting processes receive CPU time before P1 executes again, this behavior ensures fairness. ]

Example from my output:

[▶ P1 executing quantum [5000ms]
⏸ P1 completed quantum 5000ms
   Remaining time: 5197ms
↻ P1 yields CPU for context switch

➕ P1 added to ready queue │ Burst time: 10197ms │ Priority: 8

▶ P1 executing quantum [5000ms]
⏸ P1 completed quantum 5000ms
   Remaining time: 197ms
↻ P1 yields CPU for context switch

➕ P1 added to ready queue │ Burst time: 10197ms │ Priority: 8

▶ P1 executing quantum [197ms]
   Remaining time: 0ms
✓ P1 finished execution!]
```

**Explanation of example:**
[Because P1's entire burst time exceeded two time quanta, it required three execution turns. Before completing its last 197 ms, it made two trips back to the ready queue. Instead of allowing P1 to use the CPU continually, this permitted other processes to run in between P1's turns.]

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: [P1's Java thread enters the New state when new Thread(process) creates it inside addProcessToQueue()]

2. **Runnable**: [When the scheduler calls currentThread.start(), P1's thread becomes eligible for CPU execution and enters the Runnable state.]

3. **Running**: [P1 begins executing its run() method when the JVM schedules its thread, as shown by P1 executing quantum [5000ms] in my output.]

4. **Waiting**: [During the simulated execution, P1 enters the TIMED_WAITING state when Thread.sleep() is called, while the main thread waits for P1's thread to finish using currentThread.join().]

5. **Terminated**: [P1's Java thread ends when it completes its allotted quantum; the simulation then starts a new thread for P1's subsequent turn until the procedure is finished in 197 ms.]

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): [Time-Sharing Operating System]

**Description**:
[CPU time must be divided among several runnable tasks by a time-sharing operating system. Before the next available work is taken into consideration, each task in a simple Round-Robin scheduler is given a set time quantum. Each turn is limited by the time quantum, and the tasks match the simulated operations in my software.]

**Why Round-Robin works well here**:
[One CPU-bound task cannot take up all of the processor thanks to Round-Robin. Frequent scheduling and context changes improve responsiveness and fairness by allowing other prepared jobs to advance.]

### Example 2: [Background Task Processing in an Application]

**Description**:
[Document transformations and data processing are examples of independent background jobs that an application may need to handle. Before going on to the next task, a simplified cooperative scheduler may assign a finite amount of processing labor to each job. In my simulation, these jobs would function as processes, with each processing slice standing in for a time quantum.]

**Why Round-Robin works well here**:
[Instead of letting one big job cause all the others to be delayed, a Round-Robin strategy can assist spread processing chances among jobs. When multiple jobs are waiting, this makes progress more predictable; however, a practical implementation must also take resource requirements and task priorities into account.]

## Summary

**Key concepts I understood through these questions:**
1.the distinction between real Java threads and simulated processes, including thread lifespan and creation.
2.How Round-Robin scheduling distributes execution opportunities equitably using a time quantum and a FIFO ready queue.
3.How scheduler behavior is described by waiting time, turnaround time, and context-switch counting.

**Concepts I need to study more:**
1.Race situations, shared memory security, and thread synchronization
2.How actual operating systems measure scheduling performance and execute context shifts.

---

# ✅ Final Checklist (complete before submitting)

> ⚠️ **WARNING:** Go through every line. Late submission costs **-1 mark per day**, and the deadline is **October 10, 2026**.

**Repository**
- [ ] Repository is **PUBLIC** (Settings → Danger Zone → Visibility)
- [ ] Repository is renamed to `OS-Assignment1-YourFirstName-YourLastName`
- [ ] GitHub account uses the university email (`@std.psau.edu.sa`)

**Code**
- [ ] Student ID is set in `SchedulerSimulation.java` (line 150)
- [ ] Code compiles and runs with no errors
- [ ] Feature 1 (priority), Feature 2 (context switches) and Feature 3 (waiting time table) all work
- [ ] Each feature has clear comments

**Commits**
- [ ] **At least 3 meaningful commits, ideally 6 or more**
- [ ] **One commit per feature**
- [ ] Commits are spread over **different dates** (not all in the last hour)
- [ ] Everything is **pushed** to GitHub

**This file (`MY_WORK.md`)**
- [ ] Full name and student ID filled in at the top
- [ ] Development log has **5+ entries** on different dates
- [ ] Reflection: 4 questions, 5-7 sentences each
- [ ] Technical answers: 4 questions, 3-5 sentences each, with examples from **your** output
- [ ] No `[...]` placeholders left
- [ ] No section headers deleted

**Video**
- [ ] 2-3 minutes long, named `StudentID_Assignment1_Demo.mp4`
- [ ] Shows your name, ID, repository, 3 features, IDE execution, one threading concept, and commit history
- [ ] Link is **public** (tested in an incognito window) and pasted in the **Video Link** section above

**Blackboard**
- [ ] Submit **only** the link to your public GitHub repository

> 🎯 **Good luck!** Start early, commit regularly, and make sure you can explain every line you submit.
