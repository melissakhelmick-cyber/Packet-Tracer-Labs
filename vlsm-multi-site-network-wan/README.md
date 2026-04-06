VLSM Multi-Site Network with WAN Connectivity Lab

Overview

This lab demonstrates the design and implementation of a multi-site enterprise network using Variable Length Subnet Masking (VLSM). Two routers are connected via a WAN serial link, with multiple LAN segments on each side supporting different host requirements.

Objectives

* Design and implement VLSM subnetting for multiple networks
* Configure router interfaces for LAN and WAN connectivity
* Establish communication between two network sites
* Verify end-to-end connectivity across all subnets

Network Design

* Address Space: 192.168.0.0/16
* WAN Link: 10.0.0.0/30

LAN Segments:

* Network A: 100 hosts (/25)
* Network B: 50 hosts (/26)
* Network C: 75 hosts (/25)
* Network D: 100 hosts (/25)
* Network E: 50 hosts (/26)
* Network F: 25 hosts (/27)

Technologies Used

* Cisco Packet Tracer
* IPv4 Addressing
* VLSM Subnetting
* Serial WAN Configuration
* Static Routing 

Configuration Summary

* Allocated subnets based on host requirements using VLSM
* Configured LAN interfaces on both routers
* Established WAN connectivity using serial interfaces (/30 network)
* Implemented routing to allow communication between all networks
* Verified connectivity using ping and CLI commands

Key Commands

show ip interface brief  
show running-config  
show ip route  
ping  

Verification

* Devices within each LAN successfully communicate ✅
* Cross-network communication between all subnets is functional ✅
* WAN link between routers is operational ✅

What I Learned

* How to design scalable IP addressing schemes using VLSM
* How WAN links connect geographically separated networks
* How routing enables communication across multiple LAN segments
* The importance of accurate subnet planning in network design

Real-World Relevance

This lab simulates how organizations connect multiple locations (such as branch offices) using WAN links, while efficiently allocating IP space and maintaining network segmentation.

