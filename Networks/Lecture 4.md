
---
## Electronic Mail Timeline

- 1961: MIT compatible Time-Sharing System (CTSS)
- 1965: "MAIL" command in CTSS operating system
- 1969: ARPANET (Advanced Research Projects Agency Network) computer network
- 1971: ARPANET's network email system by Rai Tomlinson
- 1976: First attempts of electronic mail sending to external network
- 1981: SMTP protocol release
- 1980 Multiple LAN email systems emerged 
- 1988, 1989: Eudora by Steve Dorner and Lotus Notes applications for email management
- 1993-1996 AOL, Echomail, Hotmail, Yahoo mail services
- 1996 Internet Mail and News  1.0 service by Microsoft

# Email address format

```
<local_part> @ <domain_name>
```
local part can be Unquated and quated.


# Client server Architecture For emails Exchange 


```handwritten-ink
{
	"versionAtEmbed": "0.3.3",
	"filepath": "Ink/Writing/2025.2.14 - 14.43pm.writing"
}
```


# Network calculus

## Network calculus basics


```handwritten-ink
{
	"versionAtEmbed": "0.3.3",
	"filepath": "Ink/Writing/2025.2.14 - 15.33pm.writing"
}
```

| $U_s$                                 | Server maximum uplad speed, bytes/sec       |
| ------------------------------------- | ------------------------------------------- |
| $u_l$                                 | Server actual upload speed to Client $l$    |
| $d^{max}_l$                           | Client $l$ maximum download speed           |
| $d_l$                                 | Client $l$ actual speed                     |
| $\sum^n_{l=1}(d_l)\leq U_s$           | Bound on total upload speed to $N$ client   |
| $\sum^N_{l=1}(d_l)\leq U_s$           | Bound on total download speed by $N$ client |
| $u_l \leq d_l^{max}$                  | Bounds on client $l$ download speed         |
| $d_l = \min(d_l^{max},\frac{U_s}{N})$ | Bounds on client $l$ download speed         |
