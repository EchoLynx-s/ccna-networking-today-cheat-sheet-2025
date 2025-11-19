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

## Module 1 – Networking Today: Structure

| ID     | Title                                                   |
|--------|---------------------------------------------------------|
| 1.0    | Introduction                                            |
| 1.0.1  | Why should I take this module?                          |
| 1.0.2  | What will I learn to do in this module?                 |
| 1.0.3  | Download and Install Packet Tracer                      |
| 1.0.4  | Video – Getting Started in Cisco Packet Tracer          |
| 1.0.5  | Packet Tracer – Logical and Physical Mode Exploration   |
| 1.1    | Networks Affect our Lives                               |
| 1.1.1  | Networks Connect Us                                     |
| 1.1.2  | Video – The Cisco Networking Academy Learning Experience|
| 1.1.3  | No Boundaries                                           |
| 1.2    | Network Components                                      |
| 1.2.1  | Host Roles                                              |
| 1.2.2  | Peer-to-Peer                                            |
| 1.2.3  | End Devices                                             |
| 1.2.4  | Intermediary Devices                                    |
| 1.2.5  | Network Media                                           |
| 1.2.6  | Check Your Understanding – Network Components           |
| 1.3    | Network Representations and Topologies                  |
| 1.3.1  | Network Representations                                 |
| 1.3.2  | Topology Diagrams                                       |
| 1.3.3  | Check Your Understanding – Network Representations and Topologies |
| 1.4    | Common Types of Networks                                |
| 1.4.1  | Networks of Many Sizes                                  |
| 1.4.2  | LANs and WANs                                           |
| 1.4.3  | The Internet                                            |
| 1.4.4  | Intranets and Extranets                                 |
| 1.4.5  | Check Your Understanding – Common Types of Networks     |
| 1.5    | Internet Connections                                    |
| 1.5.1  | Internet Access Technologies                            |
| 1.5.2  | Home and Small Office Internet Connections              |
| 1.5.3  | Businesses Internet Connections                         |
| 1.5.4  | The Converging Network                                  |
| 1.5.5  | Packet Tracer – Network Representation                  |
| 1.6    | Reliable Networks                                       |
| 1.6.1  | Network Architecture                                    |
| 1.6.2  | Fault Tolerance                                         |
| 1.6.3  | Scalability                                             |
| 1.6.4  | Quality of Service                                      |
| 1.6.5  | Network Security                                        |
| 1.6.6  | Check Your Understanding – Reliable Networks            |
| 1.7    | Network Trends                                          |
| 1.7.1  | Recent Trends                                           |
| 1.7.2  | Bring Your Own Device (BYOD)                            |
| 1.7.3  | Online Collaboration                                    |
| 1.7.4  | Video Communications                                    |
| 1.7.5  | Video – Cisco Webex for Huddles                         |
| 1.7.6  | Cloud Computing                                         |
| 1.7.7  | Technology Trends in the Home                           |
| 1.7.8  | Powerline Networking                                    |
| 1.7.9  | Wireless Broadband                                      |
| 1.7.10 | Check Your Understanding – Network Trends               |
| 1.8    | Network Security                                        |
| 1.8.1  | Security Threats                                        |
| 1.8.2  | Security Solutions                                      |
| 1.8.3  | Check Your Understanding – Network Security             |
| 1.9    | The IT Professional                                     |
| 1.9.1  | CCNA                                                    |
| 1.9.2  | Networking Jobs                                         |
| 1.9.3  | Lab – Research IT and Networking Job Opportunities      |
| 1.10   | Module Practice and Quiz                                |
| 1.10.1 | What did I learn in this module?                        |
| 1.10.2 | Module Quiz – Networking Today                          |


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

This video explains what makes the Cisco Networking Academy different as a learning platform and why its approach fits the fast-changing tech world.

Key takeaways:

- **Tech never stops moving** – the world is “always moving, always changing,” and networking, security, programming, and IoT are at the center of that change. To keep up, education also has to evolve, not just repeat old theory.
- **Hands-on first** – NetAcad focuses on practical, lab-based learning with real equipment and software. Students aren’t just reading slides; they configure, break, and fix networks in a controlled environment.
- **Custom tools & simulators** – Cisco developed its own tools (like Packet Tracer) and simulators so students can:
  - Test ideas at scale in different virtual environments  
  - Experiment safely with complex topologies they wouldn’t have physical access to  
- **Competitions and hackathons** – Students can apply their skills in events that simulate real pressure: hacking challenges, competitions, and collaborative projects. This is where theory meets real-world problem solving.
- **Continuous feedback** – Learning is supported by:
  - Instructors giving direct, human feedback  
  - Automated, performance-based feedback built into labs and assessments  
  This helps students know immediately what they did right or wrong and where to improve.
- **Global and multilingual** – Courses are translated into up to **20 languages**, making it easier to learn in your native language while still collaborating with a worldwide community of students and teachers.
- **T-shaped professionals** – NetAcad aims to create “T-shaped” people:
  - Deep technical knowledge in one or two in-demand areas (e.g., networking, security)  
  - Broad skills to collaborate across related technologies, teams, and domains  
  This blend makes graduates more valuable to employers.
- **Career-focused** – The program is not just about passing a class:
  - It prepares students to join multidisciplinary teams working in networking, IoT, security, programming, and IT.  
  - Certifications and skills from NetAcad can translate directly into better jobs, higher pay, and long-term career growth.

For my own path, this video reinforces **why** I’m taking these modules: I’m not just learning commands, I’m building the T-shaped skill set needed for real networking and cybersecurity work in a world that’s constantly evolving.


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

To take part in a global online community, a device like your computer, tablet, or smartphone has to be connected to a network, usually the internet. Any device that participates directly in network communication is called a **host**. Hosts are often referred to as **end devices** and can act as either **clients**, **servers**, or both.

Each host on a network is identified by an **IP address**, which uniquely identifies that device and the network it belongs to. This addressing is what allows data to be sent to the correct destination.

A **server** is a host that provides services or resources to other devices. It runs dedicated server software, for example:
- **Email server** – handles email delivery and storage, which users access with mail client software (like Outlook).
- **Web server** – hosts websites and web applications, which users access through a browser (like Chrome or Firefox).
- **File server** – stores user and corporate files centrally so clients can access and share them over the network.

A **client** is a host that requests and uses those services. The same physical device can run multiple client applications at once (e.g., checking email, browsing the web, and using file shares at the same time). In short, servers provide, clients consume, and both are simply different roles played by network hosts.


### 1.2.2 Peer-to-Peer (P2P)

