<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />


<h2>Video Demonstration</h2>

- ### [YouTube: Network Security Groups and Inspecting Network Protocols](https://www.youtube.com/watch?v=jrQYQaARgRE)

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

- Create Resource Group 
- Create Windows 10 Virtual Machine
- Create Linux (Ubuntu) Virtual Machine
- Observe ICMP, SSH, DHCP, DNS, and RDP traffic

<h2>Actions and Observations</h2>

<p>
<img src="https://i.imgur.com/b1j5f5v.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Example: Download Wireshark.
</p>
<br />

<p>
<img src="https://i.imgur.com/4UkPLKw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Example: Filter ICMP traffic only for VM-2.
</p>
<br />

<p>
<img src="https://i.imgur.com/TMuLKT1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Example: Stopped ICMP traffic for VM-2. Restarted ICMP traffic for VM-2.
</p>
<br />
