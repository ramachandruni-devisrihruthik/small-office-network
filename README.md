# small-office-network
Small Office Network using VLANs and Inter-VLAN Routing
# 🏢 Small Office Network Design (Cisco Packet Tracer)

## 📌 Overview
This project demonstrates the design and implementation of a small office network using VLANs and inter-VLAN routing.

## 🧠 Objective
- Segment departments (HR, IT, Sales)
- Enable communication between VLANs
- Implement efficient IP addressing

## 🛠️ Technologies Used
- Cisco Packet Tracer
- VLANs
- Subnetting (/26)
- Router-on-a-Stick
- Static IP Configuration

## 🏗️ Network Design
- VLAN 10 – HR → 192.168.1.0/26
- VLAN 20 – IT → 192.168.1.64/26
- VLAN 30 – SALES → 192.168.1.128/26

## ⚙️ Configuration Highlights
- Configured VLANs on switch
- Assigned access & trunk ports
- Configured router subinterfaces
- Enabled inter-VLAN routing

## 🧪 Testing
- Verified connectivity using ping
- Ensured communication across all VLANs

## 📸 Screenshots
## 🏗️ Network Topology
![Topology](screenshots/topology.png)

## 🔹 VLAN Configuration
![VLAN](screenshots/vlan.png)

## 🔹 Trunk Configuration
![Trunk](screenshots/trunk.png)

## 🔹 Router Configuration
![Router](screenshots/router-config.png)

## 🔹 Ping Test
![Ping](screenshots/ping.png)

## 🚀 Outcome
Successfully built a scalable and segmented network with full connectivity.

## 📚 Skills Gained
- Routing & Switching
- VLAN Configuration
- Network Troubleshooting
