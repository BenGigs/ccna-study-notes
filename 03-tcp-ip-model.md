# Protocols, Standards, and the TCP/IP Model

---

## Protocols vs Standards

**Protocol**
- A set of rules defining how data is communicated between devices over a network

**Standard**
- An agreed-upon specification that defines how a protocol or technology should work

---

## Standards Organizations

### IEEE (Institute of Electrical and Electronics Engineers)
Responsible for many physical and data-link layer standards:
- Ethernet (IEEE 802.3)
- Wi-Fi (IEEE 802.11)

### IETF (Internet Engineering Task Force)
Responsible for many core internet protocols:
- TCP
- IP
- UDP
- HTTP
- DNS

- Publishes standards in documents called **RFCs (Requests for Comments)**

---

## TCP/IP Model Layers

The TCP/IP model describes how data moves from one application to another across a network.

---

### Layer 5 – Application Layer  
*(Sometimes referred to as OSI Layer 7)*

- Handles communication between application processes
- Creates, sends, and interprets data

**Common Protocols**
- HTTP / HTTPS
- FTP / SFTP
- SMTP / POP3 / IMAP
- DNS
- SNMP
- SSH

---

### Layer 4 – Transport Layer

- Provides end-to-end communication between applications
- Uses **port numbers** to identify services

**Common Protocols**
- TCP
- UDP

---

### Layer 3 – Internet Layer

- Provides end-to-end communication between hosts across networks
- Uses **IP addresses** and **routers**

**Common Protocols**
- IP (IPv4 / IPv6)
- ICMP
- IPsec

---

### Layer 2 – Data Link Layer

- Handles **hop-to-hop delivery** within a local network
- Uses **MAC addresses** and **switches**

**Common Protocols / Technologies**
- Ethernet (IEEE 802.3)
- Wi-Fi (IEEE 802.11)
- ARP

---

### Layer 1 – Physical Layer

- Transmits raw bits as electrical, optical, or radio signals
- Operates over the physical medium

**Common Technologies**
- Copper cabling (Ethernet)
- Fiber-optic cabling
- Radio / wireless signals

---

## Encapsulation

Encapsulation is the process of wrapping data with headers (and trailers) as it moves **down** the TCP/IP stack.

### Layer 4 – Transport
- TCP → **Segment**
- UDP → **Datagram**
- Also called the **Layer 4 PDU**

### Layer 3 – Internet
- Segment / Datagram + Layer 3 header → **Packet**
- Also called the **Layer 3 PDU**

### Layer 2 – Network Access
- Packet + Layer 2 header and trailer → **Frame**
- This is what is actually transmitted on the wire
- Also called the **Layer 2 PDU**

---

## Decapsulation

Decapsulation is the reverse process:
- Headers and trailers are removed as data moves **up** the TCP/IP stack
- Each layer processes only the information relevant to it

---

## PDUs (Protocol Data Units)

| Layer | PDU Name |
|-----|---------|
| Application | Data |
| Transport | Segment / Datagram |
| Internet | Packet |
| Network Access | Frame |
| Physical | Bits |

---

## Payload (Very Important)

**Payload** refers to the data carried inside a layer.

- Layer 4 payload → Application data
- Layer 3 payload → Segment or Datagram
- Layer 2 payload → Packet

---

