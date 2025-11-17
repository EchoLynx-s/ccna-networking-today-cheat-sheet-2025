# CCNA: Networking Today — 2025 Cheat Sheet (EchoLynx)

A structured, practical companion for the **Networking Today** module from Cisco Networking Academy (CCNA).  
This repo tracks my progress and notes as I work through the module and build a solid foundation in networking for my cybersecurity path.

> ⚠️ Not official Cisco material. These are my personal study notes and summaries.

---

## Module Overview

**Module title:** Networking Today  
**Module objective:** Explain the advances in modern network technologies and how they impact people, businesses, and IT.

This module introduces:

- Why networking skills matter for IT and cybersecurity  
- How Packet Tracer is used to simulate real networks  
- How networks connect people and remove geographical boundaries  
- The basic building blocks of a network (hosts, devices, media)  
- Logical vs. physical topology diagrams  
- Common network types (LAN, WAN, internet, intranet, extranet)

---

## Progress Overview (1.0 – 1.4)

| Section | Title                                                   |
|--------|----------------------------------------------------------|
| 1.0    | Introduction                                             |
| 1.0.1  | Why should I take this module?                           |
| 1.0.2  | What will I learn to do in this module?                  | 
| 1.0.3  | Download and Install Packet Tracer                       | 
| 1.0.4  | Video – Getting Started in Cisco Packet Tracer           |
| 1.0.5  | Packet Tracer – Logical and Physical Mode Exploration    |
| 1.1    | Networks Affect our Lives                                |
| 1.1.1  | Networks Connect Us                                      |
| 1.1.2  | Video – The Cisco Networking Academy Learning Experience |
| 1.1.3  | No Boundaries                                            |
| 1.2    | Network Components                                       |
| 1.2.x  | Host roles, P2P, devices, media                          |
| 1.3    | Network Representations and Topologies                   |
| 1.3.x  | Network representations, topology diagrams               |
| 1.4    | Common Types of Networks                                 |  
| 1.4.x  | Network sizes, LANs/WANs, internet, intranet/extranet    |

---

## 1.0 Introduction & Packet Tracer

### 1.0.1 Why should I take this module?

This module is the starting point for my networking journey. It explains:

- How networks are designed, built, and maintained  
- Why networking is a core skill for any IT or cybersecurity role  
- That I’ll be using **Cisco Packet Tracer** to simulate real-world networks instead of only reading theory

### 1.0.2 What will I learn to do in this module?

The official objective is:

> **Explain the advances in modern network technologies.**

In practice, this means:

- Understanding how modern networks connect people, businesses, and services  
- Getting familiar with different network types and topologies  
- Learning how reliable networks are designed (scalability, fault tolerance, QoS, security)  
- Seeing how current trends (cloud, collaboration, mobile, etc.) rely on networking

### 1.0.3 Download and Install Packet Tracer

- Packet Tracer is Cisco’s network simulation tool.  
- I obtained it directly through the **Cisco Networking Academy** portal (Lab Downloads section).  
- After installation, it’s tied to my NetAcad account so I can open activities and sample networks.

### 1.0.4 Video – Getting Started in Cisco Packet Tracer

Key ideas from the “Getting Started” video:

- The interface has three main parts:
  - **Device selection & connections** – where I pick routers, switches, PCs, and cables  
  - **Interaction tools** – select, delete, inspect, label, group, etc.  
  - **File & settings** – open, save, load sample topologies, adjust preferences, logout
- If I’ve used any normal desktop software (like a document editor), the File menu feels familiar:
  - `Open`, `Save`, `Save As`, `Exit` all behave as expected  
  - `Open Samples` gives access to prebuilt sample networks  
  - `Exit and Logout` clears login info and forces the next user to log in again

This video is mainly about getting comfortable with the UI before touching any serious labs.

### 1.0.5 Packet Tracer – Logical and Physical Mode Exploration

