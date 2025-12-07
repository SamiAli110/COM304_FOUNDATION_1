[Personal Learning Record](../../personal_learning_record/personal_learning_record.md) | [Session Notes](../sessions/README.md) 

# Session 3

## Topics covered
*What topics were covered in this session*
During session 3 we expanded on understanding of computer architecture by looking beyond CPU and focusing how computers communicate with the outside world, using Raspberry Pi.
System on a Chip (SoC) architecture specifically Broadcom which is used in Raspberry Pi. The understanding of what SoC is and exactly how it integrates with CPU cores, GPU,memory controllers, USB controllers, Ethernet controllers and other peripherals into one chip. Introduction to general purpose input output pins on the Raspberry Pi. An overview of 40 pin GPIO header on how each pin can be configured as input, output, serial or clock. Introduction on how computers interact with physical hardware through port mapping and GPIO registers. Using Node Red to control GPIO pins visually. Introduction to WringPi, a C based library for controlling GPIO on the Raspberry Pi. These are all the topics which were covered. The foucs shifts from how cpu works internally to how the CPU interacts with the real world.



## Personal Notes and research following this session
*Which class sessions and personal research refers to technology in this proposal. Link to examples.*
During and after this session i explored GPIO systems which allow computers to control hardware externally, which supported me to completely understand the connection software, electrical signals, and physical components.

Regarding GPIO and Hardware Control i learned GPIO pins have the abilty to be used to send or receive digital signals (1s and 0s). These signals allow Raspberry Pi to control external hardware such as LEDs, sensors, buttons and moters. GPIO pins can simply be switched between input mode which is reading signals and output mode which is sending signals. Some pins also support advanced features like PWM, I2C,SPI AND UART communication.
[](https://www.raspberrypi.com/documentation/computers/raspberry-pi.html#gpio
)
During my researching adding onto what was covered in this session i found out how Node RED works as a low code environment which means instead of writing code directly, Node RED uses flows, which is a visual diagrams that represents how data moves and how devices exactly interact. This makes it more simple and helped me understand exactly how GPIO, I/O without having to use raw code.
[](https://nodered.org/docs/tutorials/)
   
I then moved on to the next stage of my research for this session which is how WiringPi provides low level control of Rapberry Pi GPIO using C code. This maps the Pi's GPIO pins to simple functions like digitalwrite() and digital() which reperesents read and write function. This helped me completley understand higher level programming languages communicate with hardware.
[
](https://github.com/WiringPi/WiringPi)

## Exercises and results
*What exercises did you complete. What results. Screen shots and notes*
Installed Node RED on the raspberry Pi followung module instructions, built a simple flow to blink LED using Node RED. Used WiringPi commands to toggle GPIO pins manually. Conncet external LEDs and resistors on a dreadbard to create a working circuit. I made a attempt on a traffic light system using Node RED following the guest lecture demo.

The results which i got from this was a successfull controlled GPIO using both Node RED and WiringPi. A built functioning LED circuit which responded to GPIO output signals. Understanding how input output elctrical signals correspond to software instructions.


## Summary of learning
*What did you learn through these exercises*
What i lernt from this session was that a system on a chip integrates multiple components into one processor. The raspberry Pi GPIO system allows software directly interact with physical hardware. A diffrence between input and output signals and how GPIO pins function in both modes. Tools such as Node Rode simplify hardware control compared to direct coding. How WiringPi provides low level access to GPIO through C code which connects software logic to electrical circuits. 
