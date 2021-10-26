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

## Internet Strandards 

- RFC (Request for Comments) each protocol has an RFC number
  
- IETF Internet Engineering Task Force who authorize RFC

The internet is a **best effort** network, it means that the internet can never provide any garuntee on any network services.

The edge injects packets into the core using an access networsk *bridge* like (DSL, mobile network).

## Types of communication 

### Client/Server model 

- The most used one
- The cllients don't talk directly to each other, the first client has to send first to the server and the server reply.
- The client always iniates the communcation session. The server is always on waiting for requests.
- This structure is infrastrcture inteensive, you have to spend alot of money to create the infrastructure.


### Peer to peer model

clients communicate with each other without a server directly.
some apps are peer to peer, like BitTorrent.


## Dial-up Modem

- it uses an infrastructre that's already available (The telphone infrastrcture).
- to start a connection you have to dial a number and wait for the connection to be established.
- the telphone network is an analog network while the internet is a digital network, so we use 
modem to transfer between analog and digital networks.
- the voice bandwidth is 0 ~ 4KHZ Thus the internet speed is up t 56KPbs.
- you can't surf and phone at the same time.

### DSL (Digital Subscriber Line)

- it uses the entire bandwidth of the telphone infrastrcture.
- spiltter is a filter it takes the frequency belongs to phone voice and sends it to the telephone.
- the higher  frequency and sends that to DSL.


### Residential access: cable modems
Does not use telephone infrastructure Instead uses cable TV infrastructure


### Wireless access networks

- small range -> WIFI
- wider -> mobile networks