In a typical client–server network, servers and clients are separate machines. In a **peer-to-peer (P2P)** network, the same computer can act as both a client and a server at the same time. This is common in homes and very small businesses, where PCs share resources directly with each other instead of relying on a dedicated server.

A simple example: one PC shares a **printer** that is connected via USB, while another PC shares **files** over the network. Each device has a network interface card (NIC) and can both request resources from others and offer its own resources.

P2P networks are:

- **Easy and cheap** to set up – no special server hardware is required.
- **Less complex** – good for basic tasks like file sharing and printer sharing.

But they also have drawbacks:

- **No central administration** – managing users, backups, or updates is harder.
- **Weaker security** – each device must be secured individually.
- **Not very scalable** – as more devices join, management and performance suffer.
- **Mixed roles** – devices acting as both client and server can slow down under load.

Overall, P2P is fine for small, simple environments but not suitable for larger or security-sensitive networks.


### 1.2.3 End Devices

**End devices** are the network devices people interact with directly – PCs, laptops, IP phones, printers, servers, etc. They sit at the “edge” of the network.

Each end device has a unique network **address** (for example, an IP address). When one device wants to communicate with another, it uses the destination device’s address so the network knows where to deliver the data.

In any conversation over a network:

- An end device is always the **source** (where the data starts)  
- Another end device is the **destination** (where the data is meant to arrive)  

Between those points, the message can cross multiple networks and take different possible paths through routers and switches. But the important part is that:

> Data **originates** at an end device, **travels through** the network, and **arrives** at another end device.

Routers and switches just move the traffic; end devices are where users actually send and receive information.

### 1.2.4 Intermediary Devices

**Intermediary devices** sit between end devices and keep the network itself running. They:

- Connect individual end devices to the network  
- Connect multiple networks together to form an **internetwork**  
- Decide how data should travel from source to destination

Examples include:

- Wireless routers  
- LAN switches and multilayer switches  
- Routers  
- Firewall appliances  

Using the destination address and their knowledge of the network’s links, intermediary devices choose the best path for each message. Along the way they can:

- Regenerate and retransmit signals so data can travel further  
- Maintain information about available paths through the network  
- Report errors and communication failures  
- Reroute traffic if a link goes down  
- Prioritize certain types of traffic (quality of service)  
- Allow or block traffic based on security rules (firewalling)

In short, end devices create and consume data, while intermediary devices **move, protect, and manage** that data across the network.


### 1.2.5 Network Media

Network **media** is the physical or wireless channel that data uses to travel from one device to another. Whenever information moves across a network, it must pass through some type of medium. Modern networks primarily rely on **three major media types**:

#### **1. Copper Cables**
- Data is transmitted as **electrical signals**.
- Commonly used in Ethernet networks (e.g., Cat5e, Cat6).
- Affordable and easy to install, but limited by distance and susceptible to interference.

#### **2. Fiber-Optic Cables**
- Data is transmitted as **pulses of light** through glass or plastic fibers.
- Supports extremely high bandwidth and long-distance communication.
- Immune to electrical interference, making it ideal for backbone connections and high-performance networks.

#### **3. Wireless Transmission**
- Data travels through the air using **radio waves**.
- Used in Wi-Fi, Bluetooth, cellular networks, and wireless point-to-point links.
- Offers mobility and convenience but is more affected by interference and security risks.

---

### Choosing the Right Media

When selecting network media, four major factors must be considered:

1. **Distance** — How far must the signal travel?  
2. **Environment** — Is the installation area prone to interference, moisture, or physical obstacles?  
3. **Data requirements** — How much data needs to be transferred and at what speed?  
4. **Cost** — What is the budget for both the material and the installation?

Each medium has its own strengths, making them suitable for different use cases—from home Wi-Fi to enterprise fiber backbones.

### 1.2.6 Check Your Understanding – Network Components

This short quiz is there to make sure the core ideas from **1.2 Network Components** are clear before moving on.

The questions focus on three key points:

- **What we call devices that participate directly in communication**  
  You need to recognize that all computers and similar devices that send/receive data on the network are referred to as *hosts*.

- **How different media carry data**  
  One question checks that you can match the medium to how data is encoded—for example, knowing which type of cable carries data as **pulses of light** (fiber-optic).

- **Which devices are intermediary devices**  
  You also confirm that you can distinguish end devices from the infrastructure devices in the middle of the network—specifically, identifying things like **routers and switches** as intermediary devices rather than hosts or servers.

Overall, this checkpoint makes sure you can correctly name the main components of a network and understand their basic roles before you dive deeper into later sections.


---

## 1.3 Network Representations and Topologies

### 1.3.1 Network Representations

Network architects and admins need a clear “picture” of how devices are laid out and connected. Instead of drawing realistic photos, they use **standard symbols** to represent:

- **End devices** – desktops, laptops, printers, IP phones, tablets, TelePresence units  
- **Intermediary devices** – wireless routers, LAN switches, multilayer switches, routers, firewalls  
- **Network media** – wireless links, LAN links, WAN links  

All of this together forms a **topology diagram**: a visual map that shows which devices exist, where they sit in the design, and how they connect. Being able to read these diagrams is essential for understanding how a network is organized and how it operates.

The section also introduces key connection terms:

- **Network Interface Card (NIC)** – hardware inside an end device that physically connects it to the network.  
- **Physical port** – the actual connector on a device where a cable or other media plugs in.  
- **Interface** – a specialized port on a networking device that connects to a specific network (router ports are called network interfaces).

> In practice, *port* and *interface* are often used interchangeably, but they both refer to the connection point between a device and the network.


### 1.3.2 Topology Diagrams

**Topology diagrams** are mandatory documentation for anyone working with a network. They provide a visual map of how devices are arranged and how everything is connected. This section introduces the two main types:

#### Physical Topology Diagrams
- Show the **real-world location** of devices and cabling.
- You can see:
  - Which devices are in the **server room**, **IT office**, or **classrooms**
  - How racks, shelves, and rooms are organized
  - How switches, routers, and servers are physically wired together
- Useful for installation, troubleshooting physical issues, and planning moves or changes.

#### Logical Topology Diagrams
- Focus on **how the network operates**, not where devices sit physically.
- Show:
  - IP networks and subnets (e.g., `192.168.10.0`, `192.168.100.0`)
  - Which end devices connect to which switches and router interfaces
  - Interface labels (Fa0/1, G0/1, etc.) and how traffic logically flows
- Used for understanding routing, addressing, VLANs, and overall design.

