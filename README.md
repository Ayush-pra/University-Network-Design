# 🧩 Detailed Documentation – University Network Design

## 🎯 Objective
To design a **multi-department university network** demonstrating real-world routing, switching, and server integration using Cisco Packet Tracer.

---

## 🏗️ Network Overview
The network connects three major departments using **OSPF dynamic routing**:
| Department | IP Block | Description |
|-------------|-----------|-------------|
| CSE | 55.0.0.0/10 | Academic & Lab PCs |
| Library | 55.64.0.0/10 | Resource center network |
| ME | 55.192.0.0/10 | Mechanical Engg. department |

Each has **wired and wireless** clients, VLANs for separation, and centralized services.

---

## ⚙️ Key Configurations

### 🔹 OSPF Configuration
- Area 0 backbone across all routers  
- Each router advertises its VLAN interfaces  
- Verified routing table entries on all devices  

Inter-VLAN routing handled via subinterfaces on the core router.

### 🔹 DHCP Server
- Centralized server assigning dynamic IPs  
- IP pools per VLAN  
- Verified with successful lease allocations  

### 🔹 Wireless Network
- WPA/WEP authentication for all access points  
- Devices connected successfully with correct IP leases  

### 🔹 Servers
| Service | Description |
|----------|--------------|
| DHCP | IP management |
| DNS | Domain resolution |
| FTP | File sharing |
| HTTP | Web hosting |
| MAIL | Email communication (SMTP/POP3) |

---

## 🧪 Testing & Verification
- ✅ Cross-VLAN ping success  
- ✅ DHCP leases verified for all clients  
- ✅ Wireless devices authenticated  
- ✅ FTP and HTTP accessible  
- ✅ OSPF neighbor adjacency confirmed  

---

## 🧰 Devices & Software
- **Cisco Packet Tracer v8.x**
- **Routers, L2/L3 Switches, PCs, Servers**
- **Access Points, Wireless Routers**

---

## 🚀 Future Scope
- Add redundancy (HSRP/VRRP)
- Introduce firewall (ASA/IPS)
- Enable Syslog/SNMP monitoring
- Connect cloud or external WAN simulation

---

## 📘 Summary
This project represents a **complete campus-level network model**, showcasing:
- Routing (OSPF)
- VLANs & DHCP
- Secure wireless integration
- Multi-service server setup

---

