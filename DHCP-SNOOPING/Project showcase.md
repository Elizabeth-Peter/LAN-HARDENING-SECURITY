<h1>DHCP-SNOOPING</h1>


<h2>Description</h2>

<br>DHCP Snooping is a network security feature that blocks unauthorized DHCP servers, prevents IP spoofing, and ensures clients get IP addresses only from trusted sources

## Key Features of DHCP Snooping Implementation Include:

- <B>Blocks rogue DHCP servers <B/>

- Tracks IP, MAC, VLAN, and port info <B/>

- Protects against IP spoofing<B/>

- Supports DAI and IP Source Guard<B/>

- Limits DHCP traffic on untrusted ports<B/>


This repository serves as a practical showcase of DHCP Snooping implementation, LAN security hardening, and access control strategies ideal for IT professionals, students, and cybersecurity enthusiasts.
<br />


<h2>Environments Used </h2>

- Cisco Packet Tracer / GNS3 / Cisco IOS: For switch and network simulation<B/>
- Virtual LANs (VLANs): To segment network traffic<B/>
- DHCP Server: To assign IP addresses dynamically<B/>
- PC/End Devices: Simulated clients for testing DHCP Snooping<B/>
- IT Security Tools: Optional tools for monitoring and verification<B/>

<h2>Project walk-through:</h2>

<p align="center">
Network Diagram: <br/>
<img src="https://imgur.com/U7HG1gy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
IP Structure for the Network:  <br/>
<img src="https://imgur.com/QDXrGOn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Deploying the VMs:  <br/>
<img src="https://imgur.com/TQKiIUP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Setting up the CEO PC IP address:  <br/>
<img src="https://imgur.com/QKiOMSe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Connectivity Test on The Network using ping utility:  <br/>
<img src="https://imgur.com/FWBBJkF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Performing Scanning Using NMAP Against DNS-Server:  <br/>
<img src="https://imgur.com/1dkUkND.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Running an Active Scan Using NMAP RESULTS FOR WEB SERVER:  <br/>
<img src="https://imgur.com/NdEC0Xk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Running a Connectivity Test from a Trusted Network to Untrusted Network:  <br/>
<img src="https://imgur.com/SBWfKHC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Running a Connectivity Test from a Untrusted Network to Trusted Network:  <br/>
<img src="https://imgur.com/yGawPpd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Capturing Packets Using WireShark:  <br/>
<img src="https://imgur.com/WBTZCnj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
</p>

<h2>Conclusion</h2>

<br>This project represents a key step in strengthening network security and hardening LAN environments while maintaining efficiency and scalability. By implementing DHCP Snooping, along with supporting features like Dynamic ARP Inspection and Port Security, I transformed a standard network setup into a secure, controlled, and resilient infrastructure. The deployment ensures robust IP address management, protection against rogue DHCP servers, and prevention of IP spoofing, providing reliable and secure connectivity for all devices.

The implementation not only addresses current security challenges but also establishes a solid foundation for future network expansion and integration of advanced security protocols. Through careful planning and execution, this project showcases how practical security measures and technical expertise can enhance network integrity, demonstrating a commitment to scalable, secure, and professional IT solutions.
<br />
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
