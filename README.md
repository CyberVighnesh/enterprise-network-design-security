# Enterprise IT Support Network Design

## 📌 Project Overview

This project presents an enterprise IT support network topology designed and visualized using **Cisco Packet Tracer**.

The objective was to design a structured network for an organization with multiple departments, servers, printers, CCTV devices, employees, and guest wireless users.

The topology focuses on logical network organization, scalability, connectivity, and basic network segmentation.

> **Note:** This project focuses on network design and visualization. The topology is not intended to represent a fully configured production network.

---

## 🏗️ Network Architecture

The proposed architecture follows a hierarchical structure:

**ISP → Edge Router → Firewall → Core Switch → Access/Floor Switches → End Devices**

The network contains:

* ISP connectivity
* Edge router
* Cisco ASA firewall
* Core switch
* Floor/access switches
* Server infrastructure
* Employee systems
* Printer network
* CCTV network
* Guest Wi-Fi
* Wireless access points
* Laptops and smartphones

---

## 🌐 Proposed Network Segmentation

The topology uses separate logical network segments for different types of devices.

| VLAN    | Purpose     |
| ------- | ----------- |
| VLAN 10 | Employees   |
| VLAN 20 | Servers     |
| VLAN 30 | CCTV        |
| VLAN 40 | Guest Wi-Fi |
| VLAN 50 | Printers    |

These VLAN labels represent the **proposed network design** and are included to demonstrate how different network resources could be logically separated in an enterprise environment.

---

## 🔥 Security Design Concept

The topology includes a firewall between the ISP/router and the internal network.

The proposed segmentation can help separate:

* Employee systems
* Servers
* CCTV devices
* Guest wireless users
* Printers

Guest wireless users can be isolated from internal enterprise resources, while servers and security devices can be placed in dedicated network segments.

---

## 📡 Wireless Network

Multiple wireless access points are included in the topology to provide connectivity for:

* Smartphones
* Laptops
* Guest users
* Employee users

This demonstrates how wireless access can be integrated into an enterprise network design.

---

## 🖥️ Network Components

### Core Infrastructure

* Cisco 1941 Router
* Cisco ASA 5505 Firewall
* Cisco 3560 Core Switch
* Cisco 2950 Access/Floor Switches

### Network Services

* Server
* DHCP/DNS server concept
* Network printers

### Endpoints

* Desktop PCs
* Laptops
* Smartphones
* CCTV camera/webcam

---

## 🏢 Network Layout

The design represents a multi-floor enterprise environment.

### Floor 1

Employee workstations and wireless users.

### Floor 2

Employee systems, wireless access, and associated network devices.

### Floor 3

CCTV/security devices and wireless users.

### Central Network

The core network contains the server infrastructure and provides connectivity between the different network segments.

---

## 📸 Network Topology

![Enterprise Network Topology](screenshots/network-topology.png)

---

## 🛠️ Technology Used

* Cisco Packet Tracer
* Cisco Networking Devices
* VLAN concepts
* Network Segmentation
* Routing Concepts
* Firewall Concepts
* Wireless Networking
* Enterprise Network Design
* IT Infrastructure Design

---

## 🎯 Project Objectives

The main objectives of this project were:

1. Design an enterprise network topology.
2. Organize network devices into logical segments.
3. Demonstrate a hierarchical network architecture.
4. Separate employee, server, CCTV, printer, and guest networks.
5. Integrate wired and wireless devices.
6. Demonstrate the placement of firewall and core networking infrastructure.
7. Create a scalable topology suitable for an enterprise IT environment.

---

## 📚 Key Learning Outcomes

Through this project, I strengthened my understanding of:

* Enterprise network architecture
* Network topology design
* VLAN planning
* Network segmentation
* Router and switch placement
* Firewall placement
* Wireless network design
* IT infrastructure planning
* Cisco Packet Tracer

---

## 🚀 Future Improvements

The next version of this project could include:

* Actual VLAN configuration
* Inter-VLAN routing
* DHCP configuration
* DNS configuration
* Access Control Lists (ACLs)
* Firewall security policies
* Guest network isolation
* IP addressing scheme
* Connectivity testing
* Network monitoring

---

## 👨‍💻 Author

**Vighnesh**

IT Support | Networking | Cybersecurity | AWS | DevOps

Portfolio: [vignix.in](https://vignix.in)