Both views describe the **same network**, just from different angles:
- Physical = *“Where is everything and how is it cabled?”*  
- Logical = *“Which networks exist and how does data move between them?”*

Being able to read and switch between these two types of diagrams is a core networking skill.

### 1.3.3 Check Your Understanding – Network Representations and Topologies

This review quiz makes sure you understand the key terminology from **1.3.1** and **1.3.2** before moving on.

It focuses on three main ideas:

1. **How end devices physically connect to the network**  
   - You need to know that the hardware component inside the device that actually plugs it into the network is the **network interface card (NIC)**.  
   - Ports and interfaces exist on networking devices, but the NIC is what gives an end device its physical network connection.

2. **Specialized ports on networking devices**  
   - On routers and switches, certain ports are **interfaces** that connect to specific networks or segments.  
   - These interfaces are what we label `Fa0/1`, `G0/1`, etc., and they’re used when drawing logical topologies and configuring routing.

3. **Physical vs logical topologies**  
   - One question checks that you know which topology view shows **which end devices are connected to which intermediary devices and what media is used** → that’s the **logical** view.  
   - Another checks which view shows the **actual physical location of devices and cabling** → that’s the **physical** topology.

Overall, this section confirms that you can:

- Use the terms **NIC**, **port**, and **interface** correctly  
- Distinguish clearly between **physical** and **logical** topology diagrams and what each one is used for.

---

## 1.4 Common Types of Networks

### 1.4.1 Networks of Many Sizes

Now that the components and diagrams are clear, this section looks at **how big a network can be** and what that means in practice. Networks range from a couple of devices at home to huge global infrastructures connecting millions of systems.

- **Small home networks**  
  - Connect a few devices (PCs, phones, printers, smart TVs, consoles) to each other and to the internet.  
  - Mainly used for web browsing, streaming, gaming, and basic file/print sharing.

- **Small office / home office (SOHO) networks**  
  - Used by remote workers, freelancers, or very small businesses.  
  - Provide access to centralized resources (like a company network, cloud services, or shared printers) from a home or small office.

- **Medium to large networks**  
  - Typical for schools, corporations, and large organizations.  
  - Can span multiple floors, buildings, or sites with **hundreds or thousands of hosts**.  
  - Rely on more structured design: multiple switches, routers, servers, and security devices.

- **Worldwide networks**  
  - The **internet** is the largest example: a true *“network of networks”* made up of countless private and public networks interconnected globally.  
  - Organizations use their connection to the internet to deliver products, services, and applications to users everywhere.

In smaller environments (home and very small businesses), individual computers often act as both clients and servers in a **peer-to-peer** style. As networks grow, they move towards more centralized, managed designs to handle scale, security, and reliability.


### 1.4.2 LANs and WANs

Network infrastructures differ in:

- The **area** they cover  
- The **number of users/devices**  
- The **services** they provide  
- Who is **responsible** for managing them  

The two core types introduced here are **LANs** and **WANs**.

#### Local Area Networks (LANs)

A **LAN** is a network that spans a **small geographic area**, for example:

- A home, small office, school, single building, or campus  

Key characteristics:

- Connects end devices within a limited area (PCs, printers, phones, etc.)  
- Usually owned and managed by **one organization or person**  
- Provides **high-speed bandwidth** between local devices  
- Used for everyday internal communication, file sharing, printing, VoIP, etc.

A home network or a small company network in one building is typically a LAN.

#### Wide Area Networks (WANs)

A **WAN** links **multiple LANs** over a **large geographic area**, such as:

- Different cities, regions, countries, or continents  

Key characteristics:

- Connects LANs using long-distance links (leased lines, MPLS, VPN over the internet, etc.)  
- Usually built and managed by **telecom or internet service providers (ISPs)**  
- Often has **lower speeds** than internal LAN links, because long-distance and shared infrastructure are involved  

In the diagram, each branch office has its **own LAN**, and those LANs are interconnected through a WAN “cloud”. Together, LANs and WANs form the overall network that organizations and users rely on every day.

### 1.4.3 The Internet

The **internet** is a massive, worldwide collection of interconnected networks – literally an *“internetwork”* of many LANs and WANs. You can think of it as:

> Home LANs, school LANs, business LANs, hospital LANs, government LANs, etc., all linked together through WAN services.

Key points:

- Individual **LANs** connect to **WANs** using various media (copper, fiber, wireless).
- Those WANs then interconnect with each other, forming the global internet.
- No single person, company, or government **owns** the internet. It’s a shared infrastructure built from many independent networks.

To keep this huge system working, different organizations define and maintain **standards and rules**, for example:

- **IETF** (Internet Engineering Task Force) – develops internet protocols and technical standards.
- **ICANN** (Internet Corporation for Assigned Names and Numbers) – manages domain names and IP address allocation.
- **IAB** (Internet Architecture Board) – provides architectural oversight for internet standards.

Because everyone follows these common standards, devices and networks all over the world can communicate reliably, regardless of who owns them.

### 1.4.4 Intranets and Extranets

Besides the public **internet**, organizations also use **intranets** and **extranets**:

#### Intranet – “Company Only”
An **intranet** is a private network built from an organization’s own LANs and WANs.

- Accessible only to **employees or authorized internal users**.  
- Used for internal apps like HR portals, internal email, document sharing, ticketing systems, etc.  
- Sits behind firewalls and access controls so the public cannot reach it directly.

#### Extranet – “Trusted Outsiders”
An **extranet** extends part of the intranet to **trusted external users** who work with the organization.

Examples:

- A company giving **suppliers and contractors** access to order status and inventory.  
- A hospital allowing **doctors** to book appointments or view schedules remotely.  
- A local education office sharing **budget and staffing information** with schools in its district.

These users are outside the company but get controlled, secure access to specific resources.

#### Relationship to the Internet

You can picture it as three concentric circles:

- **Intranet** – innermost circle, **company only**  
- **Extranet** – middle circle, **suppliers/customers/collaborators**  
- **Internet** – outer circle, **the whole world**

Security and access controls determine who can move from the public internet into the extranet and then (if allowed) further into the intranet.


### 1.4.5 Check Your Understanding – Common Types of Networks

This quiz validates that you can correctly match each **network type** to its purpose and scope.

It checks that you understand:

- **LAN (Local Area Network)**  
  A network that connects users and end devices within a **small geographic area** such as a home, small office, or department inside a building.

- **Extranet**  
  The infrastructure used when an organization wants to give **secure access to its resources to people in another organization** (suppliers, partners, customers) while still keeping control.

