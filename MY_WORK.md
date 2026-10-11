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
| **Full Name** | [nourah sultan alazizi] |
| **Student ID** | [444051471] |
| **University Email** | [444051471]@std.psau.edu.sa |
| **GitHub Username** | [NouraTech26] |
| **Repository Link** | [  https://github.com/NouraTech26/OS-Assignment1-Nourah-alazizi] |
 
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

> 💡 **TIP:** Tick each step off as you go. Dolink not leave the log, the reflection or the video for the last day.

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

### Entry 1 - [october 4,2026]
**I created my GitHub account and started setting up my Operating Systems assignment repository.**:

**Details - Created my GitHub account.
- Started preparing my Operating Systems assignment repository.**:

**Challenges I had some difficulty understanding how to set up my GitHub repository because it was new to me.**:

**Solution  I followed step-by-step instructions and learned how to create and set up my GitHub repository.**:

**Time spent  2 hours**:

---

### Entry 2 - [october 5,2026]
**What I did I installed Java and set up VS Code to run my Operating Systems assignment.  **:

**Details - Installed the Java Development Kit (JDK).
- Set up VS Code with the Java extensions.
- Prepared the environment to compile and run the Java program..**:

**Challenges I had difficulty setting up Java and making sure VS Code could run the program correctly. **:

**Solution  I installed the JDK and Java extensions, followed the setup instructions, and tested the program in VS Code.**:

**Time spent 3 hours**:

---

### Entry 3 - [Date and Time october 6,2026]
**What I did  worked on running and understanding the Java scheduling simulation.**:

**Details  SchedulerSimulation.java file.
- Learned how the Round Robin scheduling simulation works.
- Practiced compiling and running the Java**:

**Challenges  Understanding the scheduling logic and how the processes were executed was difficult at first.**:

**Solution I reviewed the code step by step and tested the program to understand its output. **:

**Time spent 3 hours**:

---

### Entry 4 - [Date and Time october 7,2026]
**What I did  I worked on adding the required features to the scheduling simulation.**:

**Details  .
- Added a counter to track context switches.
- Added waiting time tracking for processes.**:

**Challenges  : I needed to understand how to add the new features without breaking the existing program.**:

**Solution  made changes to the Java code and compiled and ran the program to check the results.**:

**Time spent  2 hours**:



### Entry 5 - [Date and Time october 8,2026]
**What I did worked on documenting my assignment progress in MY_WORK.md.**:

**Details  .
- Added my GitHub repository link.
- Wrote development log entries describing my work.
- Reviewed the assignment documentation requirements.**:

**Challenges  Organizing my work into clear development log entries took some time.**:

**Solution  divided the documentation into separate entries and described the work completed in each session.**:

**Time spent 3 hours**:

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

**Total time spent on assignment**: [X hours]

**Most challenging part**:

**Most interesting learning**:

**What I would do differently next time**:

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

[I learned that multithreading allows a Java program to work with multiple threads. I learned how Runnable can define the work that a thread performs. The Thread.start() method is used to start a new thread. The Thread.join() method allows one thread to wait until another thread finishes. I also learned that Thread.sleep() pauses the current thread for a period of time and can be used to simulate work. The most interesting thing for me was seeing how threads can run independently and how their execution order can change..]

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

[The most challenging part of this assignment was understanding the Java code. At first, I did not fully understand how the scheduling simulation worked. I found it difficult to follow how the processes were executed. I needed to review the code carefully to understand each part. Running the program and checking the output helped me understand it better. After working through the code step by step, I became more confident in understanding the simulation.]

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

[I overcame the challenges by working on the assignment step by step. When I did not understand something, I asked for help and reviewed the instructions. I also checked the Java code to understand how the program worked. I used VS Code to compile and run the program. When I faced problems, I tried to understand the output and find a solution. This process helped me become more comfortable with Java and the assignment..]

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

[Multithreading can be used in many real-world applications. For example, a web browser can load a page while the user interacts with another part of the browser. A music player can play audio while the user browses a playlist. In mobile applications, background tasks can run without freezing the user interface. Games can also use different threads for tasks such as loading resources and handling input. I learned that multithreading can help applications stay responsive while handling multiple tasks.]

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

[A process is an independent program with its own memory space, while threads within the same process share memory. Threads are usually faster to create and can communicate more easily than separate processes. In this assignment, we used Java threads to simulate the execution of multiple processes. The Process class in SchedulerSimulation.java represents a simulated process, not a real operating system process. In the addProcessToQueue() method, new Thread(process) creates a real Java thread to run the simulated process.]

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

[In Round-Robin scheduling, a process that does not finish within its time quantum is added back to the ready queue. In my program, P9 had a burst time of 10856 ms and the time quantum was 5000 ms. P9 was re-queued two times before completing its execution. This allows other processes to use the CPU instead of waiting for one process to finish. Re-queuing helps make CPU scheduling fair for all processes..]

Example from my output:
``` P9 completed quantum 5000ms
Remaining time: 856ms
P9 yields CPU for context switch
P9 added to ready queue | Priority: 6 | Burst time: 10856ms
[Paste a relevant snippet from your program output here showing a process being re-queued]
```

**Explanation of example:**
[P9 needed 10856 ms to finish, but each time quantum was only 5000 ms. Therefore, P9 needed three CPU turns and was re-queued twice before finishing. This gave other processes a chance to use the CPU..]

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: [P1 enters this state when new Thread(process) creates its thread in addProcessToQueue().]

2. **Runnable**: [ becomes Runnable when the scheduler calls start() on its thread.]

3. **Running**: [P1 executes the code inside run() when the CPU schedules its thread.]

4. **Waiting**: [P1 enters Timed Waiting when Thread.sleep() pauses it temporarily, while the main thread can wait using join().]

5. **Terminated**: [P1 becomes Terminated when its run() method finishes.]
Runnable
## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): [Name of scenario]

**Description**:
[Example 1: Operating System CPU Scheduling

An operating system can use Round-Robin scheduling to share CPU time among multiple runnable programs. Each program or task plays the role of a process in our simulation. The time quantum is the maximum amount of CPU time assigned to a task during one turn. When that time expires, the operating system can perform a context switch and let another task run. This approach improves fairness and helps keep the system responsive.]

**Why Round-Robin works well here**:
[Fairness, responsiveness, predictability?]

### Example 2: [Name of application/scenario]

**Description**:
[Example 2: Web Server Request Handling

A web server could use a Round-Robin approach to distribute processing time among active requests. Each request handler plays the role of a process in our simulation. The time quantum represents the limited processing time given to each request before switching to another. A context switch occurs when execution moves from one request-handling task to another. This approach can help prevent one long request from delaying all the others.]

**Why Round-Robin works well here**:
[Round-Robin improves fairness by giving each task a turn and helps the system remain responsive.]

## Summary

**Key concepts I understood through these questions:**
1. The difference between threads and processes.
2. How Round-Robin scheduling uses a ready queue.
3. How threads move through their lifecycle states.

**Concepts I need to study more:**
1. Understanding thread synchronization and thread states.
2. Understanding context switching and CPU scheduling in more detail.

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
