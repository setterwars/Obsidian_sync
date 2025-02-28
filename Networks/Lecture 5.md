# Domain name system(DNS)
---
Most important protocol in networks is a HTTP

### DNS motivation: Webpage Retrieval example
- Webpage are hosted by sever 
- Network devices are identified by IP addresses
- User access webpages by human-friendly domain names
- Network communications are translated into server IP addresses
- DNS is a database of domain names
- DNS translate Domain name<>IP acting as a 'phone book'
```handwritten-ink
{
	"versionAtEmbed": "0.3.3",
	"filepath": "Ink/Writing/2025.2.21 - 13.03pm.writing"
}
```
### What is the most time-consuming step?
- DNS lookup, because of a large number of domain name
#### Possible optimizations:
- Local caching of frequently used IP addresses.(reduce DNS server load,)
- Hierarchical organization of DNS

### DNS organization 

```handwritten-ink
{
	"versionAtEmbed": "0.3.3",
	"filepath": "Ink/Writing/2025.2.21 - 13.58pm.writing"
}
```
**DNS iterative query**
**DNS recursive query**


## DNS requests


```handwritten-ink
{
	"versionAtEmbed": "0.3.3",
	"filepath": "Ink/Writing/2025.2.21 - 14.43pm.writing"
}
```
Example

mail.innopolis.ru 188.130.155.55 A


---
# Summary of Application Layer Protocol

---

| Protocol | Primary Purpose                                             | Statefulness                                          | Persistency                                                          | Port number | Transport Protocol |
| -------- | ----------------------------------------------------------- | ----------------------------------------------------- | -------------------------------------------------------------------- | ----------- | ------------------ |
| HTTP     | WEB page retrieval                                          | Stateless                                             | Either presistent or not, subject to configuration                   | 80,443      | TCP                |
| FTP      | Large file download                                         | Stateful                                              | Contrroll connection - persistent<br>Data conection - non-persistent | 21,20       | TCP                |
| SMTP     | Email sending from a client to a server, or between servers | Stateless                                             | Persistent                                                           | 25,587      | TCP                |
| IMAP     | Emails receival by a client                                 | Stateful                                              | Either persistent or not, subject to configuration                   | 143, 993    | TCP                |
| POP      | Emails receival by a client                                 | Stateless                                             | Persistent                                                           | 119,995     | TCP                |
| DNS      | Translation or host names to IP addresses                   | Stateless                                             | not-persistent                                                       | 53          | UDP                |
| DHCP     | IP assignment and other cofigurations to network hosts      | Either stateful or stateless, subject to confguration | Typically non-persistent, but can be configrate                      | 67,68       | UDP                |


---
# OSI and TCP/IP Reference model Data Encapsulation Introduction to Transport Layer Protocls

---
