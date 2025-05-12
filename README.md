# Bandwidth Management Using Qos  
*Student Name:* Megha Shree V  
*Register No.:* 23BCAR0326 
*Semester:* IV – BCA (IoT Specialization)  
*Course:* 23BCA4VC02 – Network Administration  
*College:* Jain Deemed-to-be University  
*Faculty In-Charge:* Mr. Sahabzada Betab Badar  

# Network Topology Project

## Project Overview

This project represents a network topology using Cisco Packet Tracer. The topology connects two local area networks (LANs) via a central router, which also connects to a server. The main goal is to establish connectivity between the LANs and provide centralized services through the server.

## Network Topology

The network is structured as follows:

* **Router 15 (Central Router):** Acts as the backbone, connecting the two LANs and the server.
* **Router 17 and Router 18:** Connect the respective LANs to the central router.
* **Switches:** Used to connect multiple PCs within each LAN.
* **PCs (PC0, PC1, PC2, PC3, PC4, PC6):** Represent client machines within the network.
* **Server (Server0):** Provides centralized services and connectivity between the LANs.

## Configuration Details

1. **IP Addressing Scheme:**

   * LAN 1 (Router 18): 192.168.1.0/24
   * LAN 2 (Router 17): 192.168.2.0/24
   * Central Router (Router 15): 192.168.3.0/24

2. **Routing Protocol:**

   * Static routing or OSPF to be configured for inter-LAN communication.

3. **Server Configuration:**

   * IP Address: 192.168.3.10
   * Subnet Mask: 255.255.255.0

## Usage

* Access the server from any PC using its IP address.
* Ping between PCs from different LANs to verify connectivity.

## Future Improvements

* Implement DHCP for dynamic IP assignment.
* Integrate additional services like DNS and HTTP on the server.

  ![Screenshot 2025-05-08 191601](https://github.com/user-attachments/assets/6edc3d57-41c5-44d1-8fe0-80908c654ea6)

