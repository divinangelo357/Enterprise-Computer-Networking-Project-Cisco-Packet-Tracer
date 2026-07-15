# Computer Networking Project

This project was developed using Cisco Packet Tracer 8.2.1 to simulate a secure enterprise network connecting two branch offices through a WAN infrastructure. The network demonstrates several networking concepts commonly used in real-world environments, including routing, switching, VLAN segmentation, network services, wireless management, and security.

The topology consists of 8 Cisco routers, 8 switches, 6 PCs, multiple servers, wireless controllers, an ASA 5506-X firewall, shared printers, and a simulated cloud that interconnects both sites. Each branch is divided into multiple VLANs representing different departments, with Inter-VLAN routing allowing communication while maintaining proper network segmentation.

Several enterprise services are implemented throughout the network, including DHCP for automatic IP address assignment, DNS for name resolution, FTP/TFTP for file transfer and device configuration, an Email server for internal communication, and a SYSLOG server for centralized logging and monitoring.

To improve network organization and scalability, VTP (VLAN Trunking Protocol) is used to manage VLAN information across switches. The two branch offices communicate through a site-to-site tunnel over the WAN, while the ASA firewall provides perimeter security by controlling network traffic between internal and external networks. Wireless connectivity is managed through Cisco Wireless LAN Controllers (WLCs), simulating an enterprise wireless infrastructure.

This project was created as a practical exercise to strengthen skills in enterprise network design and Cisco device configuration. It combines multiple networking technologies into a single topology that reflects many of the concepts covered in CCNA-level networking courses.

# Technologies Used

* Cisco Packet Tracer 8.2.1
* Static Routing
* VLANs and Inter-VLAN Routing
* VTP (VLAN Trunking Protocol)
* Site-to-Site Tunnel
* DHCP
* DNS
* FTP & TFTP
* Email Server
* SYSLOG Server
* ASA 5506-X Firewall
* Wireless LAN Controllers (WLC)
* WAN Serial Connections

# Getting Started

1. Download and install Cisco Packet Tracer 8.2.1 (or a newer version).
2. Clone or download this repository.
3. Open the `.pkt` file in Packet Tracer.
4. Explore the topology, review the configurations, and test connectivity between devices.

# Purpose

The purpose of this project is to demonstrate the implementation of a complete enterprise network using Cisco technologies while practicing routing, switching, network services, security, and WAN connectivity in a simulated environment.
