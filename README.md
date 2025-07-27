# Basic-Network-Topology-on-Cisco-Packet-Tracer
This project demonstrates a basic network topology built using Cisco Packet Tracer.
The simulation includes:
4 PCs (2 per subnet)
2 Switches (one per LAN)
1 Router (to route between the two networks)

Each LAN is configured with its own IP subnet, and routing between them is established using static IP addressing on the router interfaces.

NETWORK CONFIGURATION: 
LAN 1 (192.168.1.0/24):
Devices: PC0, PC1
Default Gateway: 192.168.1.1

LAN 2 (192.168.2.0/24):
Devices: PC2, PC3
Default Gateway: 192.168.2.1

Router interfaces:
fa0/0: 192.168.1.1
fa0/1: 192.168.2.1

Features: 
Static IP addressing
Basic router interface configuration
End-to-end connectivity testing using ping
Simulation of two connected LANs across a router
