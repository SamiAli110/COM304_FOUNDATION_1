[Personal Learning Record](../../personal_learning_record/personal_learning_record.md) | [Session Notes](../sessions/README.md) 

# Session 6

## Topics covered
*What topics were covered in this session*

Operating systems were explored, the basic structure and its components of modern systems, focusing on how the OS interacts with hardware and software to manage resources. This includes the kernel, processes, memory management, file systems, and system calls. The OS serves as a bridge between the hardware and applications, enabling efficient resource allocation, security, and multitasking.

Apache web server installation was also introduced in this session, like Apache 2. We looked at exactly how to install and configure Apache on a Raspberry Pi, as well as how to create a basic web server to serve static content. Apache is one of the most widely used web servers, and learning to set it up provides a foundation for understanding how web hosting and client-server communication work.



## Personal Notes and research following this session
*Which class sessions and personal research refers to technology in this proposal. Link to examples.*

This session builds on prior learning about computer architecture and the fundamental functions of an operating system. The concepts of processes and system calls are directly related to the work we've done on assembly language and C programming. The installation and configuration of APACHE ties into our understanding of how the operating system manages services and resources.
[https://raspberrypi-guide.github.io/networking/apache-web-server]

Operating system concepts of the structure and role of the kernel in managing hardware and system resources for understanding system-level programming and how different applications interact with the OS. We explored process management, file systems, and memory management, which provide the foundation for multitasking and security in modern OSes.
[https://www.javatpoint.com/operating-system-structure]

Research on web servers is something I furthered my knowledge by going into Apache. I explored several online resources that provide deeper insights into web server management and configuration, including virtual hosts, SSL configuration, and optimizing server performance.
[
](https://www.hostinger.com/tutorials/what-is-apache)
## Exercises and results
*What exercises did you complete. What results. Screen shots and notes*

I installed Apache2 on the Raspberry Pi using the commands
sudo apt update
sudo apt install apache2
Once the installation was complete, I then verified that the server was running, which was straightforward
systemct1 status apache 2

## Summary of learning
*What did you learn through these exercises*
Through this session, I gained a much deeper understanding of how full operating systems are structured beyond the CPU-level concepts that I learned in earlier sessions. I advanced my knowledge by understanding how Linux manages processes, services, and file systems, and how software such as Apache relies on the OS to handle hardware, networking, and background services. The hands-on setup of Apache and Raspberry Pi strengthened my skills with Linux commands, service management, ports, and web technology. I now fully understand how real servers operate at a system level and how operating systems provide the foundation for all complex computing tasks.