- **WAN (Wide Area Network)**  
  A network that provides connectivity over a **large geographic area**, usually built and managed by a **telecommunications or internet service provider**, and used to interconnect multiple LANs.

The goal of this section is to confirm you can clearly distinguish **LAN vs WAN** and **intranet vs extranet** based on who uses the network and how large an area it covers.

---
## 1.5. Internet Connections

### 1.5.1 Internet Access Technologies

Once you know what networks are, the next question is: **how do users and organizations actually get onto the internet?**

- **Home users, teleworkers, and small offices**  
  - Usually connect through an **Internet Service Provider (ISP)**.  
  - Common access options:
    - **Broadband cable**
    - **DSL (Digital Subscriber Line)**
    - **Wireless WAN / cellular**
    - Other mobile/broadband services depending on location and ISP

- **Organizations and larger businesses**  
  - Need connectivity both to the **internet** and to **other corporate sites**.  
  - Links must support high-bandwidth services like:
    - IP telephony (VoIP)
    - Video conferencing
    - Access to data centers and storage
  - Service providers offer **business-class connections**, such as:
    - Business DSL
    - **Leased lines**
    - **Metro Ethernet**

The key idea: different users (home vs business) need different types and qualities of internet access, and service providers offer a range of technologies to match those needs.

---

### 1.5.2 Home and Small Office Internet Connections

This section zooms in on common internet options for **home**, **teleworkers**, and **small offices**, all connecting to an ISP.

The main technologies:

- **Cable**
  - Delivered over the **same coaxial cable** used for cable TV.
  - High bandwidth, high availability, and **always on**.
  - Very common in residential and small office environments.

- **DSL (Digital Subscriber Line)**
  - Runs over **traditional telephone lines**.
  - Also high bandwidth, high availability, and always on.
  - SOHO users typically use **ADSL (Asymmetric DSL)** – download speed is higher than upload speed.

- **Cellular**
  - Uses the **mobile phone network** (4G/5G, etc.).
  - Works anywhere you have a cellular signal.
  - Performance depends on both the device and the cell tower.

- **Satellite**
  - Ideal for **remote areas** with no other broadband options.
  - Requires a **clear line of sight** to the satellite via a dish.
  - Often has higher latency but provides connectivity where nothing else does.

- **Dial-up Telephone**
  - Uses any standard phone line and a **modem**.
  - Very low bandwidth; not suitable for large data transfers.
  - Mostly legacy now, but can still be used for basic connectivity while traveling.

Which option is used depends heavily on **geographic location** and **what local ISPs offer**.

### 1.5.3 Business Internet Connections

Businesses have different needs than home users: they often require **higher bandwidth**, **dedicated capacity**, and **managed services** to support critical applications (VoIP, video conferencing, data centers, VPNs, etc.). The exact options depend on local service providers, but common business connections include:

- **Dedicated Leased Lines**  
  - Private circuits reserved within the service provider’s network.  
  - Used to connect **geographically separated offices** for voice and data.  
  - Rented on a monthly or yearly basis and offer predictable performance and SLAs.

- **Metro Ethernet (Ethernet WAN)**  
  - Extends familiar **Ethernet LAN technology** into the WAN.  
  - Used in metropolitan areas to provide high-speed connections between sites or from a site to the provider’s network.  
  - Simplifies integration with existing LAN infrastructure.

- **Business DSL**  
  - Similar to consumer DSL but offered in **business-class variants**.  
  - A common option is **Symmetric DSL (SDSL)**, which provides **equal upload and download speeds**—important for services like VPNs, hosting, and collaboration.

- **Satellite**  
  - Used when no suitable wired options exist (remote branches, rural locations).  
  - Provides connectivity where other business-class services are unavailable, though with higher latency.

As with home users, the final choice depends heavily on **geography** and **service provider availability**, but business links are designed to deliver more reliable, SLA-backed connectivity.

### 1.5.4 The Converging Network

In the past, organizations often ran **separate networks** for different services:

- A **data network** for computers  
- A **telephone network** for voice calls  
- A **video/broadcast network** for TV or CCTV  

Each one:

- Used its **own cabling and technology**
- Had its own **rules, protocols, and standards**
- Could not communicate with the others

Result: multiple services meant **multiple parallel networks** to install, maintain, and troubleshoot.

---

### From Separate to Converged

Modern infrastructures are **converged networks**:

- A **single physical network** (same cabling, switches, routers)  
- Carries **data, voice, and video** together  
- Uses **one common set of protocols and standards** (e.g., IP-based)

On a converged network:

- IP phones, PCs, servers, and video systems all share the **same backbone**  
- Multiple services run over **one infrastructure**, which simplifies:
  - Deployment and management  
  - Scalability and upgrades  
  - Integration between services (e.g., video conferencing, VoIP, data sharing)

In short, converged networks replace three separate networks with **one smart network** that can transport many types of communication at the same time.

### 1.5.5 Packet Tracer – Network Representation

This activity uses a Packet Tracer topology that looks like a small–to–medium business network. The goal is not to configure everything, but to **read** the diagram like a network engineer and connect it back to what you’ve learned so far.

#### What this activity is about

- Recognize **end devices**, **intermediary devices**, and **network media** in Packet Tracer.
- Practice the **client–server model** using the Server-PT device.
- Revisit the differences between **LANs** and **WANs** inside a realistic topology.
- Start thinking like a designer: *“What would I add or change to make this network work?”*

#### Part 1 – Identifying components

You explore the **icon toolbar** in Packet Tracer and the existing topology to:

- Find the categories for **intermediary devices**, **end devices**, and **connections** (media).
- Count:
  - How many **endpoint devices** (only one link) appear in the topology.
  - How many **intermediary devices** (multiple links) there are.
  - How many **end devices are not desktop PCs**.
  - How many **types of media** are used (copper, fiber, wireless, etc.).

The idea is to train your eye to quickly distinguish device roles and link types just by looking at the diagram.

#### Part 2 – Understanding device roles

Here you connect the visual representation to networking concepts:

- Use **Server-PT** as the example of a server and explain the **client–server model** in your own words:
  - Servers provide services (web, file, email, etc.).
  - Clients request and consume those services.
- List at least two functions of **intermediary devices** (e.g., routing traffic, regenerating signals, enforcing security/QoS).
- List at least two criteria for choosing a **media type** (distance, environment, bandwidth requirements, cost).

This ties together earlier sections on hosts, intermediary devices, and media, but now in a concrete Packet Tracer network.

#### Part 3 – LANs, WANs, and the Internet

Next, you compare what you see in the topology with the theory:

