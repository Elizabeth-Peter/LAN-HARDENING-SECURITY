## 🔐 Port Security  

Port Security is a Layer 2 switch security feature used to restrict network access by limiting the number of MAC addresses allowed on a switch port. It helps prevent unauthorized device access, MAC flooding attacks, and accidental misuse of network ports. When a violation occurs, the switch can take actions such as shutting down the port, restricting traffic, or silently dropping packets.

## ⚙️ Port Security Configuration (Cisco IOS)

```bash
# Configure the interface as an access port
interface FastEthernet0/1
 switchport mode access
 switchport access vlan 10
 switchport port-security
 switchport port-security maximum 1
 switchport port-security mac-address sticky
 switchport port-security violation shutdown
exit

```
## 🔍 Verification Command
```bash
show port-security interface FastEthernet0/1
```

## 🚨 Port Security Violation Modes

- <b>shutdown – Disables the port when a violation occurs (most secure)<b/>

- <b>restrict – Drops unauthorized traffic and logs the violation<b/>

- <b>protect – Drops unauthorized traffic silently<b/>
