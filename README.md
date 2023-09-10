<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />


<h2>Video Demonstration</h2>

- ### [YouTube: Azure Virtual Machines, Wireshark, and Network Security Groups](https://www.youtube.com/watch?v=gU8ZmJkoGWc)

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

- Create Resources
- Observe ICMP & SSH Traffic
- Observe DHCP & DNS & RDP Traffic

<h2>Actions and Observations</h2>

<p>
  
![image](https://github.com/techwiz77777/azure-network-protocols/assets/143854558/b45234ca-8f84-4007-8ad2-89d7653eaab8)
  
![image](https://github.com/techwiz77777/azure-network-protocols/assets/143854558/f2f3878e-044a-4133-b53e-9cdedd97ddfc)
</p>
<p>
We create resources and download wireshark to observe the traffic.
</p>
<br />

<p>
  
![image](https://github.com/techwiz77777/azure-network-protocols/assets/143854558/49b7c684-9af7-4ba9-8042-29b7becfa82e)
</p>
<p>
Here we open up wireshark and type in the filter bar to filter ICMP, SSH, DHCP, DNS, AND RDP traffic.
</p>
<br />
