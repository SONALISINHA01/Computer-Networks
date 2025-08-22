# 🌐 Network Experiments  

This repository serves as a **portfolio of hands-on network experiments and configurations** completed as part of a comprehensive **Computer Networking course**. The projects demonstrate practical skills in **configuring and managing various network devices, protocols, and services**, offering a solid foundation in **Network Architecture** and **Network Administration**.

The experiments are designed to provide a deep understanding of how networks function, from the **logical framework of Network Models** to the **physical components of Network Infrastructure**.

---

## 🧪 **Core Concepts & Topics**
The experiments in this repository directly apply the following key concepts learned in the course:

- **Network Protocols**: Practical experience with fundamental communication protocols like TCP/IP and their role in data transmission.
- **OSI and TCP/IP Models**: Implementing configurations that correspond to different layers of these foundational network models.
- **Network Routing**: Demonstrating how data packets are efficiently forwarded between networks using various routing protocols.
- **Local Area Networks (LANs)**: Building and managing small-scale network environments.
- **Network Security**: Implementing basic security measures through protocol and access controls.
- **Network Planning and Design**: Strategic decisions about IP addressing and subnetting, particularly with **VLSM**.
- **Servers & Services**: Deploying and troubleshooting essential network services.
- **Data Integrity**: Ensuring accuracy and consistency of data across the network.
- **Network Troubleshooting**: Identifying and resolving common configuration errors and connectivity issues.

---

## 📂 **Directory Structure and Experiment Details**

The projects are organized into folders, each containing the necessary configuration files and documentation for a specific experiment.

---

### **1. Server and Service Configuration**
These experiments focus on deploying **critical services** that are vital for network operations, providing hands-on experience with server functionality.

- **DHCP, DNS AND WEB SERVER**  
  Configured a server to act as:
  - **DHCP Server** – Automatically leases IP addresses to clients, eliminating manual configuration.
  - **DNS Server** – Resolves domain names to IP addresses, essential for internet access.
  - **Web Server** – Hosts a simple webpage using HTTP protocol to demonstrate client-server communication.

- **DNS SERVER**  
  Built and tested a standalone **DNS server** from scratch, including:
  - Forward and reverse lookup zones
  - Understanding DNS record types and hierarchy

- **EMAIL SERVER**  
  Configured an email server implementing:
  - **SMTP** for sending emails
  - **POP3/IMAP** for receiving emails  
  Provided insight into how email communication works in real networks.

---

### **2. IPv4 Routing**
Focuses on routing within IPv4 networks, demonstrating both **manual and automated routing** approaches.

- **DYNAMIC ROUTING (FLSM)**  
  Configured a dynamic routing protocol (e.g., **OSPF** or **EIGRP**) to:
  - Automatically exchange routing information between routers
  - Use **Fixed-Length Subnet Masking (FLSM)** for uniform subnet sizes

- **DYNAMIC ROUTING (VLSM)**  
  Advanced dynamic routing using **Variable-Length Subnet Masking (VLSM)** for:
  - Efficient IP address allocation
  - Demonstrating skills in **Network Planning and Design**

- **STATIC ROUTING WITH FLSM**  
  Manually configured static routes across routers using **FLSM**.  
  Provided a clear understanding of **low-level packet forwarding**.

- **STATIC ROUTING WITH VLSM**  
  Combined **manual routing** with **VLSM** for:
  - IP address conservation
  - Practical scenario in real-world network design

---

### **3. IPv6 Routing**
Explores **next-generation IP addressing** using **IPv6**, showcasing scalability and future-proof network designs.

- **IPv6 DYNAMIC ROUTING**  
  Configured a dynamic routing protocol for **IPv6** networks:
  - Automatic route discovery and update
  - Understanding IPv6 complexity and topology management

- **IPv6 STATIC ROUTING**  
  Implemented static routes with IPv6 addresses:
  - Explicit packet forwarding paths
  - Direct comparison with IPv4 static routing for conceptual clarity

---

## ✅ **Learning Outcomes**
By completing these experiments, you will:
- Understand **OSI & TCP/IP Models**
- Perform **IP addressing and subnetting (FLSM & VLSM)**
- Configure **IPv4 & IPv6 static and dynamic routing**
- Deploy and troubleshoot **DHCP, DNS, Web, and Email servers**
- Gain experience with **network security basics and access control**
- Build skills in **network troubleshooting and performance optimization**

---

## 🛠 **Tools & Technologies**
- **Cisco Packet Tracer** – Primary simulation tool
- **GNS3** – For advanced network emulation
- **Networking Protocols**: RIP, OSPF, EIGRP
- **Services**: DHCP, DNS, Email, Web Server


---

### ⭐ **If you find this helpful, give the repo a star!**
