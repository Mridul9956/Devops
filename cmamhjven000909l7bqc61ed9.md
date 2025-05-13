---
title: "🚀 DevOps Basics: Getting Started with Networking"
datePublished: Tue May 13 2025 12:26:09 GMT+0000 (Coordinated Universal Time)
cuid: cmamhjven000909l7bqc61ed9
slug: devops-basics-getting-started-with-networking
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1747139097884/6ad7ca37-2fa9-4a79-84ce-e36e49553ad0.png
tags: devops, devops-articles, devopscommunity, 90-days-of-devops-challenge

---

### 🌍 OSI & TCP/IP Models – How Data Travels Across Networks

Networks function like a well-organized postal system for data, ensuring information is efficiently transmitted, received, and understood. The **OSI Model** (7 layers) and **TCP/IP Model** (4 layers) are frameworks that describe this process. Each layer has a specific role in managing data transmission.

---

## **OSI Model (7 Layers)**

The OSI (Open Systems Interconnection) model provides a **structured** approach to how data moves through a network, from the user interface to physical transmission.

### **1\. Application Layer**

* Acts as the interface between users and the network.
    
* Handles services like web browsing, email, and messaging.
    
* Common protocols: **HTTP, HTTPS, FTP, SMTP, POP3, IMAP, DNS**.
    

### **2\. Presentation Layer**

* Formats and encrypts data for secure communication.
    
* Ensures compatibility across different systems.
    
* Handles compression, encoding, and encryption.
    
* Example formats: **JPEG, MP3, TLS, SSL**.
    

### **3\. Session Layer**

* Establishes, manages, and terminates connections between devices.
    
* Ensures data exchanges happen properly between sender and receiver.
    
* Protocols: **RPC, NetBIOS, PPTP, SOCKS**.
    

### **4\. Transport Layer**

* Guarantees reliable communication between devices.
    
* Provides error checking and ensures complete data delivery.
    
* Common protocols: **TCP (reliable) and UDP (fast, but less reliable)**.
    

### **5\. Network Layer**

* Determines the best path for data to travel.
    
* Assigns IP addresses to packets.
    
* Handles routing decisions.
    
* Protocols: **IP, ICMP, IGMP**.
    

### **6\. Data Link Layer**

* Ensures error-free transmission between directly connected nodes.
    
* Divides data into frames for delivery.
    
* Protocols: **Ethernet, MAC (Media Access Control), ARP (Address Resolution Protocol)**.
    

### **7\. Physical Layer**

* Transmits raw data as electrical, optical, or radio signals.
    
* Defines hardware aspects like cables, switches, and wireless networks.
    

---

## **TCP/IP Model (4 Layers)**

The **TCP/IP (Transmission Control Protocol/Internet Protocol) model** is a more simplified version of OSI, widely used for real-world internet communication.

### **1\. Application Layer**

* Functions similarly to the OSI Application, Presentation, and Session layers.
    
* Handles protocols such as **HTTP, SMTP, FTP, DNS**.
    

### **2\. Transport Layer**

* Ensures **reliable** or **fast** communication using **TCP (error-checked)** or **UDP (speed-focused)** protocols.
    

### **3\. Internet Layer**

* Defines how packets move across networks using **IP addressing, routing, and forwarding**.
    

### **4\. Network Access Layer**

* Combines OSI's **Data Link** and **Physical** layers to manage the actual data transmission.
    

## 🔗 DevOps Protocols & Ports

Different network services use **specific protocols and port numbers** to communicate. Some of the most important ones in DevOps include:

* **HTTP/HTTPS (80/443)** – Loads websites securely.
    
* **FTP (21)** – Transfers files between systems.
    
* **SSH (22)** – Secure remote login to servers.
    
* **DNS (53)** – Converts domain names (like [google.com](http://google.com)) into IP addresses.
    

These protocols keep **applications running smoothly and securely** across networks!

## ☁️ AWS EC2 & Security Groups – Cloud Basics

AWS **EC2** lets you create a **virtual server** in the cloud. But security matters!

* **Security Groups** act like firewalls, controlling access to your cloud instance.
    
* They **define rules** for what kind of traffic can enter or leave your server.
    

By setting up **security rules**, you ensure your cloud environment is **safe and efficient**

## 🔍 Essential Networking Commands

DevOps engineers often **use commands** to check connectivity, troubleshoot networks, and interact with servers. Here are some useful ones:

* **ping** – Tests if a system is reachable.
    
* **traceroute / tracert** – Tracks how data moves across networks.
    
* **netstat** – Shows active network connections.
    
* **curl** – Sends HTTP requests via the command line.
    
* **dig / nslookup** – Looks up domain names and IPs.
    

These commands help **diagnose and optimize** network performance!