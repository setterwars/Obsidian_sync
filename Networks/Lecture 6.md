# Encapsulation and Deencapsulation
---
### Data encapsulation 
- HTTP message Format 
- TCP segment fomat
- Datagram format 
- Ethernet frame format 

![[photo_2025-02-28_13-04-10.jpg]]

## Encapsulation 

```handwritten-ink
{
	"versionAtEmbed": "0.3.3",
	"filepath": "Ink/Writing/2025.2.28 - 13.05pm.writing"
}
```
##### Router and switch key differences:

|Feature|Router|Switch|
|---|---|---|
|**Function**|Connects networks (LAN to WAN)|Connects devices in a LAN|
|**Layer**|Network Layer (Layer 3)|Data Link Layer (Layer 2)|
|**Addressing**|Uses IP addresses|Uses MAC addresses|
|**Data Handling**|Routes data between networks|Switches data within a network|
|**Ports**|Fewer ports (e.g., 4-8)|More ports (e.g., 24-48)|
|**Internet Access**|Required for internet connection|No direct internet connection|
##### TCPIP reference model

| Application | Message  |
| ----------- | -------- |
| Transport   | Segment  |
| Network     | Datagram |
| Link        | Frame    |
| Physical    |          |


---
## Protocol transport layer
**Logical Process-to-Process communication**
- Hides network infrastructure details
- "Logical" an illusion of a direct hosts connection 
- "End system" an OS and network applications processes running on an end host
- "Socket library" network programming library in many programming languages


> **Every process has port**

![[photo_2025-02-28_14-04-39.jpg]]

Socket Libraries Introduced in Berkley Software Distribution (BSD) UNIX 4.2 and treated as file.

![[Pasted image 20250228141653.png]]
**Congestion control** - is a network mechanism used to manage traffic load and prevent congestion collapse in communication networks, particularly in the TCP. It ensures efficient data transmission by regulating the rate at which packets are sent based on network conditions.

## Socket programming in C language

sys/socket.h - Core socket functions and data structure
netinet/in.h - Data structure for representing IP addresses, TCP and UDP port numbers and other
arpa/inet.h - Function for manipulating with numeric IP addresses; An alternative of netinet/in.h for some OS
netdb.h - Translation function of host name
sys/un.h - communication functions for local processes running on the same computer
![[Pasted image 20250228150632.png]]
