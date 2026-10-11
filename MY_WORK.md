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
| **Full Name** | [nouf salem alhoity] |
| **Student ID** | [444051460] |
| **University Email** | 444051460@std.psau.edu.sa |
| **GitHub Username** | [Nouf-salem-444] |
| **Repository Link** | [https://github.com/Nouf-salem-444/OS-Assignment1-Nouf-salem] |
 
---

## 🎥 Video Link

**Video Link**: [https://drive.google.com/file/d/10FdJtjnLhMkFu_sYbOSuMCSzm-15TODR/view?usp=drivesdk]

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

### Entry 1 - [October9,2026,12:42AM]
**What I did**: project setup and initial testing

**Details**: frocked the repository,renamed it,update student iD and compiled the start code

**Challenges**: setting up the java development environment and understanging the project layout

**Solution**: istalled JDK and reviewed the instructions in README

**Time spent**: 2 hour

---

### Entry 2 - [October 9,2026,7:01AM]
**What I did**:implemented feature1(priority)

**Details**:added the priority field to the process class and set up random priority generation 

**Challenges**:integrating the priority attribute without breaking existing constructor logic 

**Solution**:update the process constructor and added getter method for priority

**Time spent**: 1.5 hours

---

### Entry 3 - [october10,2026,9:17pm]
**What I did**:implmented feature 2(context switch counter)

**Details**:added acounter to track how many time each thread switch context druing scheduling

**Challenges**:trcking preemption accurately across thread execution cycles 

**Solution**:incremented the context switch counter inside the run method druing scheduling rounds

**Time spent**: 1hour

---

### Entry 4 - [october11,2026,3:16am]
**What I did**:implemented feature 3(waiting time &summery table)

**Details**:tracked queue entry time using system.currentTimeMilis(),calculation waiting and turnaround time and added the final summary table

**Challenges**:calculating accurate delta time and formating the tabular output neatly

**Solution**:recoreded timestamps upon entry,cmputed waiting time dynamically and iterated through processMap.values()to print the table

**Time spent**: 2hours

---

### Entry 5 - [11october,2026,6:00pm]
**What I did**:final review ,testing ,and documentaion

**Details**:ran the complete simulation successfully,verified console output ,and prepared documentation

**Challenges**:ensuring all project requirements and formatting guidelines were met

**Solution**:double -checked outputs and ensured clean structure

**Time spent**:1.5 hours

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

**Most challenging part**:implementing accurate time tracking for process waiting times across multiple context switches

**Most interesting learning**:understanding how thread scheduling algorithms and time-slicted preemption work in java

**What I would do differently next time**:plan the time tracking logic structure earlier before writiting the implementation code

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

[Through this assignment i gained a deep practical understanding of how multiple threads execute concurrently and how an operating system manages them using scheduling algorithms like Round-Robin i learned how synchronization and state transitions (from New to Runnable, Running, Waiting, and Terminated) govern thread behavior in Java implementing context switching made me realize the underlying complexity of saving and restoring thread states. Furthermore, tracking thread execution times highlighted how CPU resources are time-sliced among competing tasks ultimately, this assignment transformed abstract OS concepts into tangible programming experience]

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

[The most challenging part of this assignment was implementing accurate time tracking for process waiting and turnaround times across multiple context switches snce threads are paused and resumed dynamically based on the time quantum, calculating the exact duration a process spent waiting in the ready queue required precise timestamps ensuring that queueEntryTime and waitingTime were updated correctly without causing calculation drifts was tricky debugging the timing logic demanded a solid grasp of both Java concurrency and system-level scheduling mechanics]

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

[To overcome the timing and logic challenges, i broke down the problem into smaller manageable steps and tested them incrementally i added descriptive print statements and used System.currentTimeMillis() at key entry and exit points in the run method to monitor state changes reviewing the Java concurrency documentation and analyzing how thread execution cycles interact with the ready queue helped clarify my implementation strategy testing the code frequently and running the simulation multiple times allowed me to catch calculation bugs early]

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

[Multithreading concepts are foundational for building responsive, high-performance real-world applications across various domains for instance, web servers use multithreading to handle thousands of concurrent client requests simultaneously without blocking the main application thread desktop and mobile user interfaces rely on background threads to perform heavy computations or network calls, keeping the UI smooth and responsive operating system kernels heavily depend on thread scheduling algorithms to distribute CPU cycles fairly among active applications ensuring optimal system throughput and responsiveness]

### Optional: What would you like to learn more about?

[Any topics related to threading or operating systems that you're curious about?]

### Optional: How confident do you feel about multithreading concepts now?

[Beginner / Intermediate / Confident. What do you understand well? What needs more practice?]

### Optional: Feedback on the assignment

[Any comments? Was it helpful? Too easy or hard? Suggestions?]

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

[process is an independent execution unit with its own memory space, whereas a thread is a lightweight execution unit inside a process that shares memory in this assignment, we simulated processes using the ⁠Process⁠ class, but executed them using real Java threads created via ⁠new Thread(process)⁠ in ⁠addProcessToQueue()⁠ we used threads instead of separate operating system processes because threads have significantly lower creation overhead and allow fast, direct memory sharing through shared structures like ⁠readyQueue⁠ and ⁠processMap]

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

[In Round-Robin scheduling, when a process exceeds its time quantum before finishing its execution, it is preempted and re-queued at the back of the ready queue for example, looking at my simulation output table, process P7 and P2 had longer burst times (such as 11671ms for P2) and experienced waiting times and turnaround times as they were cycled through the ready queue multiple times. This re-queueing mechanism prevents any single process from monopolizing the CPU, ensuring fair time-slicing and preventing process starvation ]

Example from my output:
```
[![alt text](image-1.png)]
```

**Explanation of example:**
[The output table shows the final simulation metrics for all threads managed by the Round-Robin scheduler. Each process displays its total burst time, calculated waiting time, and turnaround time. Processes with larger burst times, like P2 and P7, spent time waiting in the ready queue during context switches, resulting in higher turnaround times, while all processes successfully completed their executio]

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: [P1 enters the New state when instantiated using ⁠new Process(...)⁠ inside the initialization loop before it is added to the thread manager or execution queue]

2. **Runnable**: [P1 enters the New state when instantiated using ⁠new Process(...)⁠ inside the initialization loop before it is added to the thread manager or execution queue]

3. **Running**: [P1 enters the Running state when the scheduler dequeues it and its ⁠run()⁠ method begins executing its code logic within its allocated time quantum]

4. **Waiting**: [P1 enters the Waiting (Timed Waiting) state when it calls ⁠Thread.sleep()⁠ during its execution cycle or when preempted and placed back into the queue]

5. **Terminated**: [P1 reaches the Terminated state when its remaining burst time reaches zero, finishing its ⁠run()⁠ method execution while the main thread waits for it using ⁠Thread.join()]

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): [Operating System CPU Scheduler]

**Description**:
[A modern operating system core scheduler managing multiple user applications and system background services competing for processor time]

**Why Round-Robin works well here**:
[It guarantees fairness and responsiveness by allocating a fixed time quantum to each active process, preventing resource monopolization. In relation to our simulation, user tasks play the role of the "process", the CPU time-slice represents the "time quantum", and saving/restoring registers acts as the "context switch]

### Example 2: [Multi-User Web Server Request Handler]

**Description**:
[a web server (like Apache or Nginx) handling hundreds of simultaneous HTTP client requests, where each incoming request is processed using a shared thread pool.]

**Why Round-Robin works well here**:
[Time-slicing prevents heavy requests (like large file downloads) from blocking shorter interactive requests (like loading text data), maintaining low latency. Here, each HTTP request acts as the "process", the execution slice acts as the "time quantum", and thread switching handles the "context switch]

## Summary

**Key concepts I understood through these questions:**
1.How Round-Robin scheduling allocates CPU time slices fairly using a ready queue.
2.The differences between lightweight threads and heavy processes in memory and overhead
3.The lifecycle states of a thread from creation to termination during simulation.

**Concepts I need to study more:**
1.Advanced thread synchronization and deadlock avoidance mechanisms.
2.Detailed performance metrics analysis under different time quantum sizes.

---

# ✅ Final Checklist (complete before submitting)

> ⚠️ **WARNING:** Go through every line. Late submission costs **-1 mark per day**, and the deadline is **October 10, 2026**.

**Repository**
- [ x] Repository is **PUBLIC** (Settings → Danger Zone → Visibility)
- [ x] Repository is renamed to `OS-Assignment1-YourFirstName-YourLastName`
- [ x] GitHub account uses the university email (`@std.psau.edu.sa`)

**Code**
- [x ] Student ID is set in `SchedulerSimulation.java` (line 150)
- [x ] Code compiles and runs with no errors
- [x ] Feature 1 (priority), Feature 2 (context switches) and Feature 3 (waiting time table) all work
- [ x] Each feature has clear comments

**Commits**
- [ x] **At least 3 meaningful commits, ideally 6 or more**
- [x ] **One commit per feature**
- [ x] Commits are spread over **different dates** (not all in the last hour)
- [ x] Everything is **pushed** to GitHub

**This file (`MY_WORK.md`)**
- [ x] Full name and student ID filled in at the top
- [ x] Development log has **5+ entries** on different dates
- [ x] Reflection: 4 questions, 5-7 sentences each
- [ x] Technical answers: 4 questions, 3-5 sentences each, with examples from **your** output
- [ x] No `[...]` placeholders left
- [ x] No section headers deleted

**Video**
- [ ] 2-3 minutes long, named `StudentID_Assignment1_Demo.mp4`
- [ ] Shows your name, ID, repository, 3 features, IDE execution, one threading concept, and commit history
- [ ] Link is **public** (tested in an incognito window) and pasted in the **Video Link** section above

**Blackboard**
- [ ] Submit **only** the link to your public GitHub repository

> 🎯 **Good luck!** Start early, commit regularly, and make sure you can explain every line you submit.
