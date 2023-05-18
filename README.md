# azure-network-protocols<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />


<h2>Video Demonstration</h2>

- ### [YouTube: Azure Virtual Machines, Wireshark, and Network Security Groups](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

- Install Wireshark 
- Filter icmp and communicate between 2 ip addresses
- DNS Lookup
- 

<h2>Actions and Observations</h2>

<p>
<img src="https://i.imgur.com/xVV0WLr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In this image you can see that I have downloaded wireshark which is now going to allow me moniotr traffic on my VM.
</p>
<br /

<p>
<img src="https://i.imgur.com/CRLwDQG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In the next step I followed the icmp protocol and made contact with another VM with a different ip address.
</p>
<br />

<p>
<img src="https://i.imgur.com/KllXwX6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In the last example I followed the dns protocol. I monitored traffic from my ip address to google.com 
</p>
<br />
