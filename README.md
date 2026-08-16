# Cisco Networking Fundamentals Lab
Documentation attached as PDF

A hands-on Cisco Packet Tracer home lab covering inter-VLAN routing, switching, dynamic routing, link aggregation, and IPv6 troubleshooting.

## Overview

This project documents a series of networking labs completed using Cisco Packet Tracer.

The goal was to move beyond simply memorising Cisco IOS commands and develop a practical understanding of how enterprise networking technologies work, how they interact, and how to troubleshoot connectivity problems systematically.

## Labs Covered

### 1. Router-on-a-Stick

Configured inter-VLAN routing using router sub-interfaces and IEEE 802.1Q encapsulation, allowing devices in different VLANs to communicate.

### 2. Rapid Spanning Tree Protocol (RSTP)

Configured Rapid PVST+, root bridge priorities, PortFast, and BPDU Guard to prevent Layer 2 loops, improve convergence, and protect access ports.

### 3. EtherChannel

Configured LACP to combine multiple physical Ethernet links into a single logical Port Channel, providing increased bandwidth and redundancy.

### 4. EIGRP Dynamic Routing

Configured EIGRP across a multi-router topology so routers could dynamically exchange routing information and automatically adapt to network failures.

### 5. OSPF Dynamic Routing

Configured OSPF and examined neighbour formation, Link State Databases, routing tables, and shortest-path calculations.

### 6. IPv6 Troubleshooting

Developed a structured approach to troubleshooting IPv6 connectivity using interface verification, routing tables, IPv6 ping and traceroute, Neighbour Discovery, CDP, and debugging tools.

## Technologies

- Cisco Packet Tracer
- Cisco IOS
- IPv4
- IPv6
- VLANs
- Inter-VLAN Routing
- 802.1Q
- RSTP / Rapid PVST+
- PortFast
- BPDU Guard
- EtherChannel
- LACP
- EIGRP
- OSPF
- IPv6 Neighbor Discovery

## Key Skills Demonstrated

- Cisco IOS configuration
- Inter-VLAN routing
- Layer 2 switching
- Spanning Tree configuration
- Link aggregation
- Dynamic routing
- IPv4 and IPv6 troubleshooting
- Connectivity testing
- Network verification
- Root-cause analysis

## Troubleshooting Approach

A major focus of this project was learning to troubleshoot systematically rather than randomly changing configurations.

The approach was:

1. Identify the symptoms.
2. Gather evidence.
3. Verify interface status and addressing.
4. Check Layer 2 connectivity.
5. Examine routing information.
6. Verify neighbour relationships.
7. Test connectivity.
8. Use debugging tools when necessary.
9. Identify and correct the root cause.

The core principle I developed throughout the labs was:

> **Never guess. Always verify.**

## Verification Commands

Some of the Cisco IOS commands used throughout the labs included:

```text
show ip interface brief
show running-config
show ip route
show spanning-tree
show etherchannel summary
show ip eigrp neighbors
show ip eigrp topology
show ip ospf neighbor
show ip ospf interface
show ipv6 interface brief
show ipv6 route
show ipv6 neighbors
show cdp neighbors detail
ping
traceroute
ping ipv6
traceroute ipv6
