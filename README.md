# 🌐 OSI Model — Networking Fundamentals

A beginner-friendly cybersecurity and networking reference covering the **OSI (Open Systems Interconnection) Model**, its 7 layers, protocols, data units, common devices, and cybersecurity relevance.

## 📌 Description

The **OSI Model** is a conceptual framework that explains how data is communicated between devices over a network.

It divides network communication into **7 layers**, where each layer performs a specific function.

```text
Layer 7 → Application
Layer 6 → Presentation
Layer 5 → Session
Layer 4 → Transport
Layer 3 → Network
Layer 2 → Data Link
Layer 1 → Physical
```

## 🧠 Easy Mnemonic

**A P S T N D P**

> All People Seem To Need Data Processing

---

# 📚 The 7 OSI Layers

## 7️⃣ Application Layer

Provides network services directly to applications.

**Common Protocols:**

* HTTP
* HTTPS
* DNS
* FTP
* SMTP
* SSH

**Data Unit:** Data

**Common Systems/Devices:**

* Proxy Server
* Application Gateway

---

## 6️⃣ Presentation Layer

Responsible for data representation and can handle:

* Data formatting
* Encryption/Decryption
* Compression
* Character encoding

**Examples:**

* JPEG
* PNG
* ASCII
* UTF-8

**Data Unit:** Data

---

## 5️⃣ Session Layer

Manages communication sessions between applications.

Main functions include:

* Establishing sessions
* Maintaining sessions
* Terminating sessions
* Dialog control

**Data Unit:** Data

---

## 4️⃣ Transport Layer

Provides end-to-end communication between devices.

### TCP

* Connection-oriented
* Reliable
* Ordered delivery

### UDP

* Connectionless
* Lower overhead
* Does not guarantee delivery

**Data Units:**

* TCP → Segment
* UDP → Datagram

**Common Devices/Systems:**

* Load Balancers
* Stateful Firewalls

---

## 3️⃣ Network Layer

Responsible for **logical addressing and routing**.

**Examples:**

* IPv4
* IPv6
* IP addresses

**Common Devices:**

* Router
* Layer 3 Switch

**Data Unit:** Packet

### Example IPv4 Address

```text
192.168.1.10
```

IPv4 contains:

```text
4 Octets × 8 Bits = 32 Bits
```

---

## 2️⃣ Data Link Layer

Provides communication between devices on the same network.

It uses **MAC addresses** and works with frames.

**Examples:**

* Ethernet
* Wi-Fi

**Common Devices:**

* Switch
* Bridge
* Wireless Access Point

**Data Unit:** Frame

### Example MAC Address

```text
00:1A:2B:3C:4D:5E
```

---

## 1️⃣ Physical Layer

Responsible for transmitting raw **bits (0s and 1s)** through a physical medium.

**Examples:**

* Ethernet cable
* Fiber optic cable
* Radio signals
* Connectors

**Common Devices:**

* Hub
* Repeater

**Data Unit:** Bits

---

# 📊 OSI Model Summary

| Layer | Name         | Main Function                       | Examples            | Data Unit        |
| ----- | ------------ | ----------------------------------- | ------------------- | ---------------- |
| 7     | Application  | Network services                    | HTTP, DNS, SSH      | Data             |
| 6     | Presentation | Formatting, encryption, compression | JPEG, UTF-8         | Data             |
| 5     | Session      | Session management                  | Session control     | Data             |
| 4     | Transport    | End-to-end communication            | TCP, UDP            | Segment/Datagram |
| 3     | Network      | Routing and IP addressing           | IP, Router          | Packet           |
| 2     | Data Link    | MAC addressing and frames           | Ethernet, Wi-Fi     | Frame            |
| 1     | Physical     | Bit transmission                    | Cable, Fiber, Radio | Bits             |

---

# 🖥️ Common Device Placement

```text
Layer 7 → Proxy / Application Gateway

Layer 6 → Encryption & Data Formatting Systems

Layer 5 → Session-aware Systems

Layer 4 → Load Balancer / Stateful Firewall

Layer 3 → Router / Layer 3 Switch

Layer 2 → Switch / Bridge / Access Point

Layer 1 → Hub / Repeater / Cable
```

> **Note:** Modern network devices can operate across multiple OSI layers. Device placement above is a simplified learning model.

---

# 🔄 Data Encapsulation

When data is transmitted, it moves down the OSI layers on the sender side.

```text
Application   → Data
Presentation  → Data
Session       → Data
Transport     → Segment
Network       → Packet
Data Link     → Frame
Physical      → Bits
```

At the receiving device, the process happens in reverse. This is called **decapsulation**.

```text
Sender
L7 → L6 → L5 → L4 → L3 → L2 → L1
                  ↓
               Network
                  ↓
Receiver
L1 → L2 → L3 → L4 → L5 → L6 → L7
```

---

# 🛡️ OSI Model in Cybersecurity

The OSI Model helps cybersecurity professionals understand where network traffic and security events occur.

### Layer 1

Physical security and physical network infrastructure.

### Layer 2

MAC addresses, ARP-related traffic, switching, and VLANs.

### Layer 3

IP addressing, routing, and IP-based traffic.

### Layer 4

TCP/UDP communication and port-based traffic.

### Layer 7

Application protocols and application-level security issues.

> Security controls can operate across multiple layers, so these examples are simplified for learning.

---

# 🔑 Quick Revision

```text
L7 → Application → HTTP, DNS, SSH
L6 → Presentation → Formatting, Encryption
L5 → Session → Sessions
L4 → Transport → TCP, UDP
L3 → Network → IP, Routing
L2 → Data Link → MAC, Frames
L1 → Physical → Bits, Cables
```

## ⭐ Important Concepts

* OSI has **7 layers**.
* **IP Address → Layer 3**
* **MAC Address → Layer 2**
* **TCP/UDP → Layer 4**
* **HTTP/DNS/SSH → Layer 7**
* **Packet → Layer 3**
* **Frame → Layer 2**
* **Bits → Layer 1**
* **IPv4 → 32 bits**
* **1 Octet → 8 bits**

---

## 🎯 Purpose of This Repository

This repository is created as a **networking and cybersecurity learning reference** for understanding the OSI Model and its relationship with network protocols, devices, data units, and security concepts.

## 📖 Topics Covered

* OSI Model
* 7 OSI Layers
* Network Protocols
* IP Addressing
* MAC Address
* IPv4 and Octets
* Bits and Bytes
* Network Devices
* Data Encapsulation
* Data Decapsulation
* Basic Cybersecurity Concepts

## 👩‍💻 Author

*Fatima**

Cybersecurity & Networking Learning Repository
# OSI-model-
This repository is created as a networking and cybersecurity learning reference for understanding the OSI Model and its relationship with network protocols, devices, data units, and security concepts.
