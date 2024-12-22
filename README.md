# Company Network Infrastructure Design

## Overview
This project involves designing and implementing a network infrastructure for a medium-sized company with three departments: HR, IT, and Sales. The network design focuses on creating logical separation between each department using VLANs and efficient IP addressing through subnetting. The goal is to ensure secure and controlled inter-department communication, optimize network performance, and provide scalability for future growth.

## Technologies Used
- Subnetting
- VLAN (802.1Q tagging)
- Cisco Packet Tracer
- Layer 3 Routing (Inter-VLAN Routing)
- Access Control Lists (ACLs)

## Objectives
- Design a network with VLANs for each department to separate traffic.
- Assign IP addressing efficiently using subnetting.
- Configure inter-VLAN routing to allow controlled communication between departments.
- Apply ACLs to enforce security policies for inter-department traffic.
- Create a scalable solution for future department additions.

## Network Topology
The network is segmented into three main VLANs:
- **VLAN 10**: HR Department
- **VLAN 20**: IT Department
- **VLAN 30**: Sales Department

Each department has its own network and can communicate with other departments through controlled routing.

## Files
- **design_document.md**: A detailed description of the network design, including subnetting, VLAN configuration, and routing.
- **network_infrastructure.pkt**: Cisco Packet Tracer file with network configuration.
- **network_diagram.png**: Network topology diagram.
