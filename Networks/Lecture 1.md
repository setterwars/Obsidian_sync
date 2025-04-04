# Point to Point network

* The simplest communication scenario.
###### Chanel characteristics
* Transfer data(in one or both direction)
* Wired or wireless
* Emposes transfer delay
* Bounded throughput bits/sec
* Can corrupted and lost data. e.g. flipped bits

NIC(Network interface controller)

```handwritten-ink
{
	"versionAtEmbed": "0.3.3",
	"filepath": "Ink/Writing/2025.2.8 - 15.27pm.writing"
}
```
NIC characteristics:
- To transmit (put) data (of a binary format) into a network channel.
- To take a data from a network channel
- Emposes a "transmission delay", when transmitting or receiving data

When data is transfer is divided into a small blocks - "packets", every packet is transferred independently, bit size of the packets depends on a specific protocol.

Communication protocol - the agreement ("protocol") on technical communication details between network nodes.  **Examples:** HTTP, SMTP, IMAPS, VoLP, etc.

#### Communication Protocol purpose:
- To schedule nodes for data sending.
- To define an exchange data format 
- Other technical details 

# Multi point communication 
![[Pasted image 20250208153802.png]]
Broadcast communication:
- Message from one host is sent to all another.
- Each host, when receiving a message, checks its destination address.
	- it reads a message, if it is destinated to it
	- Otherwise, it discards a message.


# Key concepts of computer networks 

Hosts: end devices exchanging data.
Link: device to transmit data between adjacent nodes.
Router: device to forward/rout data.
Source ans destination host

```handwritten-ink
{
	"versionAtEmbed": "0.3.3",
	"filepath": "Ink/Writing/2025.2.8 - 15.43pm.writing"
}
```
Source host send data, Destination host recives data.
Packets: A block of data of  a pre-defined size.

##### Router like devices:
- Switch 
- Bridge 
- Hub 
- WIFI Access Point 
- Repeater

Network address: Unique identifier for a host.
Network address types: 
- Media access control(MAC) address. Burned-in into network interface card.
- Internet Protocol (IP) address. Assigned dynamically, changed over time. 
	-  IP version 4 (IPv4)
	-  IP version 6 (IPv6)

Network node Types: 
- Network hosts 
	- Source Host
	- Destination Host
- Intermediate Network Nodes
	- Routers 
		- Gateway Routers 
		- (WIFI) repeater
	- Switches 
	- Bridges 


