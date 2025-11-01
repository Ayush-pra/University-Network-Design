# Enterprise Network Design – Cisco Packet Tracer

# Objective
Design a full-fledged network for an organization that demonstrates inter-departmental communication, and core networking concepts.

# Network Overview
The organization’s network consists of three primary departments connected through a central router using OSPF routing:
1. **IT Department** – bottom left block  
2. **Head Office** – bottom right block  
3. **HR Department** – top left block  

Each department includes both **wired** and **wireless** hosts, connected through switches and access points configured with **WEP/WPA security**.

# Key Features
- **Routing:** Implemented using **OSPF** for dynamic route advertisement across all departments.  
- **Inter-VLAN Routing:** Departments are segmented into VLANs for logical separation with communication enabled via router-on-a-stick configuration.  
- **Subnetting:** Applied **CLSM (Continuous Length Subnet Masking)** to efficiently utilize IP addresses.  
- **DHCP:** Automatic IP assignment to all end devices across subnets.  
- **Wireless Networks:** Configured access points with WEP/WPA authentication for secure wireless connectivity.  
- **Servers:**  
  - **DHCP Server** – Dynamic IP allocation  
  - **DNS Server** – Domain name resolution  
  - **FTP Server** – File sharing between devices  
  - **HTTP Server** – Website hosting for internal/external access  
  - **Mail Server** – Handles SMTP, POP3, and IMAP services  

# Topology Description
- Central router connects all three departments using serial/WAN links.  
- Each department network contains multiple switches and wireless access points.  
- VLANs are configured per department for better traffic management.  
- All devices can communicate with each other and access shared resources via OSPF routing.

# Testing and Verification
- Successful ping between PCs across different VLANs and departments.  
- Wireless hosts authenticated successfully using WPA/WEP.  
- DHCP assigned IPs correctly to all wired and wireless clients.  
- Web, FTP, and Email servers successfully accessed by clients.

# Tools and Technologies
- **Cisco Packet Tracer** (Version 8.x)  
- **Devices Used:** Routers, Layer 2/3 Switches, PCs, Laptops, Servers, Wireless Routers, Access Points  

# Learning Outcomes
- Implementation of enterprise-scale OSPF routing  
- VLAN segmentation and inter-VLAN routing  
- DHCP and DNS service configuration  
- Wireless network design with authentication  
- Integration of multiple servers and protocols  



