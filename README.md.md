# Enterprise LAN Foundation — Week 1

## Project Overview

This project is part of my 6-week networking challenge focused on building real-world networking and troubleshooting skills.

In Week 1, I designed and configured a small enterprise LAN using Cisco Packet Tracer. The project focuses on subnetting, DHCP, static routing, SSH hardening, and network validation.

---

## Topology

![Topology](diagrams/topology.png)

---

## Network Segments

| Department | Subnet | Hosts |
|---|---|---|
| Sales | 10.10.10.0/26 | 50 |
| IT | 10.10.10.64/27 | 25 |
| HR | 10.10.10.96/28 | 12 |
| Management | 10.10.10.112/29 | 6 |

---

## Technologies Used

- Cisco Packet Tracer
- IPv4 & VLSM
- DHCP
- Static Routing
- SSH
- Cisco IOS CLI

---

## Security Configurations

- SSH enabled for remote management
- Enable secret configured
- Service password encryption enabled
- Banner MOTD configured
- Unused ports administratively shutdown

---

## Validation

- DHCP successfully assigns IP addresses
- Inter-network communication verified
- SSH access tested successfully
- Routing table validated

---

## Project Structure

```bash
enterprise-lan-foundation/
│
├── configs/
├── diagrams/
├── documentation/
├── captures/
└── README.md
