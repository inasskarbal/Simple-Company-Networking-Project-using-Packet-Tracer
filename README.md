# Simple-Company-Networking-Project-using-Packet-Tracer

## Overview

This project demonstrates the design and implementation of a small company network using Cisco Packet Tracer. The network was built based on a real-world scenario where a company requires a secure and scalable network infrastructure for a new branch office.
The implementation includes VLAN segmentation, subnetting, DHCP configuration, wireless connectivity, and inter-VLAN communication.

## Project Objectives

- Design a branch office network using Cisco devices.
- Separate departments using VLANs.
- Implement IPv4 subnetting.
- Configure DHCP for automatic IP assignment.
- Provide wireless connectivity for each department.
- Enable communication between all departments.

## Network Requirements

- One Router
- One Switch
- Three Departments:
  - Admin/IT
  - Finance/HR
  - Customer Service/Reception
- Separate VLAN for each department
- Wireless Access Point for every department
- Automatic IPv4 addressing using DHCP
- Full communication between all VLANs

## Network Topology

The network consists of:

- Cisco 2911 Router
- Cisco 2960 Switch
- 3 PCs
- 3 Printers
- 3 Wireless Access Points
Each department is connected to its own VLAN and subnet.

## IP Addressing

Base Network:

192.168.1.0/24

Subnetting:

| Department | VLAN | Network |
|------------|------|----------------|
| Admin/IT | VLAN 1 | 192.168.1.0/26 |
| Finance/HR | VLAN 2 | 192.168.1.64/26 |
| Customer Service | VLAN 3 | 192.168.1.128/26 |

## Features Implemented

- VLAN configuration
- Router
- IPv4 subnetting
- DHCP configuration
- Wireless connectivity
- Inter-VLAN routing
- connectivity testing

## Technologies Used

- Cisco Packet Tracer
- VLANs
- DHCP
- Router
- IPv4 Subnetting

## Learning Outcomes

Through this project, I learned how to:

- Design a small enterprise network
- Configure VLANs on Cisco switches
- the difference between configure vlan in mode access and mode trunk
- Implement Router
- Configure DHCP services
- Apply IPv4 subnetting
- Verify network connectivity 
