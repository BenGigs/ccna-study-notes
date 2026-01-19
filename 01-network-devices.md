# What Is a Network?

A **network** is a digital telecommunication system that allows devices (nodes) to share resources and communicate with each other.

---

## Nodes

A **node** is any device connected to a network, such as:

- Router
- Switch
- Firewall
- Server
- Client

**Servers and clients** are often referred to as:
- **End hosts**
- **Endpoints**

---

## Clients and Servers

**Client**
- A device that accesses a service made available by a server

**Server**
- A device that provides functions or services for clients

---

## LAN (Local Area Network)

A **Local Area Network (LAN)** is a network that covers a small geographic area, such as:
- Home
- Office
- School
- Campus

---

## Switches

**Examples**
- Cisco Catalyst 9200  
- Cisco Catalyst 3650  

**Purpose**
- Provide connectivity to devices within the same LAN

**Key Characteristics**
- Have many network interfaces (ports), often **24 or more**
- Allow end hosts to communicate within a LAN
- **Do NOT** provide connectivity between different LANs
- **Do NOT** route traffic to the internet

---

## Routers

**Examples**
- Cisco ISR 1000
- Cisco ISR 900
- Cisco ISR 4000  

> **ISR** = Integrated Services Router

**Purpose**
- Provide connectivity **between different LANs**
- Route traffic to and from the internet

**Key Characteristics**
- Have fewer interfaces than switches
- Make forwarding decisions based on IP addresses

---

## Firewalls

**Examples**
- Cisco ASA 5500-X
- Cisco Firepower 2100  

> **ASA** = Adaptive Security Appliance

**Purpose**
- Monitor and control network traffic based on security rules

**Key Characteristics**
- Can be placed:
  - Inside the network
  - At the network perimeter (outside-facing)
- Control traffic entering and leaving a network

### Types of Firewalls

**Network Firewalls**
- Hardware devices
- Filter traffic between networks

**Host-Based Firewalls**
- Software-based
- Filter traffic entering and exiting a single host (e.g., a PC)

**Next-Generation Firewalls (NGFW)**
- Include advanced filtering capabilities such as:
  - Application awareness
  - Deep packet inspection
  - Intrusion prevention
