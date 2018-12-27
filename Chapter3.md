# Chapter 3: Hardware and Software

Computer hardware includes the physical components of a computer, such as the central processing unit, monitor, keyboard,
computer data storage, graphic card, sound card, speakers and motherboard. Software is instructions that can be stored and run
by hardware. Software is all of the computer programs, or code, running on this machine. Software can be anything from apps
and games to webpages and data science software. 

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

<p align="center">
https://en.wikipedia.org/wiki/Operating_system
</p>

The CPU receives simple commands that tell it which circuit to use to do a specific job. The binary commands are stored in
memory and the CPU fetches and executes them in sequence one after the other. This sequence of commands is in fact the very
simple computer program.

Binary code is the most basic form of software and it controls all the hardware of a computer. These days nobody writes
software in binary, it would take forever. Today, the software we write looks more like this, C/C++, Python, Java.

Software tells the CPU what to do, but when you’re listening to music and browsing the web and chatting with a friend, your
computer is running multiple pieces of software all at once. So how do all of these programs get on the computer in the first
place, and how can the CPU run them all at once? To find out, we have to take a look at operating system.

### ![#ff00ff](https://placehold.it/15/ff00ff/000000?text=+) `Operating System`

An `operating system` is system software that manages all the hardware and other software on a computer. The operating system,
also known as an “OS”, interfaces with the computer’s hardware and provides services that applications can use.

<p align="center">
   Figure 3: Four common Operating System
</p>

<p align="center">
  <img src="https://github.com/XinYangSAU/CSCI1101-Intro-to-Computing/blob/master/Images/os.png" alt="os"/>
</p>

<p align="center">
https://www.howtogeek.com/361572/what-is-an-operating-system/
</p>

When you think your computer is running many programs at once, in reality, its the operating system that’s quickly switching
between programs, sharing that CPU for fractions of a second. 

### ![#6699ff](https://placehold.it/15/6699ff/000000?text=+) `What Operating System do?`

### 1. Starts running when the computer "boots up"
### 2. Manager/supervisor
   Starting/stopping programs
   Manages RAM, persistent storage, and other shared resources between programs
### 3. Can run multiple programs at once ("sandboxing")
### 4. Allows a computer to change over time (updates)
### 5. Other responsibilities:
   File system
   Manages windows
   Some basic programs


