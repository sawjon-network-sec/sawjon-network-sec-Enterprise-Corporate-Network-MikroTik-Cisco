
# Enterprise Corporate Network Infrastructure using MikroTik & Cisco

## Project Overview

This project demonstrates the design, implementation, and validation of an enterprise-style corporate network built in **EVE-NG** using **MikroTik RouterOS v7** and **Cisco Layer 2 Switching** technologies.

The lab simulates a real-world enterprise environment with a headquarters, multiple branch offices, dual ISP connectivity, secure VPN communication, VLAN segmentation, and enterprise switching. The primary objective is to strengthen practical skills in enterprise routing, switching, network security, and troubleshooting.

---

# Objectives

* Design a scalable enterprise campus network.
* Implement redundant Internet connectivity using BGP.
* Provide secure communication between headquarters and branch offices.
* Deploy VLAN-based network segmentation.
* Configure enterprise Layer 2 switching.
* Implement secure firewall policies and NAT.
* Improve troubleshooting and network documentation skills.

---

# Lab Environment

| Component          | Technology                          |
| ------------------ | ----------------------------------- |
| Network Emulator   | EVE-NG                              |
| Router Platform    | MikroTik RouterOS v7                |
| Switching Platform | Cisco IOS Layer 2 Switch            |
| Routing            | BGP, Static Routing                 |
| VPN                | IPsec Site-to-Site VPN, GRE Tunnel  |
| Layer 2            | VLAN, Trunking, EtherChannel (LACP) |

---

# Network Topology

The enterprise network consists of:

* Headquarters (HQ)
* Dual Internet Service Providers
* MikroTik Core Router
* MikroTik Access Router
* Cisco Layer 2 Core Switch
* Multiple Access Switches
* Branch Office 1
* Branch Office 2

### Connectivity

* Dual ISP connectivity using eBGP
* Headquarters connected to Cisco switching infrastructure
* Branch Office 1 connected through an IPsec Site-to-Site VPN
* Branch Office 2 connected through a GRE Tunnel
* Multiple access switches connected using LACP EtherChannel

---

# Technologies Implemented

## Routing

* BGP (eBGP)
* Static Routing
* Route Filtering
* IP Address Management

## Switching

* IEEE 802.1Q VLAN
* VLAN Trunking
* Access Ports
* Layer 2 Switching
* EtherChannel (LACP)
* Multi-floor Campus Switching

## Network Services

* DHCP Server
* NAT
* Firewall Filter Rules

## VPN

* IPsec Site-to-Site VPN
* GRE Tunnel

---

# Enterprise Features

* Dual ISP Redundancy
* Enterprise VLAN Segmentation
* Secure Branch Connectivity
* Layer 2 Campus Switching
* Centralized DHCP Services
* Firewall Security Policies
* NAT Configuration
* Link Aggregation (LACP)
* Route Filtering
* Enterprise Troubleshooting

---

# Project Directory

```
Enterprise-Corporate-Network/
│
├── Topology/
├── Configurations/
├── Routing/
├── VPN/
├── VLAN/
├── DHCP/
├── Firewall/
├── NAT/
├── LACP/
├── Verification/
├── Troubleshooting/
└── Documents/
```

---

# Verification

The project has been validated through:

* BGP Neighbor Status
* Successful VPN Connectivity
* GRE Tunnel Verification
* VLAN Communication
* DHCP Address Allocation
* NAT Translation
* Firewall Rule Testing
* Routing Table Verification
* Ping Tests
* Traceroute Tests
* Link Aggregation Verification

Screenshots and verification results are available in the **Verification** folder.

---

# Skills Demonstrated

* Enterprise Network Design
* MikroTik RouterOS v7 Administration
* Cisco Switching
* Enterprise Routing
* BGP Configuration
* VLAN Design
* Inter-VLAN Routing
* EtherChannel (LACP)
* DHCP Services
* NAT Configuration
* Firewall Policies
* IPsec VPN Deployment
* GRE Tunnel Configuration
* Route Filtering
* Network Troubleshooting
* Technical Documentation

---

# Lessons Learned

During this project I gained practical experience in:

* Designing an enterprise network from scratch.
* Integrating MikroTik routing with Cisco switching.
* Deploying secure VPN connections between remote offices.
* Configuring enterprise Layer 2 switching.
* Implementing redundant WAN connectivity using BGP.
* Troubleshooting routing, switching, and VPN issues.
* Building structured documentation for real-world network deployments.

---

# Future Improvements

Future versions of this lab may include:

* OSPF Multi-Area Routing
* IS-IS Routing
* VRRP High Availability
* MPLS
* FortiGate Firewall Integration
* RADIUS Authentication
* Network Monitoring (SNMP)
* Syslog Server
* NetFlow Traffic Analysis
* IPv6 Deployment
* Zero Trust Network Architecture

---

# Repository Contents

* Enterprise Network Topology
* Router Configurations
* Cisco Switch Configurations
* VPN Configurations
* Routing Configurations
* Verification Screenshots
* Troubleshooting Notes
* Project Documentation

---

# Author

**SA WJ ON**

Network & Cloud Security Engineer

* Enterprise Networking
* MikroTik
* Cisco
* Network Security
* Cloud Networking

---

## Acknowledgement

This project was developed for educational purposes to strengthen hands-on experience with enterprise networking technologies and to demonstrate practical skills in routing, switching, VPN implementation, and enterprise network troubleshooting.
