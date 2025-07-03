
# Departmental Network Design Using Cisco Packet Tracer

## 📁 Project Overview

This project demonstrates the design and implementation of a basic **LAN (Local Area Network)** for a small organization using **Cisco Packet Tracer**. The network connects three departments — **Accounts**, **Sales**, and **Delivery** — each with their own subnetwork, appropriate routing, and IP configuration.

The goal was to simulate a realistic business environment where departments are logically separated using subnetting, while still being able to communicate across the network.

---

## 🛠️ Tools & Technologies
- **Cisco Packet Tracer** (Network simulation)
- **IPv4 Subnetting**
- **Static IP configuration**
- **Routers, Switches, PCs**
- **Basic network cabling**
- **Ping for connectivity testing**

---

## 🧱 Network Structure

### Departments:
- **Accounts Department** – 2 PCs
- **Sales Department** – 2 PCs
- **Delivery Department** – 2 PCs

### Network Address Used:
```
192.165.20.0/26
```

> The network was subnetted to accommodate at least 3 departments using a subnet mask of `255.255.255.192`.

### Devices Used:
- 3 departmental **Switches**
- 1 or more **Routers** to handle inter-departmental communication
- 6 PCs (2 per department)

---

## 📡 Network Design Summary

- Each department was assigned a **separate subnet**.
- Devices were connected using **Copper Straight-Through cables**.
- Each **PC was assigned a static IP address**, subnet mask, and default gateway based on its department.
- **Switches** were used to connect PCs within each department.
- A **Router** connected all the departmental switches to allow inter-department communication.
- Connectivity was tested using the **ping command** from one department to another.

---

## ✅ Objectives Achieved

- [x] Designed 3 isolated departmental networks
- [x] Subnetted a Class C network to create 4 subnets
- [x] Assigned appropriate IP addresses and subnet masks
- [x] Configured gateway addresses on all PCs
- [x] Verified full connectivity using `ping`

---

## 📁 File Structure

```
project/
│
├── departmental-network.pkt        # Cisco Packet Tracer file
├── README.md                       # Project overview
```

---

## 🎓 What I Learned

- How to **subnet a network** using CIDR notation
- How to connect and configure **routers and switches**
- IP addressing and **default gateway configuration**
- Importance of network segmentation in real-world environments
- Basic **troubleshooting** using command-line tools (like `ipconfig`, `ping`)

---

## 🚀 Future Improvements

- Add **DHCP configuration** to automate IP addressing
- Introduce **VLANs** to increase network security
- Simulate **firewall rules or ACLs** to control traffic
- Add a **server (DNS or Web)** to simulate enterprise services

---

## 📌 Author

**Name:** [Your Full Name]  
**Cybersecurity Student | Networking Enthusiast**

---

## 📎 How to Open the Project

1. Download and install **Cisco Packet Tracer** (if you haven't already)
2. Open the `departmental-network.pkt` file
3. Review IP configurations and run connectivity tests

---

## 💼 Relevance to Cybersecurity

This project represents an essential foundation in **networking**, which is critical in cybersecurity. Understanding how to design, segment, and test networks is key for roles like:
- SOC Analyst
- Network Security Engineer
- Penetration Tester
