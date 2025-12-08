[Personal Learning Record](../../personal_learning_record/personal_learning_record.md) | [Session Notes](../sessions/README.md) 

# Session 4

## Topics covered
*What topics were covered in this session*
*Which class sessions and personal research refers to technology in this proposal. Link to examples.*
During session 4, I explored the structure and purpose of different categories of computer programming languages and how they map the physical hardware of a computer system. This session built directly on the understanding of CPU architecture, binary operations, and logic gates from earlier sessions by showing how software instructions ultimately become electrical operations executed inside the processor.

We studied machine code, the lowest-level representation of a program made entirely of binary digits 0s and 1s. This form of code interacts directly with the CPU control unit and arithmetic logic unit. We then examined assembly language, which provides a human-readable representation of machine code through mnemonics like MOV, ADD, SUB, CMP, B, and JMP. Assembly language still communicates directly with hardware, but it is written in symbolic form so programmers can understand the logic of the program more clearly. 
Moving onto high-level languages such as C, Python, and Java, which abstract away low-level instructions to make programming more efficient and accessible. These languages rely on compilers like C or interpreters for languages like Python to simply translate source code into machine code. Then introduced to the concept of linkers and loaders, which prepare compiled programs by resolving external references, connecting libraries and loading executable files into memory. 

Finally, we used the CPUlator ARM simulator to see exactly how assembly instructions are executed on an ARM processor. We observed how instructions are fetched from memory, decoded by the CPU and executed by the ALU, and how registers and condition flags update after each operation. This session bridged the gap between theoretical CPU architecture and practical low-level programming.



Personal notes and research following this session 
After this session, I researched deeply into how programming languages interact with CPU hardware, focusing on the lifecycle of software instructions from high-level code down to machine execution.

I began dissecting and understanding the role of instruction set architectures such as ARM and x86. An ISA defines the exact binary patterns a CPU can execute, the structure of registers, supported instructions, and addressing modes. This helped me understand why machine code is processor-specific and why programs compiled for one architecture cannot run on another without recompilation.
[
](https://patpannuto.com/classes/2020/fall/cse141/cse141-fa20-ISA.pdf?)

I then looked closely at ARM assembly using CPUlator documentation. I researched how instructions interact with registers, for example, RO10 and RO12, the program counter PC, stack pointer SP, and the CPSR flag register. Understanding how operations modify flags such as Zero Z, Carry C and Negative N, and Overflow V helped me clarify how conditional branching works.
[
](https://cpulator.01xz.net/?sys=arm)

Next, I examined why C remains one of the most efficient high-level languages for system-level programming. C provides direct access to memory through pointers, allows manual control over data structures and compiles into highly optimised machine code. These characteristics explain why operating systems, device drivers, and embedded systems and commonly written in C.
[
](https://www.tutorialspoint.com/cprogramming/index.htm)

Lastly, I studied the difference between compiled languages and interpreted languages. Compiled languages like C undergo a multi-step process of compilation, linking, and loading before executing line by line using a virtual machine or interpreter, which makes them easier to test but slower at runtime.
[
](https://www.geeksforgeeks.org/compiler-design/difference-between-compiler-and-interpreter/)


## Exercises and results
*What exercises did you complete? What results. Screen shots and notes*

In this session, I engaged with the CPUlator ARM simulator to explore how the CPU processes instructions step by step. I then executed several assembled programs that performed arithmetic operations, register transfers and branching logic.

Register manipulation is something I also learned, and I created programs that loaded immediate values into registers (e.g., MOV R0, 5). By stepping through each instruction, I observed how the contents of registers changed and how each operation affected condition flags in the CPSR register.

I then went on to the next stage, which was conditional branching. I wrote small programs which used CMP to compare register values and then branched using conditional instructions like BEQ, BNE and BLT. This exercise helped me to understand how comparison operations affect the zero and negative flags and how the CPU decides whether to change the program counter.

Loop construction i i understood this by simply combining arithmetic and conditional branching. I created simple loops, for example, decrementing a counter until it reached zero. Watching the loop execute cycle by cycle clarified how the CPU repeatedly fetches and executes the same block of instructions until a condition changes.

I wrote a simple C program to understand and examine C compilation output. Once, I wrote a simple C program and generated assembly equivalents using the compiler's flag. This allowed me to compare high-level logic. (loops, conditionals, variables ) With the low-level instructions, they translate into. It then demonstrated clearly that compilers optimise code and how closely C maps to hardware operations. Overall, each exercise improved my ability to interpret processor activity purely from assembly instructions and register changes.

## Summary of learning
*What did you learn through these exercises*
Through the exercise and lesson notes, and independent research for this session, helped me deepen my knowledge of exactly how software is executed on a CPU at the lowest level. I learned how machine code is structured and how the assembly acts as an essential intermediary between human logic and binary hardware operations. This gave me a clearer picture of exactly how high-level languages are converted into machine code through compilation or interpretation, and how linkers and loaders tend to prepare programs for execution. For me to understand any of it from start to finish, basic to complex stuff, CPUlator gave me the practical insight into the fetch decode cycle and demonstrated how each instruction directly influences CPU registers, flags, and memory. This session as a whole played a crucial role in my understanding of the complete journey from source code to hardware-level execution.




