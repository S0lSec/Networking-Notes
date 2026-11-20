## Private & Public
![[Pasted image 20261118214942.png]]

Public Network --> Untrusted
Private Network --> Trusted

Network traffic can go out and return, but traffic can not come in
## Demilitarised Zone (DMZ)
![[Pasted image 20261118215122.png]]
Firewall design where there is one inside interface connected to the private network, one outside interface connected to the public network and a DMZ interface.

Private --> Public/DMZ (Little or no restriction)
DMZ --> Private (Blocked)
DMZ --> Public (Selectively permitted)
Public --> DMZ (Selectively permitted and inspected)

## Zone-Based Policy Firewall (ZFP)
![[Pasted image 20261118215856.png]]

Uses zones to provide additional flexibility and easier traffic filtering.

Zone - Group of one or more interfaces that have similar functions or features.