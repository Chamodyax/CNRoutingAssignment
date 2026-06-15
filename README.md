# CNRoutingAssignment
**Cisco Packet Tracer Routing Assignment** **Author:** Chamodya Pasindu Palihawadana (NSBM Green University)

## 📖 Project Overview
This repository contains the completed Cisco Packet Tracer network topology files for my university routing assignment. The project demonstrates the practical configuration of basic device security, static routing, and dynamic routing protocols (RIPv2 & EIGRP) across multiple simulated branch networks.

## 🗂️ Files Included

### 1. `Task1_BasicConfig.pkt`
* **Topic:** Basic Router Configuration & Security
* **Description:** Demonstrates initial device setup on a Cisco 2911 router. Includes configuring a standardized hostname (`KandyNSBM_39321`), securing the console port with a password, and enabling user access verification.

### 2. `Task2_StaticRouting.pkt`
* **Topic:** Static Routing
* **Description:** A triangular topology connecting three distinct Local Area Networks (`192.168.1.0/24`, `192.168.2.0/24`, and `192.168.3.0/24`) via three routers (BusinessRouter, ComputingRouter, ScienceRouter). It demonstrates manual routing table configurations using absolute next-hop IP addresses to establish full end-to-end connectivity.

### 3. `Task3_DynamicRouting.pkt`
* **Topic:** Dynamic Routing (RIPv2 & EIGRP)
* **Description:** A linear topology featuring three routers (KandyNSBM, ColomboNSBM, GalleNSBM). The file demonstrates how to initially share routing tables dynamically using **RIPv2** (including disabling auto-summarization). It also covers transitioning the network to the faster, more efficient **EIGRP** protocol under Autonomous System (AS) 100.

## 🛠️ Tools Used
* **Cisco Packet Tracer**
* **Routing Protocols:** Static, RIPv2, EIGRP 

## 🚀 How to Run
1. Download or clone this repository.
2. Ensure you have **Cisco Packet Tracer** installed on your machine.
3. Open any of the `.pkt` files to view the network topology.
4. Access the **CLI** tab on the routers to view the routing tables (`show ip route`) or use the PCs to run ICMP `ping` commands to test connectivity across the networks.
