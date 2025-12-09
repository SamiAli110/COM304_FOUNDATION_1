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

In conclusion, I went on to review ARM assembly documentation to better understand how low-level instructions interact with hardware-controlled memory regions.
[
](https://developer.arm.com/documentation/dui0489/latest/)
## Exercises and results
*What exercises did you complete? What results. Screen shots and notes*
During the session, I was tasked to complete several exercises designed to connect OS theory with practical hardware-level programming. CPUlator seven-segment is what I used to write both assembly and C programs, which controlled a simulated seven-segment display. This required writing values to specific memory-mapped addresses and confirmed how low-level programs directly manipulate hardware states.
The results of this were successfully displayed numeric sequences, gained hands-on experience in interpreting memory addresses associated with I/O devices, and improved my understanding of memory-mapped I/O. 

I then went on to study interrupt behaviour in CPUlator. I did this by going step by step through examples which show how interrupts temporarily stop execution and redirect the CPU to a handler. Where then were the results of this? I learned how flags and saved program counters guarantee safe return to normal execution, and observed the registers' state on how it changed during interrupts.

Rapberry Pi assembly & C i anothor exercise which executed by learning Linux which exposes GPIO through file system paths and how C programs has access to them. The results of this was i understood how user space programs interact with Kernal manged hardware and practeced compliling and running low level programs uner linux.


## Summary of learning
*What did you learn through these exercises*
From this entire session i mannaged to gain a more comprehensive view of how opreating systems manage hardware resources and enable safe, efficent execution of programs. I now have to an extent masterd the distinction between kernel space, user space, how interupts give hardware the abiltiy to signal the CPU, and how virtual memory provides isolation and protection.

Working with CPUlator helped me understand along with advancing my knowlidge on how to exactly write both ARM Assembly and C programs that interact directly with hardware thorugh memory mapped I/O. Now connecting this to the Raspberry Pi environment it suppurted me to have a vision of how real world embedded system rely on OS mechanisms and low level programming. This session not only helped me but solidified the link between the thrortical structure of opreating systems and practicl behaviour of hardware level code.
