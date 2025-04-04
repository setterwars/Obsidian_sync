# TCP reliable data transfer
---

 RDT(reliable data transfer) protocol
 
![[Pasted image 20250307125813.png]]

Transport layer protocol process-to-process communication.

Segmentation of data packages if data large.
Network multiplexing is a technique that allows multiple signals or data streams to share a single communication channel efficiently using methods like TDM, FDM, WDM, or CDM.

### Transport layer service 

```handwritten-ink
{
	"versionAtEmbed": "0.3.3",
	"filepath": "Ink/Writing/2025.3.7 - 13.21pm.writing"
}
```
- No lost package
- No corrupted Data 
- Correctly assembler package on a receiver part

![[Pasted image 20250307132523.png]]

![[Pasted image 20250307133441.png]]

### RDT Interface functions

| RDT Function   | Description                                      |
| -------------- | ------------------------------------------------ |
| rdt_send()     | Reliable data sending                            |
| udt_send()     | Unreliable data sending over a physical channell |
| rdt_rcv()      | Reliable data receipt                            |
| deliver_data() | Data delivery to upper layers                    |

### RDT Modeling through FSM


```handwritten-ink
{
	"versionAtEmbed": "0.3.3",
	"filepath": "Ink/Writing/2025.3.7 - 14.08pm.writing"
}
```


![[Pasted image 20250307142331.png]]![[Pasted image 20250307142615.png]]


---
# Routers and Switches 

##### Switch types
Memory 
Broadcast
point triggering fabric
