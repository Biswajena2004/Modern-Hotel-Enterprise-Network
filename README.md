<img width="1442" height="660" alt="Topology" src="https://github.com/user-attachments/assets/2182ae5d-aae8-42a0-93a9-05b40cf9b414" />
# Modern-Hotel-Enterprise-Network
Designed and implemented a 3-floor enterprise hotel network in Cisco Packet Tracer featuring VLAN segmentation, inter-VLAN routing, OSPF, DHCP, SSH, Serial DCE, wireless networking, port security, sticky MAC, printers, and end-to-end connectivity testing across 8 departments.


# 🏨 Vic Modern Hotel – Enterprise Network

A Cisco Packet Tracer project designed and implemented for a three-floor
hotel network with multiple departments.

## 🚀 Project Overview

The network uses 3 Cisco routers and 3 switches to connect departments
across three floors. Each department is configured with a separate VLAN
and IP network for better network segmentation and management.

## 🔧 Technologies Used

- Cisco Packet Tracer
- VLAN & Inter-VLAN Routing
- OSPF Dynamic Routing
- DHCP
- SSH Remote Access
- Port Security
- Wireless Networking
- Serial DCE

## 🌐 VLANs

| VLAN | Department | Network |
|------|------------|---------|
| 10 | IT | 192.168.1.0/24 |
| 20 | Admin | 192.168.2.0/24 |
| 30 | Sales | 192.168.3.0/24 |
| 40 | HR | 192.168.4.0/24 |
| 50 | Finance | 192.168.5.0/24 |
| 60 | Logistics | 192.168.6.0/24 |
| 70 | Store | 192.168.7.0/24 |
| 80 | Reception | 192.168.8.0/24 |

## 🔐 Security & Services

- OSPF for dynamic routing
- DHCP for automatic IP addressing
- SSH for secure router management
- Port Security with Sticky MAC
- Wireless access for laptops and smartphones
- Dedicated printers for departments

## 🧪 Testing

Connectivity is verified using `ping`, `tracert`, OSPF neighbor
verification, DHCP binding checks, and port-security commands.

## 📁 Project File

The Cisco Packet Tracer `.pkt` file contains the complete network
topology and configuration.
