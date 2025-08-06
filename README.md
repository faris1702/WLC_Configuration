# WLC_Configuration
This is a basic Wireless LAN Controller setup done in Packet Tracer. Elements of the setup was taken from this [video](https://www.youtube.com/watch?v=0dfm9ws9DXI).

# Configuration
## Introduction
This topology consists of the following network devices:
- 1 Router: 4331
- 1 Switch: 3650 24PS
- 1 WLC: 3504
- 2 APs: LAP-PT
- 1 Server
- 3 End Devices: 1 Laptop & 2 Smartphones

Reasons for choosing these network devices
<b>Router</b><br>
There is no particular reason for the router selection as it was used solely as the default gateway of the network<br>
<b>Switch</b><br>
The 3650 24PS switch was chosen as it has the following characteristics:
- Layer 3 switch: Became the default gateway for the VLAN, and would have a default route to the router (optional)
- Multiple Gigabit Ports: APs would benefit the most being connected to a gigabit connection and all the other routers in Packet Tracer only have at most 2 gigabit connection
- Power over Ethernet (PoE): This allows the switch to power the APs without the APs needing to connect to an external power source
<b>WLC</b><br>
wolhs
