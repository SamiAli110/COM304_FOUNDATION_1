[Personal Learning Record](../../personal_learning_record/personal_learning_record.md) | [Session Notes](../sessions/README.md) 

# Session 5

## Topics covered
*What topics were covered in this session*
Moving on to the next session, I expanded on my understanding of how modern operating systems function internally and how low-level programs interact with hardware. This session connected the processor-level concept from earlier sessions with the structure of full operating systems, such as Linux. 

We began by examining the core components of an operating system, including the Kernel, which is responsible for memory management, process scheduling, handling interrupts, managing system calls, and controlling hardware. User space vs Kernel space: how modern systems isolate application code from critical system operations for stability as well as security. Virtual memory is how the OS uses paging, segmentation, and address translation to give each program its very own secure memory space. Scheduler mechanisms are used by the kernel to allocate CPU time fairly and efficiently across multiple processes.

After this part, I continued practising ARM assembly and C programming using CPUlator, focusing on low-level control of IO devices such as seven-segment displays. This allowed us to link OS level concepts, such as interrupts and memory operations, to actual assembly instructions and C functions interacting with hardware. Then, to overall conclude, I was introduced to using assembly and C on a real Raspberry Pi, reinforcing how low-level code interacts with GPIO, along with hardware which drives under Linux.


## Personal Notes and research following this session
*Which class sessions and personal research refers to technology in this proposal? Link to examples.*
After the last session, I conducted additional research to deepen my understanding of exactly how operating systems function at a low level, practically how the kernel manages hardware resources. I explored how interrupts exactly work, understanding what they allow hardware devices like keyboards, timers, and network cards which notify the CPU of events without constant polling. When an interrupt occurs, the CPU saves its current state and jumps to an interrupt service routine, which also stands for ISR. This research made me understand how real-time responsiveness works in modern systems.
[
](https://oer.gitlab.io/OS/Operating-Systems-Interrupts.pdf?)

I then continued to research virtual memory and address translation. So I started by focusing on how page tables map virtual addresses to physical RAM is limited, and how the OS prevents memory corruption between processes. To connect these OS concepts straight back to programming, I dived deeper into memory-mapped IO, which explains how peripherals like seven-segment displays and GPIO pins appear as special memory addresses that assembly and C programs can read or write as well.
[
](https://www.geeksforgeeks.org/virtual-memory-in-operating-system/)
[
](https://users.ece.cmu.edu/~jhoe/course/ece447/S10handouts-jose/L20.pdf?)
## Exercises and results
*What exercises did you complete. What results. Screen shots and notes*



## Summary of learning
*What did you learn through these exercises*
