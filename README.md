## Operating System

These must-do questions should be answered after studying these subjects  
If you don't have much time left for interviews, then you can directly look at them
<h3>MUST-DO Questions for Interviews Operating System </h3>

<details>
<summary style="font-size:1.15rem;">Operating System </summary>

- What is the main purpose of an operating system? Discuss different types.
- What is a socket, kernel and monolithic kernel?
- What is the difference between process and program and thread? Different types of process.
- Define virtual memory, thrashing, and threads.
- What is RAID? Different types.
- What is a deadlock? Different conditions to achieve a deadlock.
- What is fragmentation? Types of fragmentation.
- What is spooling?
- What is semaphore and mutex (Differences might be asked)? Define Binary semaphore.
- Belady’s Anomaly
- Starving and Aging in OS
- Why does trashing occur?
- What is paging and why do we need it?
- Demand Paging, Segmentation
- Real-Time Operating System, types of RTOS.
- Difference between main memory and secondary memory.
- Dynamic Binding
- FCFS Scheduling
- SJF Scheduling
- SRTF Scheduling
- LRTF Scheduling
- Priority Scheduling
- Round Robin Scheduling
- Producer Consumer Problem
- Banker’s Algorithm
- Explain Cache
- Diff between direct mapping and associative mapping
- Diff between multitasking and multiprocessing
</details>
  <h3> Complete Operating System Course </h3>

<details>
  <summary style="font-size:1.15rem;">Overview</summary>

