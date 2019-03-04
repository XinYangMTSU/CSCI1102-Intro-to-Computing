# Chapter 1: Introduction to computer architecture

Computers are everywhere! They’re on our desktops, in our homes, in people’s pockets, or people have them on their wrists. 
But while most of us use this revolutionary technology daily, we don’t often ask, what makes a computer a computer? 
And how does it even work?

In this chapter, you’ll learn how computers work:

![#f03c15](https://placehold.it/15/f03c15/000000?text=+) `1. Different parts of the computer that input, output, store and process all information.`

![#1589F0](https://placehold.it/15/1589F0/000000?text=+) `2. How computers do everything from simple math to simulating the entire virtual worlds.`

## What makes a computer a computer?

It would need to take `input`, `store` information, `process` it, and then `output` the results. 
This might sound simple, but `these four things are common to all computers`. And that’s what makes a computer a computer.

<p align="center">
   Figure 1: Four things are common to all computers
</p>

<p align="center">
  <img src="https://github.com/XinYangSAU/CSCI1101-Intro-to-Computing/blob/master/Images/f2.png" alt="common"/>
</p>

<p align="center">
   https://www.khanacademy.org/computing/computer-science/how-computers-work2
</p>

The earliest computers were made out of wood and metal with mechanical levers and gears. By the 20th century though, 
computers started using electrical components. These early computers were really large and really slow. A computer 
the size of a room might take hours just to do a basic math problem.

<p align="center">
   Figure 2: Timeline of Computers
</p>

<p align="center">
  <img src="https://github.com/XinYangSAU/CSCI1101-Intro-to-Computing/blob/master/Images/t.png" alt="common"/>
</p>

<p align="center">
   Figure 3: ENIAC
</p>

<p align="center">
  <img src="https://github.com/XinYangSAU/CSCI1101-Intro-to-Computing/blob/master/Images/Eniac.jpg" alt="common"/>
</p>

<p align="center">
    https://en.wikipedia.org/wiki/ENIAC
</p>

ENIAC (Electronic Numerical Integrator and Computer) was amongst the earliest electronic general-purpose computers made. 
The ENIAC computing system was built by John Mauchly and J. Presper Eckert at the Moore School of Electrical Engineering of
the University of Pennsylvania

Computers started out as basic calculators, which were only manipulating numbers back then. But now we can use them to talk to
each other, play games, control robots, and do any fancy stuff that you could probably imagine.

`Modern computers look nothing like those old machines, but they still do the same four things.`


1.Input Device:
---------------
First, we’ll talk about input. You can tell a computer what to do with the `keyboard`. You can tell them what to do with the
`mouse`, the `microphone`, the `camera`. And now if you’re wearing a computer on your wrist, it might listen to your heartbeat. And a `touchscreen` can actually sense your finger and it takes that as input on what it’s doing.

* Keyboard
* Mouse
* Scanner
* Web Cam
* Touchscreen

All these different inputs give the computer information, which is then stored in memory. A computer’s processor takes
information for memory it manipulates it or changes it using the algorithm, which is just a series of commands, and then it
sends the process information back to be stored in memory again. This continues until the processed information is ready to be
output.

2.Storage/Memory:
-----------------
Computers use two types of storage: `Primary storage` and `Secondary storage`. `Memory` is also known as primary storage,
primary memory, main storage, main memory, and `RAM` (Random Access Memory); all these terms are used interchangeably by
people in computer circles. The CPU interacts closely with primary storage, or main memory, referring to it for both
instructions and data. 

* Primary Memory
  * RAM (Main Memory)
  * ROM

* Secondary Memory
  * Hard Disk
  * Floppy Drive
  * CD

A computer's `Main Memory` holds data only temporarily, at the time the computer is executing a program. 
A computer's `Secondary storage` holds permanent data on some external magnetic or optical medium. 

3.Processor/CPU:
----------------

* CPU (Central Processing Unit)
   * Control Unit
   * Arithmetic/Logic Unit

The control unit of the CPU directs the entire computer system to carry out or execute, stored program instructions. Like an
orchestra leader, the control unit does not execute program instructions; rather, it directs other parts of the system to do
so. The control unit must communicate with both the arithmetic/logic unit and memory. 

The arithmetic/logic unit (ALU) executes all arithmetic and logical operations. ALU can perform four kinds of arithmetic
operations: addition, subtraction, multiplication, and division.


4.Output Device:
----------------

* Printer
* Monitor
* Speaker
* Earphone
* Projector

A computer display can show texts, photos, videos or interactive games, even virtual reality. The output of a computer may
even include signals to control a robot. And when computers connect over the internet, the output from one computer becomes
the input to another and vice versa.

All computers do the same 4 things. Each of these things is done by different part of the computer. There are input devices
that take input from the outside world and convert it into binary information. There’s the memory to store this information.
There’s a central processing unit, or CPU, where all the calculations are done. And finally, there are output devices that
take information and convert it into the physical output.

The CPU is a silicon chip that is the ‘brain’ of a computer system. It executes program instructions and data and controls all
the devices within the machine.

<p align="center">
   Figure 4: A Machine Cycle
</p>

<p align="center">
  <img src="https://github.com/XinYangSAU/CSCI1101-Intro-to-Computing/blob/master/Images/cpu.jpg" alt="common"/>
  https://turbofuture.com/computers/What-are-the-basic-functions-of-a-CPU
</p>

Before an instruction can be executed, program instructions and data must be placed into memory from an input device or a
secondary storage device. Once the necessary data and instruction are in memory, the central processing unit performs the
following four steps for each instruction: 

Step 1. 
-------
The control unit fetches (gets) the instruction from memory. 

Step 2.
-------
The control unit decodes the instruction (decides what it means) and directs that the necessary data be moved from memory to the arithmetic/logic unit. These first two steps together are called instruction time.

Step 3.
------- 
The arithmetic/logic unit executes the arithmetic or logical instruction. That is, the ALU is given control and performs the actual operation on the data. 

Step 4.
-------
The arithmetic/logic unit stores the result of this operation in memory or in a register. Steps 3 and 4 together are called execution time. 

The control unit eventually directs memory to release the result to an output device or a secondary storage device. The
combination of instruction time and execution time is called the machine cycle. Figure 4 shows an instruction going through
the machine cycle.

<p align="center">
   Figure 5: Inside The Computer
</p>

<p align="center">
  <img src="https://github.com/XinYangSAU/CSCI1101-Intro-to-Computing/blob/master/Images/cpu.gif" alt="common"/>
  https://homepage.cs.uri.edu/faculty/wolfe/book/Readings/Reading04.htm
</p>

When you press a key on your keyboard, let’s say the letter B, the keyboard converts the letter to a number. That number is
sent as binary. ones and zeros, into the computer. Starting from this number, the CPU calculates how to display the letter B
pixel-by-pixel. The CPU requests step-by-step instructions from memory, which tell it how to draw the letter B. The CPU runs
these instructions and stores the results as pixels in memory. Finally, this pixel information is sent in binary to the
screen. The screen is an output device, which converts the binary signals into the tiny lights and colors that make up what
you see. This all happens so quickly it feels instantaneous, but to display each letter, a computer runs thousands of
instructions, starting from the moment your finger presses the keyboard.

https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
https://online.stanford.edu/courses/soe-ycscs101-sp-computer-science-101
