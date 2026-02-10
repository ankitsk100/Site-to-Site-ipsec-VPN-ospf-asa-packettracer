# Site-to-Site IPsec VPN with OSPF – Project Report

## Overview
This project demonstrates a Site-to-Site IPsec VPN between a Headquarters (HQ) network and a Branch network using Cisco ASA 5506-X firewalls. OSPF is used for dynamic routing across routers and firewalls.

## Network Details
- HQ LAN: 192.168.1.0/24
- Branch LAN: 192.168.2.0/24
- WAN Links:
  - 100.50.10.0/30 (HQ ↔ ISP)
  - 100.50.10.4/30 (ISP ↔ Branch)

## Technologies Used
- Cisco ASA 5506-X
- OSPF (Area 0)
- IPsec VPN (IKEv1)
- NAT and ACLs
- Cisco Packet Tracer

## Result
Secure communication between HQ and Branch LANs was successfully achieved and verified.
