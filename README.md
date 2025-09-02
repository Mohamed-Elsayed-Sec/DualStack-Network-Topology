# EDUStack Network Topology

## 📌 Project Overview

This project demonstrates a dual-stack network topology using both IPv4 and IPv6 protocols. It includes multiple routers, subnets, and end devices, with connectivity tests performed using `ping6` and `traceroute6`.

## 🎯 Objectives

- Design and document a structured network topology
- Implement IPv6 addressing using `dhclient` and `radvd`
- Validate connectivity between devices using ICMPv6 tools

## 🧠 Topology Highlights

- Dual-stack implementation (IPv4 & IPv6)
- End-to-end testing between PC1 and PC2
- Visual diagrams created using Miro

## 🗺️ Mapping Diagrams

| Diagram | Description |
|--------|-------------|
| `topology-ipv4.jpg` | IPv4 network layout |
| `topology-ipv6.jpg` | IPv6 network layout |
| `topology-ipv4-ipv6.jpg` | Combined dual-stack topology |

## 📊 Connectivity Results

### IPv6 Addressing

- **PC1**: Configured via `dhclient`  
- **PC2**: Configured via `radvd`  
- Documentation prefix used: `2001:db8::/64`

### ICMPv6 Tests

- **Ping6**: PC1 ↔ PC2  
- **Traceroute6**: PC1 ↔ PC2

## 👤 Author

**Mohamed Elsayed Ahmed Youssef**  
This project is part of my technical journey into professional networking and cybersecurity. Feedback is welcome!
