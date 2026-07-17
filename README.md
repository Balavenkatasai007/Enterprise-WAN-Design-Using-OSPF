# Enterprise WAN Design using OSPF

## Project Overview
This project demonstrates the implementation of a four-branch Enterprise WAN using OSPF in Cisco Packet Tracer.

**Objectives:**
- Configure OSPF dynamic routing.
- Verify end-to-end connectivity.
- Simulate a WAN link failure.
- Observe automatic route recalculation and traffic rerouting.

## Tools Used
- Cisco Packet Tracer
- OSPF (Open Shortest Path First)
- IPv4 Addressing
- Serial WAN Links

## Network Details

| Branch | Network |
|---------|----------------|
| HQ | 192.168.10.0/24 |
| Hyderabad | 192.168.20.0/24 |
| Chennai | 192.168.30.0/24 |
| Bangalore | 192.168.40.0/24 |

## Features
- Multi-branch WAN design
- OSPF dynamic routing
- Automatic neighbor discovery
- Route learning
- WAN redundancy
- Link failure recovery

## Verification
- ✔ OSPF neighbor formation
- ✔ Routing table verification
- ✔ End-to-end ping test
- ✔ WAN link failure simulation
- ✔ Automatic traffic rerouting

## Screenshots

### Network Topology
![Network Topology](Screenshots/Network_Topology.png)

### OSPF Neighbor Verification
![OSPF Neighbor Verification](Screenshots/OSPF_Neighbor_Verification.jpg)

### Routing Table Before Link Failure
![Routing Table Before Failure](Screenshots/Routing_Table_Before_Failure.jpg)

### Ping Test Before Link Failure
![Ping Test Before Failure](Screenshots/Ping_Test_Before_Failure.jpg)

### WAN Link Failure Simulation
![WAN Link Failure](Screenshots/WAN_Link_Failure_Simulation.jpg)

### Routing Table After Link Failure
![Routing Table After Failure](Screenshots/Routing_Table_After_Failure.jpg)

### Ping Test After Link Failure
![Ping Test After Failure](Screenshots/Ping_Test_After_Failure.jpg)

## What I Learned
- Configured OSPF on multiple routers.
- Understood how OSPF discovers neighbors and exchanges routes.
- Verified routing using **show ip route** and **show ip ospf neighbor**.
- Simulated a WAN link failure and observed automatic route recalculation.
- Improved my understanding of enterprise WAN design and dynamic routing.

## Files Included
- Enterprise_WAN_OSPF.pkt
- README.md

## Author
**Bala Venkata Sai Dindu**
