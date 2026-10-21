# Networking Portfolio

 This repo holds my hands-on networking labs, each with configs, verification output, and notes on what I learned. 

## Projects

| # | Project | Tools | Result |
|---|---|---|---|
| 1 | [Enterprise network: VLANs, inter-VLAN routing, DHCP, PAT](project-01-enterprise-network/) | Packet Tracer | Three VLANs routed through one router, with PAT to a simulated ISP. Includes a NAT debugging write-up. |
| 2 | [Multi-router network: static routing and OSPF](project-02-routing-protocols/) | Packet Tracer | Three routers in OSPF area 0, all neighbors in FULL state, end-to-end connectivity verified. |
| 3 | [Network security with ACLs](project-03-network-security-acl/) | Packet Tracer | Extended ACL blocking the Students VLAN from the server network while HR and IT are allowed. |
| - | [INSA cloud computing internship](insa-internship/) | OpenStack, Proxmox | High-level summaries of a Skyline-Keystone integration and a 5-node Proxmox cluster. |

## Skills demonstrated

- VLANs, 802.1Q trunking, router-on-a-stick
- DHCP, PAT, static and default routing
- OSPF (single area)
- Extended ACLs
- Verifying and troubleshooting with `show` commands

## In progress

- Troubleshooting casebook (broken-network scenarios with diagnosis and fixes)
- Multi-site network with multi-area OSPF
- Network automation with Python
