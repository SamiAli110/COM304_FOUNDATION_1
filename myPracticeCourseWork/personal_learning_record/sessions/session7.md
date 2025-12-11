[Personal Learning Record](../../personal_learning_record/personal_learning_record.md) | [Session Notes](../sessions/README.md) 

# Session 7

## Topics covered
*What topics were covered in this session*
During session 9, we were introduced to the foundational concepts of computer networking and how devices communicate across local and global networks. The session focused on IP networking, routers, hosts, ports, and the idea of splitting networks into subnetworks. This provided the crucial knowledge needed to understand how data travels from one device to another across the internet.

We went on to explore the OSI networking model, which breaks communication into conceptual layers. The higher layers supported applications and user interaction, while the lower layers defined how data moved physically via cables, wireless signals, and routers. This layered learning helped explain why different technologies can coexist, switching from WIFI to Ethernet without changing how applications behave.
1. IP packets and datagrams
2. Routers vs hosts
3. Subnet masks and address calculations
4. TCP vs UDP in the Transport layer
5. Common port numbers like HTTP, SSH, DNS, and SMTP
6. Memory of how browsers send and receive web content
7. The difference between link-layer communication and routed communication and routed.
This was the first session where networking theory connected directly to practical work we previously did with Apache, the Raspberry Pi, and Linux networking utilities.


## Personal Notes and research following this session
*Which class sessions and personal research refers to technology in this proposal. Link to examples.*

To deepen my understanding, I explored more resources on networking, fundamentals, especially focusing on how IP addressing and subnetting work. I also looked into  how routers forward packets across networks and how devices use MAC addresses at the link layer and IP addresses at the network layer. 

I researched how IPv4 operates using packet switching, how each packet contains addressing information, and how routers collaborate to forward packets toward their destination. This helped reinforce why routers need routing tables and how local networks differ from wide area networks.

As this session emphasised the difference between reliable and unreliable protocols, I read more about connectionless vs connection-oriented communication. Understanding TCP's three-way handshake, packet ordering, and retransmissions helped explain why some applications as an example video calls, would prefer UDP instead.

The OS model can feel overwhelming at first, so I researched a simplified explanation that breaks down each layer with practical examples. This helped connect the physical signals to bits to frames to packets to segments to the application.  
https://www.ibm.com/think/topics/osi-model
[
](https://www.tutorialspoint.com/how-to-keep-your-browser-safe-on-work-and-home-networks-with-an-optional-chrome-vpn-layer)## Exercises and results
*What exercises did you complete? What results. Screen shots and notes*
Using an online subnet calculator, I calculated the number of available host addresses for the given subnet masks:
1. /30 network 4 addresses (2 usable)
2. /24 network 256 address (254 usable)
This helped me understand how ISPs allocate very small networks for router-to-router links, while home networks use larger address blocks.

Although not fully performed in class, the session introduced networking utilities such as Ping (test connectivity), ifconfig / ip a (view network interfaces), netstat or ss (view open ports), traceroute (trace packet path)
Exploring these tools on the Raspberry Pi helped visualise how networking is structured and monitored.

Understanding the transport layer, we examined packet structure, which showed IP addresses, port numbers, TCP flags (SYN, ACK, FIN), and DUP header simplicity. This directly helped me understand how applications like Apache use port 80 or 443, and why SSH uses port 22.

## Summary of learning
*What did you learn through these exercises*
This session significantly deepened my understanding of how computers communicate. I learned how data is broken into packets, how routers ensure delivery across different networks, and how the OSI model explains the interaction between hardware and software. TCP and UDP gave clarity to how applications choose transport mechanisms depending on performance or reliability requirements.

This session is also connected to earlier sessions, for example, Apache using ports 80/443, SSH using port 22, and how IP addressing determines network communication. By the end, I had a foundational understanding necessary for future work in cybersecurity, Linux server administration, and cloud networking.
