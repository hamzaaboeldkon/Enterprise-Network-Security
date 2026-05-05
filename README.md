# Enterprise Network Security Project

## 📖 Overview
This project demonstrates the design and simulation of a secure enterprise network using Cisco Packet Tracer.  
The network is segmented into multiple zones to enhance security, reduce attack surface, and simulate real-world enterprise environments.

## 🧠 Key Features
- Multi-zone network architecture
- OSPF dynamic routing
- Access Control Lists (ACLs)
- Zone-Based Firewall (ZBF)
- VLAN segmentation & Layer 2 security
- AAA (RADIUS & TACACS+)
- SSH secure remote access
- Syslog centralized logging
- Port Security & unused ports disabled
- DMZ implementation for public servers
- NTP Server
- Web Server

## 🏗️ Network Design
- Each zone uses a dedicated subnet (VLSM)
- /30 subnets for inter-router links
- DMZ isolates public-facing services
- Internal network protected by firewall policies

## 🔐 Security Implementation
- Port Security (MAC binding)
- ACLs to control traffic flow
- Secure VTY access (SSH only)
- AAA for authentication and authorization
- Logging using Syslog server

## 🔐 Network Access (Lab Credentials Only)
> Note: These credentials are for lab/simulation purposes only.

- Console: admin  
- Enable: admin  
- SSH Username: hamza
- SSH Password: 553324
- Telnet Password: 553324 

## 🛠️ Tools & Technologies
- Cisco Packet Tracer
- OSPF
- ACL
- ZBF
- VLAN
- AAA (RADIUS & TACACS+)
- SSH
- Syslog
- Subnetting (VLSM)

## 📂 Project Files
- network.pkt
- documentation.pdf
- screenshots/


## 🚀 Future Improvements
- Add IDS/IPS simulation
- Perform attack & defense testing scenarios
