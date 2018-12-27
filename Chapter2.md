# Chapter 2: Binary & Data

You may have heard that computers work on ones and zeros. But almost nobody today actually deal directly with these ones and zeros, but ones and zeros do play a big role in how computers work on the inside.

<p align="center">
   Figure 1: Binary
</p>

<p align="center">
  <img height="300" width="400" src="https://github.com/XinYangSAU/CSCI1101-Intro-to-Computing/blob/master/Images/binary.jpg" alt="Binary"/>
</p>

Inside a computer are electric wires and circuits and carry all the information in a computer. 

<p align="center">
   Figure 2: Wire & Circuits
</p>

<p align="center">
  <img height="300" width="400" src="https://github.com/XinYangSAU/CSCI1101-Intro-to-Computing/blob/master/Images/wc.png" alt="Binary"/>
</p>

How do you store or represent information using electricity? Well, if you have a single wire with electricity flowing through
it. The signal can either be on or off. That’s not a lot of choices. but it’s a really important start. With one wire, you can
represent a ‘yes’ or a ‘no’. true or false, a one or a zero. or anything else with only two options. This on/off state of a
single wire is called a bit. 

## A bit (short for binary digit) is the smallest unit of information the computer can store. A bit has a single binary value, either 0 or 1.

<p align="center">
   Figure 3: Bit: Zero and One
</p>

<p align="center">
  <img height="400" width="400" src="https://github.com/XinYangSAU/CSCI1101-Intro-to-Computing/blob/master/Images/b2.png" alt="Binary"/>
</p>

<p align="center">
   https://delightlylinux.wordpress.com/2014/09/05/binary-lesson-7-bits-and-bytes/
</p>

If you use more wires, you get more bits. More ones and zeros with more bits. You can represent more complex information. But
to understand that, we need to learn about something called about the binary number system.

In the decimal number system, we have 10 digits from zero to nine. and that’s how we’ve all learned to count. In the binary
number system, we only have two digits, zero and one. With these two digits, we can count put to any number. Here’s who this
works.

# How do we count in Decimal?

* ![#f03c15] 0	   Start at 0
* ...	Count 1,2,3,4,5,6,7,8, and then...
* 9	 	This is the last digit in Decimal
* 10	 	So we start back at 0 again, but add 1 on the left

In decimal number system, there’s the one position, the 10 position, the 100 position, and so on. For example, a nine in the
100 position is a 900.



In binary, each position also carries a value, but instead of multiplying by 10 each time, you multiply by two. there’s 1
poison, 2 position, 4 position, 8 position, and so on.

For example, the number nine in binary is 1001. Almost nobody does this math because computer do it for us. What’s important
is that any number can be represented with only ones and zeros. or by a bunch of wires that are on or off. The more wires use,
the larger the numbers you can store.

With eight wires, you can store numbers between 0 and 255. That’s eight ones. With just 32 wires, you can store all the way
from zero to over four billion. Using the binary number system, you can represent any number you like.

But what about other types of information.like text ,image, or sound? It turns out that all these things can also be
represented with numbers.



