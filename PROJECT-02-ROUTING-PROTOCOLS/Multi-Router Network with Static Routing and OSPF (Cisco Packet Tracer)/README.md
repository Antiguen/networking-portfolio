# Multi-Router Network with Static Routing and OSPF
**Tool:** Cisco Packet Tracer

## 📌 Overview
This project demonstrates the design and configuration of a multi-router network using both static routing and the OSPF dynamic routing protocol. The objective is to understand how routers exchange routing information and enable end-to-end communication across multiple networks.

---

## 🎯 Project Objectives
- Build a multi-router network topology
- Configure and verify static routing
- Implement OSPF for dynamic routing
- Compare static routing with OSPF
- Verify routing using connectivity tests

---

## 🧱 Network Topology
The topology consists of three routers connected in series, each with its own LAN and end devices.


---

## 🔧 Technologies & Concepts Used
- Static Routing
- OSPF (Open Shortest Path First)
- Multi-router IP addressing
- Routing tables and neighbor relationships
- Cisco IOS CLI

---

## ⚙️ Configuration Summary

### Interface Configuration
Each router was configured with LAN and WAN interfaces using appropriate IP addressing.


---

### Static Routing
Static routes were manually configured to enable communication between non-directly connected networks.

*(Used for learning and comparison purposes.)*

---

### OSPF Configuration
OSPF was configured using a single backbone area (Area 0). Routers dynamically learned routes and formed neighbor relationships automatically.


---

## ✅ Testing & Verification
- OSPF neighbor relationships verified in FULL state
- Routing tables populated dynamically via OSPF
- Successful end-to-end connectivity between all PCs


---

## 🧠 Key Learning Outcomes
- Understanding how routing works across multiple routers
- Difference between static and dynamic routing
- Practical OSPF configuration and verification
- Improved troubleshooting and verification skills

---

## 🚀 Future Improvements
- Implement multi-area OSPF
- Add route summarization
- Combine routing with ACL-based security

---


