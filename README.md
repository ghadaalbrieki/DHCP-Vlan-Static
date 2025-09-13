# 🌐 Two Routers DHCP Network Project using Cisco Packet Tracer

## 📘 Overview

This project is a simulation of a network using **Cisco Packet Tracer**.  
It includes two routers, two switches, a DHCP server, and multiple PCs.

- **Router1** acts as a DHCP server for its subnet (192.168.10.0/24).  
- **Router2** uses an external DHCP server to assign IPs in subnet (192.168.11.0/24).  
- A point-to-point link (10.0.0.0/30) connects the two routers for inter-network communication.

---

## 🖥️ Network Components

- 2 Routers (R1, R2)  
- 2 Switches (SW1, SW2)  
- 1 DHCP Server (192.168.11.100)  
- Multiple PCs

---

## 🗺️ Subnet Distribution

| Subnet         | Connected Devices                         | DHCP Source      |
|----------------|-------------------------------------------|-----------------|
| 192.168.10.0/24 | PCs connected to R1                        | Router1 (DHCP)  |
| 192.168.11.0/24 | PCs + DHCP Server (192.168.11.100) connected to R2 | DHCP Server     |
| 10.0.0.0/30     | Between Router1 and Router2               | Static IP       |

---

## ⚙️ DHCP Configuration

- **Router1** provides DHCP for subnet `192.168.10.0/24`.  
- **DHCP Server** provides IPs for subnet `192.168.11.0/24`.  
- The link `10.0.0.0/30` between R1 and R2 is configured manually (static IP).  
- All PCs are configured to obtain IPs automatically (DHCP).

---

## ✅ Connectivity Testing

- ✅ PCs in 192.168.10.0 can reach PCs in 192.168.11.0  
- ✅ DHCP works correctly in both subnets  
- ✅ Inter-network routing between R1 and R2 is functional

---

## 📁 Included Files

| File Name               | Description                          |
|-------------------------|--------------------------------------|
| `Routers-DHCP.pkt`   | Cisco Packet Tracer network file     |
| `screenshot.png`        | Image of the network design          |
| `README.md`             | Project documentation                |

## 👩‍💻 Ghada Albrieki
