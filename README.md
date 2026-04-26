# RIP vs OSPF Routing Protocol Comparison
Performance comparison of RIP vs OSPF routing protocols using Cisco Packet Tracer. Includes network topology, routing tables, convergence analysis, and failover testing.

**Course:** Computer Networks (CN) | FAST NUCES Lahore
**Developed by:** Sehrish Ejaz

## Overview
Performance comparison of RIP (Distance Vector) and OSPF (Link State) routing protocols
implemented and tested on Cisco Packet Tracer.

## Network Topology
- 3 Routers (R1, R2, R3)
- R1 uses RIP | R2 acts as redistribution point | R3 uses OSPF
- Web Server, File Server, and multiple PCs across subnets

## Key Findings
| Feature | RIP | OSPF |
|---------|-----|------|
| Convergence Time | ~45 seconds | ~5 seconds |
| Metric | Hop Count | Bandwidth (Cost) |
| Scalability | Small networks | Large/Enterprise networks |
| Configuration | Simple | Complex but powerful |

## Tests Performed
- Routing table verification across R1, R2, R3
- Ping tests across subnets
- Failover scenario (R1-R2 link down → rerouted via R3)
- Protocol redistribution at R2

## Tools Used
- Cisco Packet Tracer
- CLI commands: show ip route, show ip protocols, show ip ospf neighbor

## Files
- `CN_PROJECT.pkt` — Cisco Packet Tracer simulation file