- [Quick Notes to Follow](https://mega.nz/file/pEpRUIQQ#ArZTGmmvMpygGuoOL6rokFesY7IJVTDJCPUQ_VsLR4U)
- [What is an Operating System](https://www.scaler.com/topics/operating-system/what-is-operating-system/)
- [Features of Operating System](https://www.interviewbit.com/blog/features-of-operating-system/)  
- Services provided by an Operating System
- [Types of Os](https://www.geeksforgeeks.org/types-of-operating-systems/)
  - Batched OS
  - Time Sharing OS
  - Distributed OS
  - Network OS
  - Real-Time OS
- [RAM vs ROM](https://www.guru99.com/difference-between-rom-ram.html)
- [SRAM & DRAM](https://www.guru99.com/sram-vs-dram-difference.html)
- [PROM, EPROM & EEROM](https://pediaa.com/what-is-the-difference-between-prom-eprom-and-eeprom/)
- [Virtualisation vs Containerisation](https://www.tutorialspoint.com/difference-between-virtualization-and-containerization)
- [BIOS vs UEFI](https://www.howtogeek.com/56958/htg-explains-how-uefi-will-replace-the-bios/)
- [MBR vs GPT](https://www.howtogeek.com/193669/whats-the-difference-between-gpt-and-mbr-when-partitioning-a-drive/)
- Important Terms to Know
  - Compiler
  - Loader
  - Assembler
  - Interpreter
  - System Calls
  - Application Programming Interface
  - Kernel
  - Shell
  - JVM
  - [Booting](https://www.scaler.com/topics/operating-system/what-is-booting/)
- [Multi-programming, Multi-processing, Multi-tasking & Multi-threading](https://www.geeksforgeeks.org/difference-between-multitasking-multithreading-and-multiprocessing/)
- [Monolothic architecture vs MicroKernel arch](https://stackoverflow.com/questions/4537850/what-is-difference-between-monolithic-and-micro-kernel)
- [Why Windows kernel is more monolithic & not microkernel?](https://micksmix.wordpress.com/2011/02/20/does-windows-have-a-microkernel-or-monolithic-kernel/)
- [What happens when we turn on our computer?](https://www.geeksforgeeks.org/what-happens-when-we-turn-on-computer/)
</details>




<details>
  <summary style="font-size:1.15rem;">Process Concept</summary>

- [Process vs Program](https://www.geeksforgeeks.org/difference-between-program-and-process/)
- [Different State of process](https://www.geeksforgeeks.org/states-of-a-process-in-operating-systems/)
- Types of Process?
- [PCB structure in detail](https://www.geeksforgeeks.org/process-table-and-process-control-block-pcb/)
- [How does a process look like in memory?](https://www.tutorialspoint.com/how-does-a-process-look-like-in-memory)
- [Process vs Threads](https://www.geeksforgeeks.org/difference-between-process-and-thread/)
- Process Scheduling
  - [Introduction](https://www.tutorialspoint.com/operating_system/os_process_scheduling.htm)
  - [Inter Process Communication (IPS) in OS](https://www.scaler.com/topics/operating-system/inter-process-communication-in-os/)
  - Scheduling Queue
    - Job Queue
    - Ready Queue
    - Device Queue
  - Scheduler
    - Short-term Scheduler
    - Medium-term Scheduler
    - Long-term Scheduler
- [CPU Bound Process vs I/O Bound Process](https://stackoverflow.com/questions/868568/what-do-the-terms-cpu-bound-and-i-o-bound-mean)
  The best Performance system is which have a combination of CPU-bound and I/O bound process
- [What is Context Switch?](https://www.tutorialspoint.com/what-is-context-switching-in-operating-system)
- IPC
  - [Introduction](https://www.geeksforgeeks.org/inter-process-communication-ipc/)
  - by Shared Memory
  - by Message Passing
- [Define Pipe](https://www.tutorialspoint.com/inter_process_communication/inter_process_communication_pipes.htm)
- [Maximum number of Zombie processes a system can handle?](https://www.geeksforgeeks.org/maximum-number-zombie-process-system-can-handle/)
</details>



<details>
  <summary style="font-size:1.15rem;">Thread Concepts</summary>
  
- [What is a Thread?](https://www.studytonight.com/operating-system/multithreading)
- [Benefits of Multi-threading?](https://www.geeksforgeeks.org/benefits-of-multithreading-in-operating-system/)
- [Example of Multi-threading](https://www.quora.com/What-are-some-best-examples-of-multithreaded-applications)
- [Models](https://www.studytonight.com/operating-system/multithreading)
  - Many to One
  - One to One
  - Many to Many
  - Best Model??
- [Optimal number of threads required for a process?](https://stackoverflow.com/questions/1718465/optimal-number-of-threads-per-core)
- [Effect of Multiple cores on Multi-threading](https://blogs.grammatech.com/multi-core-processors-headache-for-multithreaded-code)
- Thread vs Process
- [Why C++ static variables are dangerous in real life OS?](https://stackoverflow.com/questions/7026507/why-are-static-variables-considered-evil)
</details>


<details>
  <summary style="font-size:1.15rem;">Process Scheduling</summary>

- Why do we need it?
- CPU Burst Cycle
- CPU Scheduler
  - Pre-Emptive Scheduling
  - Non PreEmptive
  - Advantages/Disadvantages
- Dispatch
  - Role of Dispatcher
  - Dispatch Latency
- Scheduling Criteria
  - CPU Utilisation
  - Throughput
  - TAT [Turn around Time]
  - Waiting Time
  - Response Time
- Scheduling Algo
  - FCFS
  - SJFC
  - Priority-based
  - Round-Robin
  - MLQS
  - MLFQS
  - Which algo is used in real-world OS
- IMP terms to know
  - Starvation
  - Ageing
- How to prevent Starvation?
</details>

<details>
  <summary style="font-size:1.15rem;">Synchronisation</summary>

- [Why Process Coordinator/Sync is needed?](https://www.studytonight.com/operating-system/process-synchronization)
  - Data Inconsistency
  - Race Condition
- [Physical Address Space vs Logical Address Space](https://www.geeksforgeeks.org/logical-and-physical-address-in-operating-system/)
- Imp terms to know
  - [Mutual Exclusion](https://www.geeksforgeeks.org/mutual-exclusion-in-synchronization/)
  - [Critical Section](https://www.geeksforgeeks.org/g-fact-70/)
- Critical Section Problem, Peterson Solution
  - [Follow YouTube video (knowledge gate)](https://www.youtube.com/watch?v=YwqexcfbucE&list=PLmXKhU9FNesSFvj6gASuWmQd23Ul5omtD)
- Why pre-emptive kernel is better than non pre-emptive kernel?
- Semaphore
  - Binary Semaphore/Mutex Locks
  - Counting Semaphore
- Imp terms to know
  - Busy Waiting
  - Spin Lock
- Example of busy waiting & spin lock
- [How to implement Binary Semaphore in real-world coding](https://www.geeksforgeeks.org/semaphores-in-process-synchronization/)
- What is Deadlock & Starvation?
- Bounded Buffer, Reader-Writer Problem & Dining Philosopher Problem
  - [Follow YouTube video (knowledge gate)](https://www.youtube.com/watch?v=YwqexcfbucE&list=PLmXKhU9FNesSFvj6gASuWmQd23Ul5omtD)
  </details>


<details>
  <summary style="font-size:1.15rem;">Deadlocks</summary>

- [What is Deadlock?](https://www.cs.rpi.edu/academics/courses/fall04/os/c10/)
- [Effects of Deadlock?](https://stackoverflow.com/questions/41204406/what-is-effect-of-deadlock-on-other-processes-which-are-not-involve-in-deadlock/41713812)
- Necessary Conditions
  - Mutual Exclusion
  - Hold & Wait
  - No Pre-emption
  - Circular Wait
- [Methods for Deadlock handling](https://www.scaler.com/topics/dbms/deadlock-in-dbms/)
  - Prevention or Avoidance
  - Detection or Recovery
    - Banker's Algo
    - Ostrich Algo
    - Resource Per-emotion
  - Ignorance
  </details>



<details>
  <summary style="font-size:1.15rem;">Memory-Management</summary>
  
  - Imp Points
    - CPU can directly access Registers and Main Memory
    - Protection of Memory space is handled by Hardware
    - OS loads Base and Limit registers
    - Mapping from Logical to Physical address is done by MMU[Memory Management Unit]
    - OS memory is categorised into
      - for the resident of OS
      - user processes
  - Logical vs. Physical address space
  - What is Swapping
    - Ex-priority-based Scheduling
    - Done by Dispatcher
    - [Context Switch](https://www.scaler.com/topics/operating-system/context-switching-in-os/) time in swapping is very high
    - OS can't swap process that has pending input/output
  - Imp topics to cover
    - [Follow YouTube videos](https://www.youtube.com/watch?v=YwqexcfbucE&list=PLmXKhU9FNesSFvj6gASuWmQd23Ul5omtD)
    - Memory Allocation
      - Contiguous Memory Allocation
        - Address Translation: Base and limit Register
        - Fixed Partitioning
        - Variable Partitioning
        - Variable Partitioning
        - dynamic storage allocation problem
          - Best Fit
          - Worst Fit
          - First Fit
        - Internal Fragmentation
        - External Fragmentation
          - Compaction
          - Non-Contiguous Allocation
            - Paging
            - Segmentation
      - Paging
        - Page table
        - Page no
        - Page Offset
        - Page Table Limit Register (PTLR)
      - Segmentation
        - Segment Table
        - Base Register
        - Limit Register
  - [Why paging increases the context-switch time?](https://gateoverflow.in/178062/paging-os-galvin-book-page-no-332)
  - [Page vs Frame?](https://practice.geeksforgeeks.org/problems/page-and-frames)
  - [What is TLB miss?](https://stackoverflow.com/questions/37825859/cache-miss-a-tlb-miss-and-page-fault)
</details>


<details>
  <summary style="font-size:1.15rem;">Virtual Memory</summary>

- Goal of mem. Mgmt
  - To keep multiple processes in memory to allow multi-programming
- [Virtual Memory](https://www.tutorialspoint.com/operating_system/os_virtual_memory.htm)
  - What?
  - Why?
  - Where it is physically located?
  - How it is implemented?
    - Demand Paging
    - Strategy to only load pages when they are needed
    - Paging + Swapping
  - Advantages
    - user can write programs for extremely large virtual address space
    - [CPU utilisation & throughput] increases & [Response Time, Turn around time, TAT] remains same
    - Less I/O would be needed to load or swap user programs into memory, so each user program would run faster
    - Degree of Multiprogramming increases
    - allows file and memory to be shared by 2 or more processes through page sharing
  - If it is used carefully, it can decrease performance
- [Demand Paging](https://www.youtube.com/watch?v=Agi0u5Png_U)
  - paging + swapping
  - Lazy Swapper
  - pager
  - page fault
- [Pure Demand Paging](https://practice.geeksforgeeks.org/problems/what-is-pure-demand-paging)
- Swap Space
  - Section of the hard disk used for implementing Virtual Mem. in swap
- What is Page Fault?
- Page Replacement Algo
  - FIFO
  - Optimal Page Replacement
  - LRU
- What is the Frame Rate
- [Most Asked Questions (Thrashing)](https://practice.geeksforgeeks.org/problems/thrashing-in-os)
  - What?
    - Low CPU Utilisation->Degree of Multiprogramming increases->More Page Fault->Cycle Continues->Thrashing occurs->Page fault occurs tremendously->CPU utilisation decrease sharply
  - Cause of Thrashing?
  - Solution to Thrashing?
    - use priority based replacement algo
    - allocate the exact number of frames that are actually required
- Can we replace physical memory i.e., RAM with virtual memory?
- Is the performance of virtual memory and physical memory the same?
</details>


<details>
  <summary style="font-size:1.15rem;">Storage Management</summary>
  (optional)
  
  - [Resource 1](https://www.slideshare.net/DeepikaT13/storage-management-in-operating-system) 
  - [Resource 2](https://www.slideshare.net/arjunk007/secondary-storage-structureoperating-system-concepts)

</details>


<details>
  <summary><span style="font-size:1.15rem;"> <a href="https://www.os-book.com/OS9/slide-dir/index.html">For College Exams</a></span></summary>
</details>
<br />