This activity introduces a **small-to-medium business network** modeled in Packet Tracer.

What I did / will do here:

- Explore the **Logical view**:
  - See how the branch office and data center are connected  
  - Identify routers, switches, access points, servers, and end devices  
- Explore the **Physical view**:
  - Move between “cities”, “buildings”, and “wiring closets”  
  - See how racks, cabling, and devices are laid out in a more realistic way
- Interact with devices:
  - Click devices to inspect interfaces and basic configurations  
  - Trace how PCs are physically connected back to switches and routers  
- Answer guiding questions to verify understanding (even if I don’t fully understand all technologies yet)

The goal is **familiarity, not perfection** — getting used to navigating networks in both logical and physical perspectives.

---

## 1.1 Networks Affect Our Lives

### 1.1.1 Networks Connect Us

This section explains how important communication is for humans and how digital networks extend that:

- Our need to connect to other people sits just below basic survival needs like food and shelter.  
- Modern networks let us:
  - Share ideas almost instantly  
  - See news and discoveries in real time  
  - Play games and collaborate with friends worldwide

In other words, networking is not just cables and routers – it’s how modern social life, business, and entertainment actually work.

### 1.1.2 Video – The Cisco Networking Academy Learning Experience

This short video focuses on:

- Cisco’s long-term goal of educating and training people for the digital economy (since 1997).  
- The idea that “world changers are made, not born” — skills like networking and cybersecurity can be learned.  
- How NetAcad uses technology to create opportunities globally (not just in tech hubs).

For my portfolio, this shows the **official learning context** behind the technical content I’m studying.

### 1.1.3 No Boundaries

Key ideas from this section:

- Networking technologies are removing many traditional barriers:
  - Country borders, distance, and physical separation matter less  
  - People and companies can collaborate across time zones
- The **internet** has reshaped:
  - Social interaction  
  - Commerce and business  
  - Politics and global communication
- **Online communities** allow people to:
  - Learn together  
  - Share resources and ideas  
  - Join global projects regardless of location
- **Cloud services** mean:
  - Files, photos, and apps are accessible from almost any device  
  - I can work from home, on a train, or even in a park with the same data

From a cybersecurity perspective, this always-on connectivity increases both **opportunity** and **risk**, which is why understanding networking is so important.

---

## 1.2 Network Components

> Status: high-level theory understood, detailed lab work in progress.

This part introduces the basic building blocks that make a network function.

### 1.2.1 Host Roles

- A **host** is any device that sends or receives data on the network (PCs, laptops, servers, phones, etc.).  
- Hosts can act as:
  - **Clients** – consuming services (e.g., a browser getting a webpage)  
  - **Servers** – providing services (e.g., a web server, mail server, file server)

Understanding host roles is the first step in seeing how traffic flows in a network.

### 1.2.2 Peer-to-Peer (P2P)

- In a **peer-to-peer** setup, devices share resources directly with each other.  
- There is no dedicated central server — every host can be both client and server.  
- Good for very small networks or quick ad-hoc file sharing, but hard to secure and manage at scale.

### 1.2.3 End Devices

Examples of end devices:

- PCs, laptops, IP phones, tablets, smartphones  
- Printers, IP cameras, IoT sensors, smart TVs

End devices are where users actually interact with the network.

### 1.2.4 Intermediary Devices

These devices move, direct, or manage traffic between end devices:

- **Switches** – forward frames within a LAN  
- **Routers** – forward packets between different networks  
- **Wireless access points** – connect wireless devices into the wired network  
- **Firewalls** – inspect and filter traffic based on security policies

They’re the “infrastructure” that makes sure data gets from A to B reliably.

### 1.2.5 Network Media

Network media are the paths that data travels over:

- **Copper cables** – twisted pair (Ethernet), common in LANs  
- **Fiber-optic cables** – high bandwidth, long distance, backbone links  
- **Wireless** – radio waves (Wi-Fi, cellular, etc.)

