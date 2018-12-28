# Chapter 5: Addressing system and Routers in Internet

In this chapter, we'll explore more deeply how communication between multiple computers can work over the Internet. We will
learn “Internet Protocol” addressing system, commonly known as IP Addresses. The benefits and security concerns associated
with routing traffic across the Internet:

### ![#ff00ff](https://placehold.it/15/ff00ff/000000?text=+) `1. IP addresses and DNS.`
### ![#66ccff](https://placehold.it/15/66ccff/000000?text=+) `2. Packets and Routers.`

# `1. IP addresses and DNS.`

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
  <img height="300" width="400" src="https://github.com/XinYangSAU/CSCI1101-Intro-to-Computing/blob/master/Images/ip.png" alt="Binary"/>
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
per address, and provides over `340 undecillion ($3.4 \times 10^38$) unique addresses`.