- Explain the difference between a **LAN** and a **WAN** and give real-world examples of each.
- Count how many **WANs** and how many **LANs** are present in the activity.
- Briefly describe the **internet** (a huge, global collection of interconnected networks).
- List common ways **home users** connect to the internet (cable, DSL, cellular, etc.).
- List common **business** connectivity methods in your region (leased lines, Metro Ethernet, business DSL, etc.).

#### Challenge section

Finally, you’re encouraged to experiment:

- Add a **new end device**, connect it to a LAN, and figure out what extra configuration it needs to communicate.
- Add a **new intermediary device** and think about what has to be configured for it to correctly forward traffic.
- In a fresh Packet Tracer file, build your own mini–network with **two LANs connected by a WAN**, using the original activity as inspiration.

The goal isn’t to master all configs yet—it’s to get comfortable **reading, extending, and reasoning about** realistic network diagrams in Packet Tracer.


---
## 1.6. Reliable Networks

### 1.6.1 Network Architecture

This section introduces the idea of **network architecture** – the overall design principles that make a modern network work well. A good architecture is built to provide:

- **Fault tolerance** – the network keeps working even when devices or links fail.  
- **Scalability** – new users, devices, and whole networks can be added without redesigning everything.  
- **Quality of Service (QoS)** – important traffic (like voice or video) gets the performance it needs.  
- **Security** – both the infrastructure and the data it carries are protected.

The rest of 1.6 breaks these four characteristics down in more detail.

---

### 1.6.2 Fault Tolerance

A **fault-tolerant** network continues to operate even if something breaks.

- Uses **redundant connections and devices** so there are **alternative paths** when a link or router fails.
- Routing protocols can automatically reroute traffic over the remaining paths.
- From the user’s point of view, the failure is often **invisible**—applications keep working and calls or sessions are not interrupted.

In short: design for **no single point of failure** so that hardware issues don’t take the whole network down.

---

### 1.6.3 Scalability

A **scalable** network can grow quickly without hurting existing users.

- New users, devices, and even entire **new networks** can be connected without performance degradation.
- This is possible because designers follow **open standards and protocols**, so new equipment can slot into the existing design.
- Vendors can focus on improving speed and features rather than reinventing basic connectivity rules.

Result: as an organization expands, the network can expand with it **without needing a full redesign**.

---

### 1.6.4 Quality of Service (QoS)

As data, voice, and video all share the same converged network, **not all traffic is equal**.

- **QoS** is about managing **congestion** and ensuring that time-sensitive traffic (like **VoIP calls or live video**) gets priority over less critical traffic (like bulk file transfers or web browsing).
- When bandwidth demand is higher than what’s available, routers can:
  - Classify traffic
  - Queue it appropriately
  - Give **higher priority** to certain flows (e.g., voice) so they stay smooth and uninterrupted.

Key point: QoS prioritizes traffic **by type and importance**, not by content.

---

### 1.6.5 Network Security

Network infrastructure and the data it carries are valuable targets, so security has two main angles:

1. **Infrastructure security**  
   - Physically securing routers, switches, and other network devices.  
   - Limiting who can access management interfaces.  
   - Using hardware and software protections (firewalls, ACLs, IPS, etc.).

2. **Information security**  
   - Protecting the **data in transit** and the data stored on networked devices.

To achieve this, network security follows the **CIA triad**:

- **Confidentiality** – only authorized users can view the data.  
- **Integrity** – data is not altered in transit; it arrives exactly as sent.  
- **Availability** – authorized users have timely, reliable access to network services and data.

Together, these measures protect both the network itself and the information moving across it.

---

### 1.6.6 Check Your Understanding – Reliable Networks

This quiz checks whether you can connect the four core characteristics of a **reliable network** to real design choices:

- **Scalability** – Achieved when designers follow **open standards and protocols**, making it easy to plug in new devices and networks without redesigning everything.
- **Security** – Tied to the **CIA triad**: confidentiality, integrity, and availability. These three requirements define what “secure” means for data and services.
- **Quality of Service (QoS)** – The policy a router uses to **prioritize certain traffic types**, such as giving VoIP calls higher priority than web browsing when the network is congested.
- **Fault tolerance** – Provided by **redundancy**: having multiple paths to a destination so that if one device or link fails, traffic can automatically use an alternate route.

Together, these questions confirm that you understand not just the definitions, but how each characteristic shows up in real network designs.

---

### 1.7 Network Trends

Modern networks don’t just move data between PCs. They have to support a growing mix of devices, apps, and services: phones, tablets, video meetings, cloud apps, smart homes, and more. This section introduces the big trends you need to recognize as a NetAcad / CCNA student.

---

#### 1.7.1 Recent Trends

**Key idea:** Networks must evolve constantly as new end-user devices and applications appear.

You should be able to name and briefly explain these current trends:

- **BYOD (Bring Your Own Device)** – users connect personal phones, laptops, and tablets to the business or campus network.
- **Online collaboration** – teams use shared tools (chat, whiteboards, file sharing) to work together from anywhere.
- **Video communications** – video calls and conferencing for meetings, learning, and entertainment.
- **Cloud computing** – applications and storage delivered from remote data centers over the internet.
- **Technology trends in the home** – “smart home” devices (ovens, lights, cars, etc.) connected to the network and cloud.
- **Powerline networking** – using existing electrical wiring to extend the home LAN.
- **Wireless broadband** – high-speed wireless access where wired connections are difficult or unavailable.

---

#### 1.7.2 Bring Your Own Device (BYOD)

**Key idea:** *Any device, any ownership, anywhere* on the network.

- Employees and students use **personally owned** devices (laptops, tablets, smartphones, e-readers) on the organization’s network.
- Devices may be bought by the company, the user, or both.
- BYOD increases flexibility and productivity: people can work with the tools they already know.
- It also creates **management and security challenges**, because IT must:
  - Support many OSes and device types.
  - Control and secure access for personal devices.

Remember: **BYOD = any device, with any ownership, used anywhere.**

---

#### 1.7.3 Online Collaboration

**Key idea:** Networks are also for people to **work together in real time**, not just access data.

- **Collaboration** = working with others on a shared project or goal.
- Tools like **Cisco Webex / Webex Teams** provide:
  - Instant messaging and presence.
  - Voice and video meetings.
  - Screen sharing, whiteboards, and file sharing.
  - Persistent “spaces” (rooms) that keep a history of messages and content.
- Organizations rely on collaboration tools to stay competitive and support:
  - Remote workers.
  - Distributed project teams.
  - Group work in education (students helping each other, team assignments, etc.).

