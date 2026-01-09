# Project 3 — Network Security with Access Control Lists (ACLs)

## Overview
This project demonstrates how Access Control Lists (ACLs) are used to secure an enterprise network by controlling which departments can access sensitive resources. The network is segmented using VLANs, and security policies are enforced at the router level.

This design reflects how real organizations protect critical systems from unauthorized users.

---

## Network Architecture

The network consists of:
- One router using router-on-a-stick configuration
- One Layer 2 switch
- Three departmental VLANs
- One protected server network

### VLAN Structure

VLAN 10 — HR Department — 192.168.10.0/24  
VLAN 20 — Students — 192.168.20.0/24  
VLAN 30 — IT Department — 192.168.30.0/24  

### Server Network
The server is located in the 192.168.100.0/24 network and represents a sensitive company system.

---

## Security Policy

The company enforces the following access rules:

HR Department — Allowed to access the server  
IT Department — Allowed to access the server  
Students — Blocked from accessing the server  

This ensures that confidential company data is protected and only accessible to authorized users.

---

## Implementation Summary

- The network was segmented into VLANs based on departments.
- Inter-VLAN routing was configured so different departments could communicate through the router.
- An extended Access Control List was implemented to filter traffic based on both source and destination networks.
- The security policy was enforced by applying the ACL at the appropriate router interface, close to the traffic source.
- Traffic from the Students VLAN to the server network was blocked, while HR and IT were permitted.

---

## Testing and Verification

Connectivity tests were performed from each department’s PC to the server.

Results:
- HR PC → Server: Successful
- IT PC → Server: Successful
- Students PC → Server: Blocked

Screenshots included in this project show the successful and failed tests, as well as the network topology and router configuration.

---

## What This Project Demonstrates

- VLAN-based network segmentation  
- Inter-VLAN routing using a single router  
- Network security using Access Control Lists  
- Role-based access control  
- Enterprise-style network design and protection  
- Troubleshooting and verification  

---

## Files Included

- Cisco Packet Tracer network file  
- Network topology diagram  
- Router security configuration screenshots  
- Ping test results showing allowed and blocked traffic  

---


