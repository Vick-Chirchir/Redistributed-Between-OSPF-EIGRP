
<h1>Redistributed Between OSPF & EIGRP</h1>

<!-- ### [Kaltura Capture Recording](https://mediaspace.minnstate.edu/media/Kaltura+Capture+recording+-+April+26th+2025%2C+11%3A11%3A10+pm/1_sp0j5ef9) -->

<h2>Description</h2>
This project demonstrates the redistribution of routes between OSPF and EIGRP within a multi-router network topology using Cisco Packet Tracer. The lab simulates a common enterprise scenario where two different routing protocols operate across network segments and must exchange routing information to ensure full network connectivity. 
This project enhanced my understanding of hybrid routing environments and the practical application of redistribution to bridge protocol boundaries, preparing me for real-world enterprise networking challenges.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Cisco IOS CLI commands</b> 

<h2>Environments Used </h2>

- <b>Cisco Packet Tracer</b> (8.2)

<h2>Program walk-through:</h2>

<p align="center">
Network Design: <br/>
<img src="https://i.imgur.com/bcQgPyr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
DHCP Server Config on the Router(Router 1):  <br/>
<img src="https://i.imgur.com/okCHFdZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Interface Config with Loopback interface as the IP address to the DHCP Server: <br/>
<img src="https://i.imgur.com/8QABK5s.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Router Configuration (Router 2) using (ip helper-address):  <br/>
<img src="https://i.imgur.com/uH3Mw58.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Verify Communication between Devices on both Sites:  <br/>
<img src="https://i.imgur.com/wdv5L5x.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>