Each medium has trade-offs in cost, speed, distance, and resistance to interference.

### 1.2.6 Check Your Understanding – Network Components

This is a short knowledge check to make sure I can:

- Identify end vs. intermediary devices  
- Distinguish different host roles (client, server, peer)  
- Recognize basic media types and where they are used

---

## 1.3 Network Representations and Topologies

### 1.3.1 Network Representations

This section explains why we draw networks instead of just listing devices:

- **Logical diagrams** show:
  - How devices are addressed  
  - How they’re grouped and which networks exist  
  - Routing and VLAN relationships
- **Physical diagrams** show:
  - Where devices are located in real life (racks, rooms, buildings)  
  - How cables are physically run

Good documentation is crucial for troubleshooting, upgrades, and security reviews.

### 1.3.2 Topology Diagrams

A **topology** is the layout of the network:

- **Physical topology** – real cabling and device placement  
- **Logical topology** – how data flows logically between devices
- Common topologies:
  - **Star** – devices connect to a central switch  
  - **Bus** – all devices share a single backbone (legacy)  
  - **Ring** – devices form a loop (legacy)  
  - **Mesh** – many interconnections for high redundancy  
  - **Hybrid** – mixtures used in real-world networks

### 1.3.3 Check Your Understanding – Network Representations and Topologies

Quick recap to verify that I can:

- Read basic topology diagrams  
- Explain the difference between logical and physical views  
- Recognize common topological patterns

---

## 1.4 Common Types of Networks

### 1.4.1 Networks of Many Sizes

Introduces networks at different scopes, for example:

- **Small/home networks** – a few devices, a single router  
- **Small office networks** – more devices, maybe a separate switch and access point  
- **Enterprise networks** – many switches, routers, Wi-Fi, and services across multiple sites  
- **Global networks** – service providers and the broader internet

The idea is that the same core principles scale from a single room to global infrastructure.

### 1.4.2 LANs and WANs

Key distinctions:

- **LAN (Local Area Network)**:
  - Limited geographic area (single building, floor, office, home)  
  - Typically owned and managed by one organization or person  
  - High-speed connections (Ethernet, Wi-Fi)
- **WAN (Wide Area Network)**:
  - Connects LANs over large distances  
  - Uses service provider infrastructure (ISP, telecom carrier)  
  - Often involves technologies like MPLS, leased lines, VPNs, etc.

### 1.4.3 The Internet

- A massive global network of networks.  
- Uses **TCP/IP** as the main protocol suite.  
- Provides access to web, email, file transfer, streaming, and countless applications.

From a security perspective, the internet is the most common source of external threats, which is why network design and segmentation are so important.

### 1.4.4 Intranets and Extranets

- **Intranet**:
  - A private network for internal use within an organization  
  - Often hosts internal tools, documentation, and business apps
- **Extranet**:
  - A controlled extension of the intranet  
  - Gives limited access to partners, suppliers, or customers

These concepts are central when designing access controls and secure connectivity between organizations.

### 1.4.5 Check Your Understanding – Common Types of Networks

This checkpoint ensures I can:

- Differentiate LAN vs WAN  
- Describe the internet vs an intranet vs an extranet  
- Relate network type to typical use cases (home, business, enterprise, global)

---

## How to Use This Repo

- Use the headings (1.0–1.4) to align with the official **Networking Today** module structure.  
- Treat this README as a **high-level map**:
  - Before studying – to know what’s coming  
  - After studying – to quickly review key concepts
- As I continue the module, I’ll extend this repo with:
  - More detailed notes for sections **1.5–1.10**  
  - Packet Tracer lab notes / configs  
  - Maybe diagrams or mindmaps for revision

---

## Disclaimer

- All trademarks and course names belong to Cisco Systems, Inc.  
- This repository contains **my own summaries and interpretations** and is not endorsed by Cisco.  
- No exam questions or proprietary content are reproduced; everything here is high-level study material only.
