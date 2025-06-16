![image alt](https://github.com/GOODNEWS221/cisconetworkproject/blob/84fe435a8432bc0a0dac822d7afb99b549327c9d/NEWTECH_ENT/NEWTECH_PNG.png)

This topology has 1 ISP CE routers, 2 LAN Routers, 1 Switch, 4 LAN, 4 voice VLAN

The configurations include DHCP,NAT,SSH,AAA,HSRP,EIGRP,VLANS,DNS,STP,PORT SECURITY

The STP was configured to match with the HSRP standby as the switch G0/1 interface which is the outbound interface to NEWTECH1(Router) is the primary pass for Vlan 10 and 20, Voice LAN 11 and 21, NEWTECH1 is the primary pass for same VLAN

Whereas 

switch G0/2 interface which is the outbound interface to NEWTECH2(Router) is the primary pass for Vlan 30 and 40, Voice LAN 31 and 41, NEWTECH2 is the primary pass for same VLAN

Also an access-list was configured to make sure that only the TECH department can login to the various nodes with telnet and SSH

## ✅ Features Covered

- 🔐 SSH Configuration
- 🔁 HSRP Setup (Primary & Secondary roles)
- 🌐 NAT Overload with ACLs
- 🗺️ EIGRP Routing (neighbor, topology, route tracking)
- 📊 Port-Security (static and sticky MACs)
- 🔧 VLAN & Trunking Configuration
- 🔄 Spanning-Tree Enhancements (Priority, BPDU Guard)
- 🔌 SVI-based routing and IP addressing


![images alt](https://github.com/GOODNEWS221/cisconetworkproject/blob/d5439c119343802d9ace01f8af39da2f37e0fa7c/NEWTECH_ENT/NEWTECH_PING.png)

