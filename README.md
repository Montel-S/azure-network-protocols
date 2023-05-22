# azure-network-protocols<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, I observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />




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
- Filter icmp and connect between 2 ip addresses
- DNS Lookup


<h2>Actions and Observations</h2>

<p>
<img src="https://i.imgur.com/xVV0WLr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In this image you can see that I have downloaded wireshark which is now going to allow me to monitor and inspect live traffic on my virtual machine.
</p>
<br /

<p>
<img src="https://i.imgur.com/CRLwDQG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In the next step I followed the icmp protocol. In order to get a response between the 2 virtual machines I first had to find the private ip address for VM2. After that I pinged the ip address and waited for a reply.
</p>
<br />

<p>
<img src="https://i.imgur.com/KllXwX6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here in the last screenshot I followed the dns protocol. I monitored traffic from my ip address to google.com and observed the information that was sent back.
</p>
<br />
