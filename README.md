Enterprise Network Design & Implementation

Project Overview

This project demonstrates the design and implementation of an enterprise network using Cisco Packet Tracer.

The network includes 26 PCs distributed across three departments, three switches, one router, and one server.

Network Departments

Department| VLAN ID| Network| Number of PCs
Management| 10| 192.168.10.0/24| 6
Sales| 20| 192.168.20.0/24| 12
IT| 30| 192.168.30.0/24| 8

Network Devices

- 1 Cisco 2911 Router
- 3 Cisco 2960 Switches
- 26 PCs
- 1 Server

Technologies Implemented

- VLAN Configuration
- Access Ports and Trunk Links
- Inter-VLAN Routing (Router-on-a-Stick)
- DHCP Configuration
- DNS Configuration
- Web Server (HTTP)
- Extended Access Control Lists (ACL)

Security Policy

Source| Destination| Permission
Sales| Management| Denied
Sales| IT Devices| Denied
Sales| Company Web Server| Allowed
Management| Other Departments| Allowed

Testing and Verification

The following tests were performed successfully:

- Inter-VLAN communication
- DHCP address assignment
- DNS name resolution
- Company website access
- ACL security restrictions
- Management department access to IT

Screenshots

Project screenshots are included in the repository to demonstrate:

- Network Topology
- VLAN Configuration
- Trunk Configuration
- ACL Security Rules
- Inter-VLAN Connectivity
- Blocked Access Test
- Web Server Test

Project File

The Cisco Packet Tracer project file (".pkt") is included in this repository.

Note: This is a simulated network environment created using Cisco Packet Tracer.