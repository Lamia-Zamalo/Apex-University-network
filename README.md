# 🌐 Apex University Network

This project shows the **network infrastructure of Apex University**, an academic institution similar to East West University. The university manages a large number of computers and devices across multiple campuses with both wired and wireless connectivity.  
The network supports various academic and administrative systems such as admissions, results, library management, accounts, eTender, and more.

 Tools & Devices Used
- **Cisco Packet Tracer**
- **PT-Router**
- **2960 Switch**
- **PC**
- **Copper Straight-Through Cable**
- **Serial DCE Cable**
- **DNS Server**
- **DHCP Server**
- **Web Server**
- **Wireless Devices:** Laptops, Smartphones


# Purpose of the Network
- Every server device functions as a **WEB, DHCP, and DNS server**, representing the University of Apex website.
- The **DNS Server** resolves `http://www.apex.edu.bd` to the web server hosting the university site.
- **DHCP Server** automatically assigns IP addresses to all network devices.
- Provides **wireless internet access** across all campuses.
- The network includes **six routers** connecting **six campuses** of the university.
- Ensures full **interconnectivity between all hosts and servers**.


## Network Design Details
- **Campus 1:** Class A IP – `15.0.0.0`  
- **Campus 2:** Class A IP – `115.0.0.0`  
- **Campus 3:** Class B IP – `145.50.0.0`  
- **Campus 4:** Class B IP – `135.30.0.0`  
- **Campus 5:** Class C IP – `210.210.210.0`

All IPs are **automatically assigned** by a centralized **DHCP server**.  
A **DNS server** is configured to allow access to the Apex University website (`www.apex.edu.bd`) for all connected hosts.



##  How to Use
1. Download the `.pkt` file from this repository.  
2. Open it using **Cisco Packet Tracer**.  
3. Explore each campus topology, device configuration, and connectivity.  
4. Simulate pings, check DHCP allocations, and test website resolution via the DNS server.

---

## Key Learning Outcomes
- Understanding enterprise-level **multi-campus network topology**.  
- Implementation of **DHCP, DNS, and Web Servers**.  
- Configuration of **routers, switches, and wireless access**.  
- Realistic simulation of a university’s IT infrastructure.



👩‍💻 *Created by Lamia Zaman*  
🎓 *Apex University Network Simulation | Cisco Packet Tracer Project*
