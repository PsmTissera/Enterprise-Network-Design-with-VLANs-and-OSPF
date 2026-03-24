# Enterprise Network Design with VLAN Segmentation and OSPF (Cisco Packet Tracer)

## Overview
This project demonstrates the design and implementation of a simulated enterprise network using Cisco Packet Tracer. The network is structured using a hierarchical model with a core multilayer switch, access switches, and routers. The main goal of the project is to implement VLAN segmentation, inter-VLAN routing, trunking, and dynamic routing using OSPF.

The network simulates different organizational departments and enables secure and efficient communication between them.

---

## Network Architecture
The network topology consists of:

- 1 Core Multilayer Switch (Cisco Catalyst 3560)
- 4 Access Switches (Cisco Catalyst 2960)
- 2 Routers
- Multiple PCs representing different departments

Departments are separated using VLANs and connected through a multilayer switch that performs inter-VLAN routing. The routers simulate WAN connectivity and exchange routes dynamically using OSPF.

---

## VLAN Structure

| VLAN ID | Department |
|-------|-------------|
| 10 | HR |
| 20 | Finance |
| 30 | IT |
| 40 | Sales |

Each department is connected to a dedicated access switch and assigned to its respective VLAN.

---

## Key Features

- VLAN segmentation for department isolation
- Inter-VLAN routing using a Layer 3 switch
- 802.1Q trunking between access and core switches
- WAN connectivity between routers using serial interfaces
- Dynamic routing using OSPF
- End-to-end connectivity verification using ICMP (ping)

---

## Technologies Used

- Cisco Packet Tracer
- VLAN Configuration
- Inter-VLAN Routing
- OSPF Dynamic Routing
- 802.1Q Trunking
- Static and Dynamic IP Addressing

---

## Connectivity Testing

End-to-end connectivity between different VLANs and networks was tested using ICMP ping to verify that routing and VLAN configurations were functioning correctly.

---

## Project Topology

Screenshots of the network topology and configuration outputs are included in this repository:

- Network Topology
- VLAN Configuration
- Trunk Links
- Routing Table
- Connectivity Tests

---

## Learning Outcomes

This project helped develop practical understanding of:

- Network segmentation using VLANs
- Layer 3 switching and routing
- Enterprise network design concepts
- Dynamic routing protocols (OSPF)
- Troubleshooting connectivity issues in simulated environments

---

## Author

Sandupama Tissera  
BSc (Hons) Computer Networks  
NSBM Green University
