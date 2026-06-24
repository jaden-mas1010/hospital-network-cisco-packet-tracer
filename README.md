# Secure Smart Hospital Network — Cisco Packet Tracer

**Author:** Jaden Julius Mascarenhas  
**Student ID:** K2462387  
**University:** Kingston University London  
**Programme:** MSc Information and Network Security  

## Overview
This project presents the design and implementation of a secure smart 
hospital network using Cisco Packet Tracer. The network demonstrates 
SDN principles including logical segmentation, centralised policy 
enforcement, and programmable traffic control — without a full SDN 
controller implementation.

## Files
- `hospital_network.pkt` — Cisco Packet Tracer simulation file
- `hospital_network_paper.docx` — Full IEEE-style tutorial paper
- `hospital_network_demo.mp4` — Video walkthrough of the implementation

## Network Design
- **VLAN 10** — IoT devices
- **VLAN 20** — Admin systems
- **VLAN 30** — Guest users
- **VLAN 40** — On-premise server

## Key Concepts Demonstrated
- VLAN segmentation and port assignment
- Inter-VLAN routing
- Access Control Lists (ACLs) — principle of least privilege
- Cloud gateway integration
- SDN principles (logical segmentation, centralised policy enforcement)

## Tools Used
- Cisco Packet Tracer
- CLI configuration (switch and router)

## How to Open
1. Install Cisco Packet Tracer (free via Cisco NetAcad)
2. Open `hospital_network.pkt`
3. Explore the topology, VLANs, and ACL configurations
