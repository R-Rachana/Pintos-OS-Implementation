# Operating Systems Project: Implementing Pintos

![Project Screenshot / Architecture Diagram]
*(A great image here would be an architecture diagram of a kernel, or a screenshot of your terminal showing your new scheduler working.)*

## 1. Project Overview

This was a foundational, multi-phase group project for my graduate-level Operating Systems course. The goal was to take "Pintos," a simple, instructional operating system for x86 architecture, and implement core, complex functionalities from scratch in C.

## 2. The Problem & Goal

The base Pintos system lacks essential features like thread scheduling, user programs, and a file system. Our task was to build these critical components, gaining a deep, practical understanding of core OS concepts like process management, memory management, and system calls.

## 3. Tech Stack

* **Language:** C
* **Core System:** Pintos OS
* **Architecture:** x86
* **Tools:** GDB, QEMU

## 4. Project Status: Case Study (Academic Policy)

This repository serves as a **case study** to document the project's architecture and my personal contributions. **The source code for this project is kept private** to comply with the University at Buffalo's academic integrity policies for this course.

## 5. My Role & Contributions

As a member of a [X-person, e.g., 3-person] team, I was an active contributor across all project phases. My primary focus and most significant contributions were on **Project 1: Threads & Scheduling**.

Specifically, I:
* **Implemented Priority Scheduling:** Modified the Pintos thread scheduler to select the highest-priority thread to run, rather than a simple round-robin.
* **Solved Priority Inversion:** Implemented priority donation (using locks and semaphores) to solve the classic priority inversion problem, where a high-priority thread is blocked by a lower-priority one.
* **Built the MLFQ Scheduler:** Designed and implemented the Multi-Level Feedback Queue (MLFQ) scheduler from scratch to improve system responsiveness and fairness.
* **Ensured System Stability:** Worked with my team to rigorously debug complex concurrency issues, memory leaks, and race conditions to ensure our kernel was stable.

## 6. Challenges & What I Learned

This was one of the most challenging projects of my academic career. Debugging race conditions in a kernel with minimal tools taught me the importance of meticulous design and synchronization. I gained a fundamental understanding of how modern operating systems manage concurrency, scheduling, and resource allocation.
