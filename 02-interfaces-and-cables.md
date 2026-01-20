# Ethernet Basics

---

## What Is Ethernet?

**Ethernet** is a collection of networking protocols and standards used for wired network communication.

---

## Why Do We Need Protocols and Standards?

- Provide a **common language** for devices to communicate
- Ensure interoperability between hardware from different vendors
- Define how data is formatted, transmitted, and received

---

## Bits and Bytes

- Data is represented using **binary (0 and 1)**
- **8 bits = 1 byte**
- Network speed is measured in **bits per second (bps)**

### Common Bit Measurements

| Name | Number of Bits |
|-----|---------------|
| 1 Kilobit (Kb) | 1,000 bits |
| 1 Megabit (Mb) | 1,000,000 bits |
| 1 Gigabit (Gb) | 1,000,000,000 bits |
| 1 Terabit (Tb) | 1,000,000,000,000 bits |

---

## Ethernet Standards

- Ethernet standards are defined by **IEEE**
- Officially standardized as **IEEE 802.3** in **1983**

---

## Ethernet Terminology

**BASE**
- Refers to **baseband signaling**

**T**
- Stands for **Twisted Pair**

**UTP**
- Unshielded Twisted Pair
- Twisting helps protect against **EMI (Electromagnetic Interference)**

**Full-Duplex**
- Devices can send and receive data **simultaneously**

---

## UTP Cables (10BASE-T & 100BASE-T)

### Straight-Through Cable

Used when connecting **different device types** (e.g., PC to switch).

**Transmission Pairs**
- PCs, Routers, Servers
  - Transmit (Tx): Pins **1 & 2**
  - Receive (Rx): Pins **3 & 6**
- Switches
  - Transmit (Tx): Pins **3 & 6**
  - Receive (Rx): Pins **1 & 2**

---

### Crossover Cable

Used when connecting **same device types** (e.g., switch to switch).

- Transmit and receive pairs are **reversed**
- Example:
  - Pin 1 connects to Pin 3 on the opposite end

---

## Auto MDI-X

**Auto MDI-X** is a network port feature that:
- Automatically detects cable type (straight-through or crossover)
- Automatically adjusts pinouts to establish a link

> Eliminates the need to manually select cable types

---

## UTP Cables (1000BASE-T & 10GBASE-T)

- Uses **all four wire pairs**
- Supports **bidirectional communication**
- Active pairs:
  - (1 & 2)
  - (3 & 6)
  - (4 & 5)
  - (7 & 8)

---

## Fiber-Optic Connections

### SFP Transceivers

**SFP** = Small Form-Factor Pluggable

- Uses separate fibers for:
  - Transmit (Tx)
  - Receive (Rx)

---

### Single-Mode Fiber

- Narrow core diameter
- Light enters at a **single angle**
- Uses **laser-based transmitters**
- Supports **longer distances**
- More expensive than multimode

---

### Multi-Mode Fiber

- Wider core diameter
- Allows **multiple light angles**
- Shorter distance than single-mode
- Longer distance than UTP
- Uses **LED-based transmitters**
- Less expensive than single-mode

---

## Fiber-Optic Cable Standards

Fiber standards define:
- Cable type
- Core size
- Maximum distance
- Supported speeds