---

#### 1.7.4 Video Communications

**Key idea:** Video is now a critical part of communication and collaboration.

- Used for:
  - **Business communication** – meetings, interviews, project updates.
  - **Collaboration** – online classes, workshops, remote whiteboarding.
  - **Entertainment** – streaming, live events.
- Works **from anywhere** with an internet connection, local or global.
- Video conferencing lets organizations communicate across:
  - Different cities and countries.
  - Different cultures and time zones.
- Because video is **high-bandwidth and time-sensitive**, networks must be designed to handle it (QoS, enough capacity, low latency).

---

#### 1.7.5 Video – Cisco Webex for Huddles

**Key idea:** Collaboration tools integrate into everyday workspaces.

The Webex “huddles” video illustrates:

- Small teams gather in **huddle rooms** with a shared screen/board.
- They draw, write, and share content while remote participants join over video.
- Everyone sees the same content in real time, whether in the room or remote.

Takeaway: modern networks + tools like Webex enable **fast, informal collaboration** without needing big conference rooms.

---

#### 1.7.6 Cloud Computing

**Key idea:** Applications and data live in **remote data centers (“the cloud”)**, accessed over the internet.

For **individuals**:

- Store files and backups online (photos, docs, etc.).
- Use cloud-based apps (word processing, photo editing) directly in a browser.

For **organizations**:

- Extend IT without buying hardware or hiring more staff.
- Pay for computing, storage, and software **on demand**.
- Deliver services securely to any device, anywhere in the world.

Cloud providers build and operate **large data centers** and often:

- Store data in **multiple locations** for reliability and fault tolerance.
- Handle power, cooling, physical security, and hardware maintenance.

**Cloud types to know:**

- **Public cloud**
  - Services available to the general public over the internet.
  - Often pay-per-use or free tier (e.g., public online storage).
- **Private cloud**
  - Cloud for a **single organization** (e.g., a government).
  - Built on the organization’s own network or hosted with strict access controls.
- **Hybrid cloud**
  - Combines **two or more clouds** (for example, part private, part public).
  - All parts are connected using one architecture.
  - Users can access different services based on their rights.
- **Community cloud**
  - Shared by organizations with similar needs (e.g., multiple hospitals).
  - Customized for specific **security, privacy, and compliance** requirements.

---

#### 1.7.7 Technology Trends in the Home (Smart Home)

**Key idea:** Networking is transforming everyday life through **smart home technology**.

Smart devices built into appliances and systems can:

- Connect to each other and to cloud services.
- Be controlled via smartphone or tablet, locally or remotely.
- Adjust behavior automatically based on schedules and sensors.

Example (smart oven):

- You prepare food and put it in the oven before leaving.
- The oven ties into your **calendar** to choose when to start cooking.
- It can change cook time/temperature if your schedule changes.
- When food is ready, it sends an **alert** to your phone.

As high-speed internet becomes more common, expect more connected:

- Lights, thermostats, security systems.
- Cars, charging stations, and other home devices.

---

#### 1.7.8 Powerline Networking

**Key idea:** Use **existing electrical wiring** as a network medium inside the home.

- A **powerline adapter** plugs into a wall outlet and the network device.
- Data is sent over the same wires that carry electricity, using special frequencies.
- No new data cables are needed; power usage barely changes.

Benefits:

- Reach rooms where Wi-Fi signals are weak or blocked.
- Avoid running long Ethernet cables through walls.

Limitations:

- Not a full replacement for dedicated network cabling or Wi-Fi.
- Best seen as an **alternative/backup** when cable or wireless isn’t practical.

---
### 1.7.9 Wireless Broadband

**Wireless Internet Service Provider (WISP)**  
- An ISP that connects subscribers to a **designated access point / hot spot** using **wireless LAN–type tech**.  
- Common in **rural areas** where DSL or cable are not available.  
- Subscriber has a **small dish/antenna** on the roof, connected to the **home’s wired network**.  
- From the user’s view it feels like DSL/cable; the **difference is the last-mile link is wireless**, not a physical cable.

**Wireless Broadband Service (for home & small business)**  
- Uses the **same cellular technology as smartphones**.  
- An **external antenna** on the house provides **wireless or wired connectivity** to devices inside.  
- Competes directly with **DSL and cable** in many regions.

---

### 1.7.10 Check Your Understanding – Network Trends

**Q1. Which feature is a good conferencing tool to use with others who are located elsewhere in your city, or even in another country?**  
 **Answer: _Video communications_**  

**Q2. Which feature describes using personal tools to access information and communicate across a business or campus network?**  
 **Answer: _BYOD (Bring Your Own Device)_**  

**Q3. Which feature contains options such as Public, Private, Custom, and Hybrid?**  
 **Answer: _Cloud computing_**  

**Q4. Which feature is being used when connecting a device to the network using an electrical outlet?**  
 **Answer: _Powerline_**  

**Q5. Which feature uses the same cellular technology as a smartphone?**  
 **Answer: _Wireless broadband_**

 ---
 ## 1.8.3 Network Security – Quiz Helper (No direct answers)

> Use these hints to choose the right option yourself. I’ll tell you **what concept** the question is about and why the other options don’t fit.

---

### Q1 – Which attack slows down or crashes equipment and programs?

This question is about an attack whose **main goal is to overload resources** so that normal work can’t be done.

- Think of an attacker **flooding a server or network** with so much traffic or so many requests that:
  - programs hang,
  - the device becomes super slow or
  - it outright crashes.
- In the chapter, this was described as an attack on **availability**, not about stealing data or sneaking in quietly.

Why the other choices don’t match:
- A **firewall** is a *defense*, not an attack.
- The **“first-day attack” term** is about *when* a vulnerability is exploited, not specifically about crashing systems by overload.
- **Encrypted remote connections** are about secure access, not attacks.
- **Viruses/worms/Trojans** are malicious code installed on devices; they can cause damage, but the classic exam phrase “slow down or crash equipment and programs” in networking context points to traffic flooding.

---

### Q2 – Which option creates a secure connection for remote workers?

Here they want the technology that lets someone **work from home or on the road** and still safely reach the company network.

Key idea:
- It creates an **encrypted tunnel over the internet** between the remote user and the company.
- From the user’s point of view, it’s like their laptop is “virtually inside” the office network.

Why the others don’t fit:
- Malware types (virus/worm/Trojan) obviously don’t *secure* anything.
- A **firewall** protects the perimeter but isn’t itself the remote access connection.
- The **“first-day attack” term** and the **overloading attack** are both *threats*, not remote-access solutions.

