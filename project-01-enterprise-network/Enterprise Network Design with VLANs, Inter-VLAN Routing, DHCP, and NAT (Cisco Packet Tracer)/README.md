# Enterprise Network Design with VLANs, DHCP, and NAT  
**Tool:** Cisco Packet Tracer

## 📌 Overview
This project demonstrates the design and configuration of a small enterprise network using Cisco Packet Tracer. The network is segmented using VLANs, supports inter-VLAN communication, assigns IP addresses dynamically using DHCP, and provides internet access to internal users using Network Address Translation (NAT).

---

## 📂 Packet Tracer File
The complete Cisco Packet Tracer (.pkt) file is included in this repository and contains all configurations used in this project. Reviewers can open the file to explore the network design and CLI configurations in detail.

---

## 🎯 Project Objectives
- Design a multi-VLAN enterprise network
- Enable communication between different VLANs
- Configure DHCP for automatic IP address allocation
- Implement NAT (PAT) to allow private networks to access external networks
- Verify connectivity and troubleshoot network issues

---

## 🧱 Network Topology
The network consists of:
- Multiple PCs connected to a Layer 2 switch
- VLAN-based segmentation
- A main router configured with subinterfaces (router-on-a-stick)
- An ISP router to simulate external connectivity

---

## 🧱 Network Components

- Cisco Router (Main Router)

- Cisco Switch (Layer 2)

- ISP Router (Simulation)

- Multiple PCs in different VLANs

## 🔧 Technologies & Concepts Used
- VLANs and VLAN Trunking (802.1Q)
- Router-on-a-Stick (Inter-VLAN Routing)
- DHCP Configuration
- NAT (PAT / Overload)
- Static Routing
- Cisco IOS Command Line Interface (CLI)

---

## ⚙️ Configuration Details

### VLAN Configuration
Three VLANs were configured on the switch to segment the network:
- VLAN 10 – Users  
- VLAN 20 – Admin  
- VLAN 30 – Servers  


---

### Inter-VLAN Routing
Router subinterfaces were created for each VLAN, enabling communication between VLANs.


---

### DHCP Configuration
The router was configured as a DHCP server to automatically assign IP addresses to devices in each VLAN.


---

### NAT Configuration
NAT overload (PAT) was configured on the router, allowing internal private IP addresses to access an external network through a single public IP address.


---

## ✅ Testing & Verification
- Successful communication between VLANs
- PCs successfully receive IP addresses via DHCP
- Internal hosts can access the external network through NAT
- Connectivity verified using ICMP (ping)


---

## 🧠 Key Learning Outcomes
- Understanding enterprise network segmentation using VLANs
- Practical experience with router-on-a-stick design
- Hands-on DHCP and NAT configuration
- Improved troubleshooting skills in a simulated network environment

---

## 🚀 Future Improvements
- Implement Access Control Lists (ACLs) for security
- Configure dynamic routing protocols (e.g., OSPF)
- Add firewall and security policies

---

