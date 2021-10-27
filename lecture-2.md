# Lecture 2

## The Network Core 

The job of the core is to transfer packets from one place to another.
take the packet from the access network and sends them across several routers until finally it reaches the destination.

The routing protocol finds a path through the set of routers that connects the source and destination.

### How Resources are Shared?

The network core is just a huge resources shared.

## Circut Switchig 

if you have a resource, you divide it among the users that would like to access the resource.

for example, if you have a router and you're trying to share the resourcse of these routers among several divces.

you reserve some of the resources of that router for for one connnection and reserve another part to a differnert connection.

the advantage of circurt switching is that you have reserved resources and there's no interfernce, you may or may not use the resources depending on their availability but if you get the reources, no one 
else share them withh you.

They're two main ways how to share the resources of a router.
1. frequency division multiplexing.
2. time division multiplexing.

### TDM 

you divide the time into fixed slots, slots can be a any duration(1 sec for example), and 
you assign each slot to a particular communication session.

During each slot, the n users may send data to each other, if someone has a packet to send, can only be sent during that reserved slot.
if a packet is generated outside that slot, it has to wait to its turn.

> The resousores are shared evenly among the all communication sessions that are requseting access to the resources.

### FDM 

you have the entire spectrum of the frequency, and yyou divide it into frequencies chunk and each communication session gets its frequency band.

> the resources are shared evenly among the all communication sessions that are requseting access to the resources.


#### Circut switching disadvantage

let's say you're making a a call, you have reserved resources for that call, once the call is active, you're silent for a while, during that period, resources are reserved for you even you're not using them.

so circut switching tends to be  very lossy, it loses alot of resources.


## Packet Switching

packet switching means taht each packet once it arrives the router it's going to use its full resources. 

every router has an internal memory (buffer), once a packet arrives, it's going to be stored in the buffer (at the end of the queue) waiting for its turn.

the routers are going to transmit one packet after the other.

Two types of routers uses packet switching.

- "store and froward" is the most common one, the router needs to receive the packet and store it in its buffer, then it will transmit it to the next router.
- "cut through" doesn't have to want unti the full packet received, it can transmit the packet as soon as it receives it.

The buffer has fixed limited capacity, if the buffer is full, the packet is dropped.
This called **congestion**.

packet switching is 
                    
                    - great for bursty data
                    - resource sharing
                    - simple, no call setup

## Network Structure 

- **Tier 1 ISP** 
the largest network and its job is to conenect contientes (under water submarine cables).

- **Tier 2 ISP**
the second largest network and its job is to conenect countries, get thier connectivity from Tier 1 ISP.

**Tier 3 ISP** this is local ISP 

WE can be considerd both Tire 2 and 3 ISP.

