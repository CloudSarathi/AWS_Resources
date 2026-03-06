# 🌐 Networking & AWS Cloud Computing: Master Notes

Welcome to my comprehensive study repository. These notes cover everything from fundamental networking concepts to advanced AWS cloud infrastructure.

---

## 📑 Table of Contents
1. [BASICS OF NETWORKING](#1-basics-of-networking)
2. [Network Classifications](#2-network-classifications)
3. [IP Addressing & Subnetting](#3-ip-addressing--subnetting)
4. [Protocols & Models](#4-protocols--models)

---

## 🏗 1. Basics of Networking

### What is networking ????
Networking is the practice of transporting and exchanging data between nodes over a shared medium in an information system.

## 🏗 2. Network Classifications
Networking is the practice of exchanging data between nodes over a shared medium.

| Type | Full Name | Coverage | Key Characteristic |
| :--- | :--- | :--- | :--- |
| **LAN** | Local Area Network | Residence/Office | High speed, low cost |
| **MAN** | Metropolitan Area Network | City-wide | Connects multiple LANs |
| **WAN** | Wide Area Network | Global (Internet) | Uses leased telecommunication circuits |

### Local Area Network (LAN)
A local area network is a computer network that interconnects computers within a limited area, such as a residence, school, laboratory, university campus, or office building.

<img width="628" height="480" alt="image" src="https://github.com/user-attachments/assets/4e1ada6d-cda1-4820-b29a-5eb825d54ab3" />

> [!CAUTION]
> **LAN Security:** While cost-effective, LANs are vulnerable because it is easy to gain access to others' software components.

### Metropolitan Area Network (MAN)
A metropolitan area network (MAN) is a computer network that is larger than a single building local area network (LAN) but is located in a single geographic area that is smaller than a wide area network (WAN).

<img width="1200" height="630" alt="image" src="https://github.com/user-attachments/assets/8ac9bec1-1368-41f5-b95e-d776cdd6fbcb" />

### Wide Area Network (WAN)
A wide area network is a telecommunications network that extends over a large geographic area. Wide area networks are often established with leased telecommunication circuits

<img width="627" height="398" alt="197-1972632_wan-definition-hd-png-download-removebg-preview" src="https://github.com/user-attachments/assets/d71606de-e414-4726-a0c8-46cbf04f53a4" />

---

## 🔢 2. IP Addressing & Subnetting
* **IPv4:** 32-bit address (e.g., `172.16.254.1`).
* **Localhost:** `127.0.0.1` (Internal loopback).
* **0.0.0.0:** Offline status or "any" network.
* **Public vs Private:** Public IPs are ISP-assigned; Private IPs are for internal routing (NAT).
* **CIDR:** `10.0.0.0/24` — The `/24` defines the network portion and available host IPs.

### What is an IP Address?
An IP Address (Internet Protocol Address) is a unique numerical label assigned to each device connected to a computer network that uses the Internet Protocol for communication.

<img width="800" height="400" alt="image" src="https://github.com/user-attachments/assets/50b2229d-df2b-4e40-ae1a-8cc0128939f3" />

### Public IP Addresses
A Public IP address is assigned to every device that directly accesses the internet. This address is unique across the entire internet. Uniqueness & Accessibility are its key characteristics & are assigned by Internet Service Providers. When you connect to the internet through an ISP, your device or router receives a public IP address. These addresses can be static or dynamic.

<img width="800" height="400" alt="image" src="https://github.com/user-attachments/assets/937b3356-0d6c-4db3-b376-be7b5bd0c01a" />

### Private IP Addresses
Private IP addresses are used within private networks and are not routable on the Internet. This means that devices with private IP addresses cannot directly communicate with devices on the internet without a translating mechanism like a router performing Network Address Translation (NAT). These are only required to be unique within their own network & are used for communication between devices within the same network

* Defined ranges for IPv4: 10.0.0.0 to 10.255.255.255, 172.16.0.0 to 172.31.255.255, 192.168.0.0 to 192.168.255.255

### IPv4

This is the most common form of IP Address. It consists of four sets of numbers(octets) separated by dots. This format can support over 4 billion unique addresses. Each octet represents eight bits, or a byte, and can take a value from 0 to 255. This range is derived from the possible combinations of eight bits (28 = 256 combinations)

<img width="800" height="350" alt="image" src="https://github.com/user-attachments/assets/96fc933a-7f15-4214-b890-4bfd6e070a47" />

### Classes of IPv4 Address

<img width="669" height="304" alt="image" src="https://github.com/user-attachments/assets/24d78997-88a6-47ad-b983-832756a48275" />

* Class A (1.0.0.0 to 127.255.255.255): Used for very large networks (like multinational companies). Supports up to 16 million hosts per network.
* Class B (128.0.0.0 to 191.255.255.255): Used for medium-sized networks, such as large organizations. Supports up to 65,000 hosts per network.
* Class C (192.0.0.0 to 223.255.255.255): Used for smaller networks, like small businesses or home networks. Supports up to 254 hosts per network.
* Class D (224.0.0.0 to 239.255.255.255): Reserved for multicast groups (used to send data to multiple devices at once). Not used for traditional devices or networks.
* Class E (240.0.0.0 to 255.255.255.255): Reserved for experimental purposes and future use.


---

## 📜 3. Protocols & Models
### TCP/IP Layer Stack
* **Application:** HTTP, FTP, SMTP, DNS.
* **Transport:** TCP (Reliable) / UDP (Fast).
* **Network:** IP Addressing & Routing.
* **Physical/Link:** Ethernet & Hardware.

### Remote Access Tools
* **SSH (Port 22):** Secure data exchange between two computers.
* **RDP (Port 3389):** Microsoft's protocol for remote desktop access.
---

## 🛠 Project Progress
- [x] Networking Basics
- [ ] Cloud Service Models
- [ ] AWS Compute (EC2/Lambda) Notes
- [ ] AWS Storage (S3) Notes

---
*Created by Cloud Sarathi - 2026*
