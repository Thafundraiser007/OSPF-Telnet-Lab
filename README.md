# OSPF-Telnet-Lab
Hybrid Network topology with OSPF and Telnet configuration


This project is a GNS3-based network lab designed to demonstrate a hybrid topology combining a Hub-and-Spoke design with a Ring topology. The lab focuses on routing, redundancy, and network services configuration using enterprise-style practices.

The goal of this lab is to build a realistic multi-router environment and validate connectivity, routing protocols, and remote management access.

Topology Design
The network consists of:
-1 Core Router (Hub)
-Multiple Edge Routers (Spokes)
-Edge routers are interconnected to form a ring structure
-Core router connects directly to all edge routers
This creates a hybrid Hub-and-Spoke + Ring topology, providing both centralized routing and redundant paths.

Tools & Technologies
-GNS3
-Cisco IOS Routers
-IPv4 Static Addressing
-OSPF (Open Shortest Path First)
-SSH
-Telnet

Features Implemented
1. Hybrid Topology Design
-Hub-and-spoke structure for centralized routing
-Ring topology for redundancy between edge routers
-Additional router interfaces added for expanded connectivity

3. IP Addressing
-Static IP addressing configured on all router interfaces
-Proper segmentation for point-to-point links

5. Routing
-OSPF configured across all routers
-Full network adjacency established
-Dynamic route exchange verified

6. Network Verification
-Connectivity tested using ping between all routers
-Routing tables validated for correct path selection
-Failover paths tested via ring redundancy

7. Remote Management
-Telnet configured for basic remote access
-SSH configured for secure management access
-Enable secret and device security settings applied
-Verification & Testing

The following tests were successfully completed:
-Ping between all routers (end-to-end connectivity)
-OSPF neighbor adjacency confirmation
-Route propagation across all network segments
-Remote login via Telnet and SSH
-Redundancy validation through alternative ring paths
-Key Learning Outcomes
-Designing hybrid network topologies in a simulated environment
-Implementing and troubleshooting OSPF in multi-router setups
-Understanding redundancy using ring structures
-Configuring secure and legacy remote access methods
-Practical experience with enterprise-style routing design

Files Included
-GNS3 project file (.gns3)
-Network topology screenshots
-Configuration snapshots (optional)

Author
Jamill Naipao
Network & Server Administration (Advanced Professional Diploma Graduate)
Port Moresby, Papua New Guinea