---

### Q3 – Which option blocks unauthorized access to your network?

Now they’re asking for the **device or feature that sits at the edge** of the network and decides what is allowed in or out.

Think of:
- A system that enforces **rules based on IP addresses, ports, applications**, etc.
- It **permits or denies traffic** according to a security policy.

Why the others don’t match:
- Malware categories are attacks, not defenses.
- The **remote-worker tunnel** provides secure access *for authorized users*, but it doesn’t by itself filter all incoming traffic.
- The **overloading attack** and the **“first-day attack”** are both threats, not protective mechanisms.

---

### Q4 – Which option describes an attack that occurs on the first day a vulnerability becomes known?

This one is almost straight from the text:

- It’s about an exploit that hits **before patches or signatures exist**.
- Security tools haven’t had time to be updated, so the attack happens **“on day zero”** of the vulnerability’s public life.

Why others don’t fit:
- Malware like viruses/worms/Trojans can exist for years; the question is specifically about **timing** relative to discovery.
- The resource-overload attack focuses on **flooding** and service disruption, not timing.
- A **firewall** and **remote-access tunnel** are defenses, not attacks.

---

### Q5 – Which option describes malicious code running on user devices?

Here they want the **category name for harmful programs**:

- It covers things that:
  - replicate or spread by themselves,
  - lie hidden inside “normal looking” software,
  - can steal data, damage files, or join the computer to a botnet.
- These run **on the endpoint itself** (PC, laptop, phone), not just on the network.

Why the others don’t fit:
- The **remote-worker tunnel** and **firewall** are defensive tools.
- The **“first-day attack”** describes timing of an exploit, not the form of the code.
- The **overloading attack** is about flooding resources over the network, not malicious programs installed on the host.

---

Use these descriptions to match each question with the option in your quiz UI. 😉

---
## 1.9 The IT Professional

### 1.9.1 CCNA

**Big idea:**  
CCNA is Cisco’s *entry-level networking certification* that proves you understand core networking and stay relevant as technology changes.

**Why it matters**

- Shows you know **foundational networking technologies** and can support **next-gen networks**.
- Recognized world-wide by employers → often used as a **baseline requirement** for junior network jobs.

**Current CCNA structure**

- **Three courses + one exam** (for networking engineers).
- Focus areas:
  - **IP networking fundamentals**
  - **Security basics**
  - **Wireless**
  - **Virtualization & cloud-related concepts**
  - **Automation & programmability** (using APIs / controllers)

**Beyond CCNA**

- **Cisco DevNet certifications**
  - Levels: **Associate, Specialist, Professional**.
  - Focus: **software development, automation, programmability** for networks.
- **Specialist certs** (example mentioned):  
  - *Cisco Enterprise Advanced Infrastructure Specialist* – validates deeper skills on specific technologies.
- **No formal prerequisites**
  - You can start at associate, specialist, professional, or expert level whenever you’re ready.
- **Continuing education**
  - You can renew CCNA and higher certs using **CE credits** and further training instead of only re-taking exams.

---

### 1.9.2 Networking Jobs

**Goal:** understand how CCNA maps to real jobs and how to search for them.

**Where to look**

- **NetAcad Careers** on `netacad.com`
  - Use **Talent Bridge Matching Engine** to find:
    - Jobs at **Cisco**
    - Jobs at **Cisco partners and distributors**
    - Roles explicitly looking for **NetAcad students/alumni**
- General job boards:
  - **Indeed, Glassdoor, Monster**, etc.
  - Useful search terms:
    - *IT*, *Network Administrator*, *Network Engineer*
    - *Network Architect*
    - *Computer Systems Administrator*
    - *Cisco CCNA* (or other cert keywords)

**How CCNA helps**

- Prepares you for **entry-level networking roles**, for example:
  - Helpdesk / support with networking focus
  - Junior **Network Administrator / Engineer**
  - NOC or operations roles
- Makes your CV stand out vs. people with only generic IT experience.

---

### 1.9.3 Lab – Research IT and Networking Job Opportunities (guide)

Use this lab to connect CCNA topics to **real job ads** and **salary ranges**.

#### Step-by-step workflow

1. **Open a job site**
   - Example: `monster.com`  
   - For non-US: use Monster’s **site selection** page for your country.

2. **Search for networking jobs**
   - Start with a broad title like **“Network Administrator”**.
   - Then refine by adding **cert keywords**:
     - `Cisco CCNA`, `CCNP`, `CCNA Security`, `CCNA Voice`, etc.
   - Add or change **location filters**:
     - Your city, country, or “remote”.
   - Observe:
     - How many results you get.
     - How job titles change when you add certs.
     - Whether there are jobs in the locations you want.

3. **Check salary information**
   - Go to a salary site such as:
     - `salary.com` (US)  
     - `payscale.com` (international options)
   - Search with a broad term, e.g. **“Information Technology”** or a specific job name.
   - Pick one role that interests you and view:
     - **Typical salary range**
     - How salary changes with **experience**, **location**, or **certifications**.

4. **Explore more roles**
   - Browse related titles suggested by the site, for example:
     - *Network Engineer*, *Security Analyst*, *Cloud Engineer*, *DevNet / Automation roles*, etc.
   - Note:
     - Required **skills** (routing/switching, Linux, cloud, scripting…)
     - Required or preferred **certifications** (CCNA, Security+, Azure, AWS, etc.).
     - Whether roles mention **soft skills** (communication, teamwork, documentation).

---

### Reflection Questions (fill these in for your lab report)

Use these prompts and type your own answers in the PDF or your notes.

1. **What job titles did you search for?**  
   - *Hint:* list everything you actually tried (e.g. Network Administrator, Junior Network Engineer, Security Analyst, Helpdesk, etc.), not only the final one.

2. **What skills or certifications were required?**  
   - *Hint:* look for repeated patterns:
     - Same certs appearing across many ads (CCNA, Security+, etc.).
     - Same technical skills (TCP/IP, VLANs, routing, firewalls, Linux, cloud).
     - Any mention of **soft skills** (customer service, documentation, English level).

3. **Did you find any jobs you didn’t know existed? Which ones?**  
   - *Hint:* think about titles that surprised you or mixed skills (e.g. “Network Automation Engineer”, “Cloud Network Engineer”, “Collaboration Specialist”).

4. **Did you find any jobs you are interested in?**  
   - *Hint:* for each job that sounds attractive, note:
     - Job title and type of company.
     - **Key skills** required.
     - **Certifications** requested or preferred.
     - Any **experience level** info (entry-level, 1–2 years, etc.).

