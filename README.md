# 🖧 DataBridge Network Design

## 📘 Project Overview
The **DataBridge Network Design** project demonstrates a small-to-medium enterprise network built in **Cisco Packet Tracer**. The topology connects three departments — **Administration**, **Sales**, and **Human Resources** — through a central router providing inter-VLAN routing and DHCP/DNS services.  
This project highlights IP addressing, VLAN segmentation, device connectivity, and basic network services implementation.

### 🎯 Objectives
- Design and simulate a functional LAN with multiple departments.
- Implement VLANs to segment network traffic for security and performance.
- Configure inter-VLAN routing via a central router.
- Deploy DHCP and DNS services for automated IP assignment and name resolution.
- Validate connectivity between departments and servers.

---

## 🧰 Tools and Technologies
| Tool / Technology | Purpose |
|-------------------|----------|
| **Cisco Packet Tracer 8.2** | Network simulation |
| **Routers (2911)** | Inter-VLAN routing and gateway configuration |
| **Switches (2960, 2950)** | VLAN segmentation and port assignment |
| **DHCP & DNS Server** | Automated IP and name resolution |
| **End Devices (PCs)** | Departmental hosts for connectivity testing |
| **IPv4 addressing** | Network communication setup |

---

## 🗺️ Network Topology
![Network Diagram](./DATABRIDGE%20NETWORK%20DESIGN.png)

**Departments and Subnets**
| Department | Subnet | Default Gateway |
|-------------|---------|-----------------|
| Administration | 192.168.10.0/24 | 192.168.10.1 |
| Sales | 192.168.20.0/24 | 192.168.20.1 |
| Human Resources | 192.168.30.0/24 | 192.168.30.1 |

---

## ⚙️ Configuration Summary
- **Router:** Configured with subinterfaces for each VLAN and corresponding IP gateways.  
- **Switches:** Assigned VLANs and configured trunk ports.  
- **DHCP/DNS Server:** Provides IP addresses dynamically and resolves domain names.  
- **End Devices:** Assigned to VLANs and tested for inter-department communication.

---

## ✅ Key Takeaways
- VLANs improve **security**, **network organization**, and **performance**.
- Inter-VLAN routing allows communication between segmented departments.
- Centralized DHCP/DNS simplifies IP management and host configuration.
- Proper IP planning ensures scalability and troubleshooting ease.

---

## 📊 Results
- Successful **ping and connectivity** across all departments.  
- Automatic IP addressing verified via DHCP.  
- DNS resolution confirmed using configured DNS server.  

---

## 🚀 How to Run
1. Open `DATABRIDGE MOD 1.pkt` in **Cisco Packet Tracer 8.2 or later**.
2. Power on all devices.
3. Use the `ping` command from one PC to another to test connectivity.
4. Experiment with VLANs, DHCP scopes, or adding new departments.

---

## 🧩 Future Improvements
- Add redundancy using multiple routers (HSRP or VRRP).
- Implement ACLs for traffic control between VLANs.
- Integrate wireless access points for mobility.

- 
  (https://drive.google.com/file/d/1Srd7Ldq8Ej-PFIQRp4T1nj2-cvLhAL-a/view?usp=sharing)

## 👩🏽‍💻 Author
Emmanuella Obenewah Oppong (@Emmanuella Oppong) 
_Networking & IT Infrastructure Enthusiast_

---

## 🪪 License
This project is licensed under the [MIT License](LICENSE).
# Emmanuella-O-Oppong
My Profile
