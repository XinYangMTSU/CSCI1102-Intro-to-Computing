# Chapter 3: Hardware and Software

When you look inside a computing device,you see a bunch of circuits, chips, wires, speakers, plugs, and all sorts of other
stuff. This is the hardware. But what you don’t see is the software. Software is all of the computer programs, or code,
running on this machine. Software can be anything from apps and games to webpages and data science software. 

### ![#f03c15](https://placehold.it/15/f03c15/000000?text=+) `Hardware - Physical components that make up a computer system.`

### ![#1589F0](https://placehold.it/15/1589F0/000000?text=+) `Software - Computer programs and related data that provide the instructions for telling computer hardware what to do and how to do it.`

<p align="center">
   Figure 1: Standard hardware components
</p>

<p align="center">
  <img src="https://github.com/XinYangSAU/CSCI1101-Intro-to-Computing/blob/master/Images/hd.png" alt="hardware"/>
</p>

How do the hardware and the software interact with one another? Let’s start at looking at a computers’s central processing
unit, or CPU. The CPU is the master chip that controls all the other parts of the computer. A CPU needs to do different
things, so inside it has smaller, simpler parts that handle specific tasks. It has circuits to do simple math and logic, it
has other circuits to send and receive information to and from different parts of the computer. The real magic of the CPU is
how it knows which circuits to use and when to use them.

<p align="center">
   Figure 2: Relationship between Hardware and Software
</p>

<p align="center">
  <img src="https://github.com/XinYangSAU/CSCI1101-Intro-to-Computing/blob/master/Images/hs.png" alt="hardware"/>
</p>

The CPU receives simple commands that tell it which circuit to use to do a specific job. The binary commands are stored in
memory and the CPU fetches and executes them in sequence one after the other. This sequence of commands is in fact the very
simple computer program.

Binary code is the most basic form of software and it controls all the hardware of a computer. These days nobody writes
software in binary, it would take forever. Today, the software we write looks more like this, C/C++, Python, Java.

Software tells the CPU what to do, but when you’re listening to music and browsing the web and chatting with a friend, your
computer is running multiple pieces of software all at once. So how do all of these programs get on the computer in the first
place, and how can the CPU run them all at once? To find out, we have to take a look at operating system.

The operating system of a computer is the master program that manages how software gets to use the hardware of the computer.
The operating system is a program with special abilities that let it control the other software on the computer. 

When you think your computer is running many programs at once, in reality, its the operating system that’s quickly switching
between programs, sharing that CPU for fractions of a second. 