You can re-use this same process later whenever you want to update your **learning roadmap** or decide which certs to chase next.


## 1.10 – What did I learn in this module?

### Networks Affect Our Lives
- Networks let people share ideas, information, and media instantly across the world.  
- Online communities and cloud storage make it easy to collaborate and access files from anywhere.

---

### Network Components

- **Hosts / End devices**
  - Devices that send or receive data (PCs, phones, servers, printers, IP phones, etc.).
  - Can act as **clients**, **servers**, or both.
  - In **peer-to-peer** networks, devices share resources directly with each other.

- **Intermediary devices**
  - Connect individual end devices and link multiple networks.
  - Use addressing information and knowledge of the network to choose a path for traffic.
  - Examples: switches, routers, wireless access points, firewalls.

- **Network media**
  - The physical path that carries signals: copper, fiber, or wireless.
  - Provides the channel over which messages travel from source to destination.

---

### Network Representations and Topologies

- Diagrams use icons to represent devices and connections.
- A **topology diagram** is the “picture” of the network.
- **Physical topology** – where devices and cables are actually located.
- **Logical topology** – how devices are addressed and how data logically flows.

---

### Common Types of Networks

- **Small home network**
  - Connects a few devices to each other and to the internet.

- **SOHO (Small Office / Home Office) network**
  - Connects home or remote workers to a corporate network or shared resources.

- **Medium to large networks**
  - Used by schools, companies, and enterprises; can span multiple locations with many hosts.

- **The Internet**
  - A massive collection of interconnected networks worldwide.

- **LAN (Local Area Network)**
  - Spans a small geographic area such as a home, office building, or campus.

- **WAN (Wide Area Network)**
  - Spans a large geographic area, interconnecting multiple LANs.
  - Usually owned or managed by service providers.

- **Intranet**
  - Private LAN/WAN infrastructure that belongs to an organization and is only for authorized internal users.

- **Extranet**
  - Controlled access from outside organizations (suppliers, partners, customers) into selected internal resources.

---

### Internet Connections

- **SOHO / home options**
  - Cable
  - DSL
  - Cellular
  - Satellite
  - Dial-up telephone

- **Business options**
  - Dedicated leased lines
  - Metro Ethernet
  - Business DSL
  - Satellite

- **Converged networks**
  - Single network infrastructure that carries data, voice, and video using common standards and protocols.

- **Packet Tracer**
  - Cisco’s simulation tool for building and testing LAN and WAN topologies without real hardware.

---

### Reliable Networks

A good network architecture must support:

1. **Fault tolerance**
   - Uses redundancy (multiple paths/devices) to limit the impact of failures.

2. **Scalability**
   - Can grow to support more users and services without major redesign.

3. **Quality of Service (QoS)**
   - Prioritizes time-sensitive traffic (e.g., voice/video) when there is congestion.

4. **Security**
   - Protects both the network infrastructure and the data that flows through it.

---

### Network Trends

Modern networking trends that affect organizations and consumers:

- **BYOD (Bring Your Own Device)**
  - Users connect with personally owned laptops, tablets, and smartphones from almost anywhere.

- **Online collaboration**
  - Tools like Webex and similar platforms enable teams (employees, students, customers, partners) to work together in real time.

- **Video communications**
  - Video calls and conferencing for meetings, training, and entertainment across geographic boundaries.

- **Cloud computing**
  - Applications and data stored in remote data centers and accessed over the internet.
  - Main cloud types:
    - **Public cloud** – services offered to the general public.
    - **Private cloud** – dedicated to a single organization or government.
    - **Hybrid cloud** – mix of two or more cloud types (e.g., part public, part private).
    - **Community cloud** – shared by organizations with similar requirements (e.g., healthcare).

- **Smart home technology**
  - Networked devices and appliances (lights, ovens, cars, heating, etc.) that can be monitored and controlled via cloud services and mobile apps.

- **Powerline networking**
  - Uses existing electrical wiring to carry network data where Wi-Fi or new cabling is difficult.

- **Wireless broadband / WISP**
  - Wireless ISPs and broadband solutions that connect homes or small offices to the internet using radio links instead of cables.

---

### Network Security

**Common external threats**

- Viruses, worms, Trojan horses (malicious code on user devices)  
- Spyware and adware (secretly gather data)  
- Zero-day / zero-hour attacks (exploit newly discovered vulnerabilities)  
- Threat actor attacks (malicious individuals targeting devices/networks)  
- Denial-of-service (DoS) attacks (overload or crash services)  
- Data interception and theft (sniffing, man-in-the-middle, etc.)  
- Identity theft (stealing login credentials and personal data)

**Home / small office protections**

- **Antivirus and antispyware** – detect and remove malicious software.  
- **Firewall filtering** – block unwanted traffic into and out of the network.

**Enterprise-level protections**

- **Dedicated firewalls** – advanced filtering and inspection.  
- **Access control lists (ACLs)** – permit/deny traffic based on IPs, ports, protocols.  
- **Intrusion prevention systems (IPS)** – detect and stop suspicious or known attack patterns.  
- **Virtual private networks (VPNs)** – encrypted remote access for teleworkers.

**Security goals (CIA triad)**

- **Confidentiality** – only authorized parties can read the data.  
- **Integrity** – data is not altered from source to destination.  
- **Availability** – authorized users can access services and data when needed.

---

### The IT Professional

- **CCNA (Cisco Certified Network Associate)**
  - Validates core networking knowledge and keeps skills aligned with current technologies (IP, security, wireless, automation, programmability).
  - Structured as multiple courses plus a certification exam.

- **Career paths**
  - CCNA can help you pursue roles such as:
    - Network technician / support
    - Network administrator
    - Systems administrator
    - Network engineer / architect
  - Job opportunities can be found via:
    - The Cisco Networking Academy career tools and Talent Bridge Matching Engine.
    - General job boards (Indeed, Glassdoor, Monster, etc.) using terms like *IT*, *network administrator*, *network engineer*, or *Cisco CCNA*.

---

## How to Use This Repo

- Use the headings (1.0–1.4) to align with the official **Networking Today** module structure.  
- Treat this README as a **high-level map**:
  - Before studying – to know what’s coming  
  - After studying – to quickly review key concepts


---

## Disclaimer

- All trademarks and course names belong to Cisco Systems, Inc.  
- This repository contains **my own summaries and interpretations** and is not endorsed by Cisco.  
- No exam questions or proprietary content are reproduced; everything here is high-level study material only.
