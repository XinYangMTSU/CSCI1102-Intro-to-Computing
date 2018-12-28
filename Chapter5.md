# Chapter 5: Addressing system in Internet

In this chapter, we'll explore more deeply how communication between multiple computers can work over the Internet. We will
learn “Internet Protocol” addressing system, commonly known as IP Addresses:

### ![#ff00ff](https://placehold.it/15/ff00ff/000000?text=+) `1. IP addresses`
### ![#66ccff](https://placehold.it/15/66ccff/000000?text=+) `2. Domain Name System`

# `1. IP addresses.`

Every computer on the Internet has an address that uniquely identifies it. An address on the Internet is just a number:
141.72.251.38. The addressing system for computers on the Internet is similar to a mailing address, and it forms part of one
of the most important protocols used in internet communication, simply called the `Internet Protocol`, or IP. A computer’s
address, then, is called its `IP address`. Visiting a website is really just your computer asking another computer for
information. Your computer sends a message to the other computer’s IP address, and it also sends along its origin address so
the other computer knows where to send its response. 

<p align="center">
   Figure 1: IP address
</p>

<p align="center">
  <img src="https://github.com/XinYangSAU/CSCI1101-Intro-to-Computing/blob/master/Images/ip.png" alt="Binary"/>
</p>

<p align="center">
   https://www.expressvpn.com/what-is-my-ip
</p>

As you've seen, an IP address is just a bunch of numbers. These numbers are organized in a hierarchy. Just like a home
address has a country, a city, a street, and a house number, an IP address has many parts.

Each of these numbers is represented in bits. Traditional IP addresses are `32 bits` long, with eight bits for each part of
the address. The earlier numbers usually identify the country and regional network of the device. Then come the subnetworks.
And then, finally, the address of the specific device. This version of IP addressing is called `IPv4`. It was designed in
1973, and widely adopted in the early 80s, and provides for more than `4 billion unique addresses` for devices connecting to
the internet.

But the internet has turned out to be much more popular than people imagined, and 4 billion unique addresses won’t be
enough. We are now in the middle of a multi-year transition to a longer IP address format called `IPv6`, which uses `128 bits`
per address, and provides over `340 undecillion unique addresses` (![equation](http://latex.codecogs.com/gif.latex?%7B3.4%7D\times%7B10^{38})).

<p align="center">
   Figure 2: IPv4 vs Ipv6
</p>

<p align="center">
  <img src="https://github.com/XinYangSAU/CSCI1101-Intro-to-Computing/blob/master/Images/ip2.png" alt="Binary"/>
</p>

# `2. Domain Name System.`

Most users never see or care about internet addresses. A system called the `Domain Name System`, or DNS, associates names,
like `www.google.com`, with the corresponding addresses. Your computer uses the DNS to look up domain names and get the
associated IP address, which is used to connect your computer to the destination on the internet. 

A domain name is the text version of an IP address. Domain names are easy for people to remember and type.

<p align="center">
   Figure 3: Domain Name Example
</p>

<p align="center">
  <img src="https://github.com/XinYangSAU/CSCI1101-Intro-to-Computing/blob/master/Images/dn.png" alt="DNS"/>
</p>

How do we design a system for billions of devices to find any one of billions of different websites? The answer is that DNS
servers are connected in a distributed hierarchy, and are divided into zones, splitting up responsibility for the major
domains such as .org, .com, .net, and so on.

The internet is huge, and getting bigger every day. But the Domain Name System and Internet Protocol are designed to scale, no
matter how much the internet grows. 
