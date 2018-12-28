# Chapter 6: Packets and Routers in Internet

In this chapter, we'll explore how is it possible for every piece of data to be delivered reliably in Internet:

### ![#ff00ff](https://placehold.it/15/ff00ff/000000?text=+) `1. Packets`
### ![#66ccff](https://placehold.it/15/66ccff/000000?text=+) `2. Routers`

# `1. Packets`

Say someone want to send an image to you. How’s it possible for every piece of data to be delivered to you reliably? 
The way information gets transferred from one computer to another is pretty interesting. It need not follow a fixed path. In
fact, your path may change in the midst of a computer-to-computer conversation. And just as you can transport all sorts of
stuff inside a car, many kinds of digital information can be sent with IP packets, but there are some limits. For example, you
need to move a space shuttle from where it was built to where it will be launched? A shuttle won’t fit in one truck, so it
needs to be broken down into pieces, transported using a fleet of trucks. They could all take different routes, and might get
to the destination at different times, but once all the pieces are there, you can reassemble the pieces into the complete
shuttle, and it’ll be ready for launch. 

On the internet, the details work similarly. If you have a very large image that you want to send to a friend or upload to a
website, that image might be made up of tens of billions of bits of ones and zeroes, too many to send along in one packet.
Since it’s data on a computer, the computer sending the image can quickly break it into hundreds or even thousands of smaller
parts called `packets`.  

<p align="center">
   Figure 1: Divide bytes of image.jpg into packets.
</p>

<p align="center">
  <img src="https://github.com/XinYangSAU/CSCI1101-Intro-to-Computing/blob/master/Images/packets.png" alt="Binary"/>
</p>

<p align="center">
   Curtesy of Stanford University CS101
</p>

`Each packet has the internet address of where it came from and where it’s going`.

<p align="center">
   Figure 2: Packet
</p>

<p align="center">
  <img src="https://github.com/XinYangSAU/CSCI1101-Intro-to-Computing/blob/master/Images/packet.png" alt="Binary"/>
</p>

<p align="center">
   Curtesy of Khan Academy
</p>

Information on the Internet goes from one computer to another in what we call a `packet of information`, and a packet travels
from one place to another on the internet a lot like how you might get from one place to another in a car, depending on
traffic congestion or road conditions, you might choose or be forced to take a different route to get to the same place each
time you travel. Special computers on the internet, called routers, act like traffic managers to keep the packets moving
through the network smoothly. 

# `2. Routers`

Routers are the traffic directors of the global internet. Routers communicate with each other, and forward network packets out
of or into a network. The router provides the internet connection your traffic goes through it.

<p align="center">
   Figure 3: How does a packet get around the internet ?
</p>

<p align="center">
  <img src="https://github.com/XinYangSAU/CSCI1101-Intro-to-Computing/blob/master/Images/router2.png" alt="router"/>
</p>

<p align="center">
   Curtesy of Stanfor University CS101
</p>

Each router knows enough to figure the next hop, not the whole route. There is no "center" of the internet that knows
everything. Most data you get or send on the Internet goes in packets which take more than 10 but less than 20 hops from
origin to destination.

<p align="center">
   Figure 3: Routers
</p>

<p align="center">
  <img height = "300px" width = "500px" src="https://github.com/XinYangSAU/CSCI1101-Intro-to-Computing/blob/master/Images/routers.png" alt="router"/>
</p>

<p align="center">
   Curtesy of Khan Academy
</p>

If one route is congested, individual packets may travel different routes through the internet, and they may arrive at the
destination at slightly different times, or even out of order. Then how can the out of order packets be reassembled into the
complete original data? 

# `3. Tansmission Control Protocol`

Say you want to send an image to another. How can you be 100% sure all the data will be delivered so the iamge can be
donwloaded perfectly? We need to introduce the new conecpt: `TCP, transmission control protocol`. TCP manages the sending and
receiving of all your data as packets. We can think of it as a guaranteed mail service. 

When you request a song service from Spotiy, Spotify sends the song broken up into many packets. When your packets arrive, TCP
does a full inventory and sends back acknowledgements of each packet received. If all packets are there, TCP signs for your
delivery, and  you are done. 

<p align="center">
   Figure 4: TCP
</p>

<p align="center">
  <img src="https://github.com/XinYangSAU/CSCI1101-Intro-to-Computing/blob/master/Images/tcp.png" alt="tcp"/>
</p>

<p align="center">
   Curtesy of Khan Academy
</p>

If TCP finds some packets are missing, it won’t sign. Otherwise, your song would’t sound as good,
or portions of  the song could be missing. For each missing or incomplete packet, spottily will resend them. Once TCP verifies
the delivery of many packets for that one song request, your song will start to play. 

What’s great about the TCP and router systems is they’re scalable. They can work with eight devices or 8 billion devices. In
fact, because of these principles of fault tolerance and redundancy, the more router we add, the more reliable the Internet
becomes. What’s also great is we can grow and scale the Internet without interrupting serve for anybody using it. 

The Internet is made of hundreds of thousands of networks and billions of computers and devices connected physically. These
different systems that make up the Internet connect to each other, communicate with each other, and work together because of
agreed upon standards for how data is send around on the Internet. Computing devise, or routers along the Internet, help all
the packets make their way to the destination where they’re reassembled, if necessary, in order. This happens billions of
times a day, whether you and others are sending an email, visiting a webpage, doing a video chat, using a mobile app. 





