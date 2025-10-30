# Bank Network Simulation (Head Office + 2 Branches)

This project simulates a **bank’s internal network** built in **Cisco Packet Tracer**, connecting a Head Office with two remote Branch Offices through serial WAN links. It demonstrates real-world enterprise networking with DHCP, DNS, ACLs, routing, and backup links.

---

## Features
- **DHCP Server:** Centralized IP allocation for all network segments  
- **DNS Server:** Domain name resolution for internal resources  
- **RIP Routing:** Dynamic route exchange between all routers  
- **Backup Serial Link:** Ensures branch connectivity if the main link fails  
- **Access Control List (ACL):** Restricts Branch 2 from accessing HQ web server (port 80)  
- **End-to-End Communication:** HQ ↔ Branch1 ↔ Branch2 fully operational  

---

## Topology Summary
**Head Office (HQ):**
- Router: Cisco 2911  
- Switch: Cisco 2960  
- DHCP + DNS Server  
- 4 PCs  

**Branch 1:**
- Router: Cisco 2911  
- Switch: Cisco 2960  
- 3 PCs  

**Branch 2:**
- Router: Cisco 2911  
- Switch: Cisco 2960  
- 3 PCs  

---

## Learning Outcomes
- Understanding of IP addressing, subnetting, and hierarchical design  
- Implementation of DHCP relay and DNS mapping  
- Applying ACLs to control inter-branch traffic  
- Realistic simulation of enterprise branch connectivity and failover  

---

## Tools Used
- **Cisco Packet Tracer 8.x**  
- **Router:** Cisco 2911  
- **Switch:** Cisco 2960-24TT  

---

## How to Use
1. Open the `.pkt` file in Cisco Packet Tracer  
2. Start the simulation  
3. Use `ping` and `nslookup` to verify communication between PCs  
4. Experiment with ACLs or disable one serial link to test backup routing  

---

**Project:** CNDC Lab — Bank Network with Head Office and Two Branches  
