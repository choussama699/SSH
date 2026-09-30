# SSH

A lab that configures SSH version 2 on a Cisco router and a Cisco switch so both can be managed remotely and securely from a PC, replacing insecure Telnet.

Topology and Addressing
Device	Interface	    IP Address      	Notes
PC0	    NIC	          192.168.10.10/24	Gateway: 192.168.1.1
Switch0	VLAN 1 (SVI)	192.168.10.2/24  	Default gateway: 192.168.1.1
Router0	Gi0/0.10	    192.168.10.1/24	  Connected to Switch0
