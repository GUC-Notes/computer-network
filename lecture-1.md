# Lecture 1

## What's The internet?

We can divide the internet into two parts:

1. The Edge
2. The Core

### Edge

- The edge is where our devices are.

- If one edge device wants to communicate with otherone, it has to inject data in the core.

### Core

The core consists of high speed switching device, They're basically two different form either a switch or a router

- Switches are more used to connect smaller networks and local networks.

- Routers are the one who's used to transport data across the internet
  
so you inject packets(data) into the core and the routers are responsible for transporting these data from router to another until it reacheas a router that connected
to a destenation or the end device that you want to send the data to.

## nuts-and-bolts description

he Internet is a computer networks that interconnects hundreds of millions of computing devices through the world.

All the devices connected to the Internet are called **hosts** or **end systems**. End systems are connected together by a network of communication links and packets switches.

Different links can transmit data at different rates, with the transmission rate of a link measured in bits/second.

When one end system has data to send to another end system, the sending end system segments the data and adds header bytes to each segment. The resulting packages of information, called packets, are then sent through the network to the destination and system where they a reassembled into the original data.

**Example**: if you want to download a website, you contact the server, you send them
an http request to the server then it sends you the content back.

Routers communicate with each other through communication links (wired, wireless).

## A Services Description

The Internet can be described as an infrastructure that provides services to applications. These applications (Web, social networks, VoIP...) are said to be distributed since they involve multiple end systems that exchange data with each other. Internet applications run on end systems, not in the packet switches or routers, packet switches facilitate the exchange of data, but they are not concerned with the application that is the source or sink of data.

End systems attached to the Internet provide and Application Programming Interface (API) that specifies how a program running on one end system asks the Internet infrastructure to deliver data to a specific destination program running on another end system.

### What Is a Protocol?

All the activity in the Internet that involves two or more communicating remote entities is governed by a protocol.

> A protocol defines the format and the order of messages exchanged between two or more communicating entities, as weel as the actions taken on the trasmission and/or receipt of a message or other event

**Example** TCP protocol

The clinet starts by sending a connection request. If the responded that means 

- it understood the request
- it's willing to respond (enough responses, time, auth).

Now, The clinet can send thier http request.
