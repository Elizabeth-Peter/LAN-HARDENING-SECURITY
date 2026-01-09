## DHCP-Snooping

DHCP Snooping is a Layer 2 network security feature used on switches to protect against rogue DHCP servers and DHCP-based attacks. It works by allowing DHCP messages only from trusted ports while blocking unauthorized DHCP responses from untrusted ports.



## How DHCP-Snooping Works

- <b>Switch ports are classified as trusted or untrusted.<b/>

- <b>Trusted ports: Allowed to send DHCP server responses (usually uplink ports to the legitimate DHCP server).<b/>

- <b>Untrusted ports: Only allowed to send DHCP requests (typically end-user access ports).<b/>

- <b>The switch inspects DHCP packets and drops invalid or malicious ones.<b/>


 
## Key Functions

- <b>Prevents rogue DHCP servers<b/>

- <b>Protects against IP address spoofing<b/>

- <b>Builds a DHCP Snooping Binding Table (MAC address, IP address, VLAN, and port)<b/>

- <b>Supports other security features like Dynamic ARP Inspection (DAI) and IP Source Guard<b/>


## Benefits

- <b>Enhances LAN security<b/>

- <b>Ensures clients receive IP addresses from legitimate DHCP servers<b/>

- <b>Reduces man-in-the-middle and network disruption attacks<b/>



## Basic Configuration Example (Cisco Switch)
``` bash
enable
configure terminal
ip dhcp snooping
ip dhcp snooping vlan 10

interface GigabitEthernet0/1
 ip dhcp snooping trust

interface range GigabitEthernet0/2 - 24
 ip dhcp snooping limit rate 5

end
write memory
```

## Application
DHCP Snooping is commonly deployed in enterprise networks, campus LANs, and secure environments where network integrity and controlled IP address assignment are critical.





