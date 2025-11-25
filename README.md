# Internet

## Table of Contents

1. [What Is the Internet?](#1-what-is-the-internet)
   - [1.1 History & Concepts of Internet](#11-history--concepts-of-the-internet)
     - [1.1.1 ARPANET and the birth of packet switching](#111-arpanet-and-the-birth-of-packet-switching)
     - [1.1.2 Evolution from TCP/IP to the modern Internet](#112-evolution-from-tcpip-to-the-modern-internet)
     - [1.1.3 ISPs, IXPs, and the global Internet structure](#113-isps-ixps-and-the-global-internet-structure)
     - [1.1.4 Internet governance: IETF, ICANN, W3C, etc.](#114-internet-governance-ietf-icann-w3c-etc)
     - [1.1.5 Domain names, DNS hierarchy, and IP address allocation (RIRs)](#115-domain-names-dns-hierarchy-and-ip-address-allocation-rirs)
   - [1.2 Computer Networking Basics]()
     - [1.2.1 Data transmission: bits, bytes, latency, bandwidth]()
     - [1.2.2 OSI Model (7 layers) & TCP/IP model]()
     - [1.2.3 Network devices: routers, switches, firewalls, hubs, modems]()
     - [1.2.4 Addressing and routing (MAC, IP, subnetting)]()
     - [1.2.5 Network topologies (LAN, WAN, MAN, PAN)]()

2. [How Does Internet Actually Work?]()
   - [2.1 Layer 2 & 3 (Data Link + Network)]()
     - [2.1.1 Ethernet, ARP, VLANs]()
     - [2.1.2 IPv4 & IPv6 addressing and subnetting]()
     - [2.1.3 Routing protocols: RIP, OSPF, BGP]()
     - [2.1.4 NAT, DHCP, ICMP, ARP]()
   - [2.2 Layer 4 (Transport)]()
     - [2.2.1 TCP vs UDP]()
     - [2.2.2 Ports and sockets]()
     - [2.2.3 Congestion control, flow control, three-way handshake]()
     - [2.2.4 Connection termination, retransmission, sliding window]()
   - [2.3 Layer 5–7 (Application)]()
     - [2.3.1 HTTP/HTTPS]()
     - [2.3.2 DNS, SMTP, FTP, SSH, Telnet]()
     - [2.3.3 REST APIs and WebSockets]()
     - [2.3.4 Caching (CDNs, proxies, reverse proxies)]()

3. [System And Infrastructure]()
   - [3.1 Servers & Data Centers]()
     - [3.1.1 Physical vs virtual servers]()
     - [3.1.2 Web servers (Apache, Nginx)]()
     - [3.1.3 Load balancing and reverse proxying]()
     - [3.1.4 Content Delivery Networks (Akamai, Cloudflare)]()
     - [3.1.5 Data center design: power, cooling, redundancy]()
   - [3.2 Cloud & Virtualization]()
     - [3.2.1 Virtual Machines vs Containers]()
     - [3.2.2 Hypervisors (KVM, VMware, Hyper-V)]()
     - [3.2.3 Cloud computing models (IaaS, PaaS, SaaS)]()
     - [3.2.4 Major clouds (AWS, Azure, GCP)]()
     - [3.2.5 Edge computing and CDN edge nodes]()
   - [3.3 Internet Routing & Backbone]()
     - [3.3.1 Autonomous Systems (AS)]()
     - [3.3.2 BGP routing and peering agreements]()
     - [3.3.3 Internet Exchange Points (IXPs)]()
     - [3.3.4 Anycast and GeoDNS]()
     - [3.3.5 Undersea cables and satellite Internet]()

4. [Security And Trust]()
   - [4.1 Internet Security Fundamentals]()
     - [4.1.1 Encryption, hashing, and authentication]()
     - [4.1.2 SSL/TLS and HTTPS]()
     - [4.1.3 Public Key Infrastructure (PKI), certificates, CA hierarchy]()
     - [4.1.4 Firewalls, VPNs, IDS/IPS]()
     - [4.1.5 DNSSEC, DANE, HSTS, CSP]()
   - [4.2 Cybersecurity & Attacks]()
     - [4.2.1 DDoS, phishing, MITM, spoofing]()
     - [4.2.2 Zero Trust Networks]()
     - [4.2.3 OWASP Top 10 (Web Security)]()
     - [4.2.4 Security in routing (RPKI, MANRS)]()
     - [4.2.5 Threat detection and incident response]()

5. [Software & Web Technology]()
   - [5.1 Web Architecture]()
     - [5.1.1 How browsers work (rendering engine, JS engine)]()
     - [5.1.2 HTTP lifecycle (request–response, caching, cookies)]()
     - [5.1.3 APIs, GraphQL, gRPC]()
     - [5.1.4 Progressive Web Apps, SPAs]()
     - [5.1.5 RESTful design and microservices]()
   - [5.2 Backend & Database]()
     - [5.2.1 Web servers and frameworks (Node.js, Django, etc.)]()
     - [5.2.2 Database fundamentals (SQL vs NoSQL)]()
     - [5.2.3 Caching (Redis, Memcached)]()
     - [5.2.4 Scalability (sharding, replication, CQRS)]()

6. [Modern Internet Technology]()
   - [6.1 Wireless & Mobile Internet]()
     - [6.1.1 Wi-Fi (IEEE 802.11 standards)]()
     - [6.1.2 Cellular (2G → 5G → 6G)]()
     - [6.1.3 Mobile network architecture]()  
     - [6.1.4 Satellite and IoT connectivity]()
   - [6.2 Internet of Things (IoT)]()
     - [6.2.1 IoT protocols (MQTT, CoAP, LoRaWAN)]()
     - [6.2.2 Edge devices and gateways]()
     - [6.2.3 Security & identity in IoT]()
   - [6.3 Emerging Internet Technologies]()
     - [6.3.1 IPv6 adoption and future of routing]()
     - [6.3.2 QUIC, HTTP/3]()
     - [6.3.3 WebAssembly (WASM)]()
     - [6.3.4 Decentralized Web (Web3, IPFS, blockchain)]()
     - [6.3.5 AI-driven networking and observability]()

7. [Miscellaneous]()
   - [7.1 Internet Measurement & Performance]()
     - [7.1.1 Traceroute, Ping, BGP looking glass]()
     - [7.1.2 Network observability & metrics]()
     - [7.1.3 Internet health reports (RIPE Atlas, CAIDA)]()
   - [7.2 Internet Governance & Policy]()
     - [7.2.1 Net neutrality]()
     - [7.2.2 Censorship and filtering]()
     - [7.2.3 Internet freedom and surveillance]()
     - [7.2.4 Legal frameworks (GDPR, data localization)]()
   - [7.3 Building & Operating at Scale]()
     - [7.3.1 Designing fault-tolerant distributed systems]()
     - [7.3.2 Scaling microservices globally]()
     - [7.3.3 DevOps, CI/CD, observability]()
     - [7.3.4 Resilience engineering & chaos testing]()


# 1. What is the Internet?

**The Internet is a global network that connects millions of computers and devices, allowing them to communicate and share information using standard communication rules called protocols.**

**It lets people access websites, send messages, share data, and use online services from anywhere in the world.**

*The Internet is not the same as the Web.*  
The **World Wide Web** is a service that runs on the Internet. The Web is made of websites and pages; the Internet is the underlying network.

## **1.1 History & Concepts of the Internet**

The Internet has evolved from a small research experiment into a global network that powers modern life. Below is a timeline-style breakdown of how it all began and how it continues to grow.

### **Early Ideas (1960s)**

- The concept of a global computer network first emerged in the **1960s**.
- The U.S. Department of Defense developed **ARPANET** (Advanced Research Projects Agency Network) in **1969**.
- Its main purpose was to allow computers in different locations to communicate, even if parts of the network failed.

### **ARPANET Grows (1970s)**

- Researchers designed the essential communication rules known as **TCP/IP** (Transmission Control Protocol / Internet Protocol).
- In **1983**, ARPANET officially adopted TCP/IP, forming the foundation of today’s Internet.
- More universities, laboratories, and government institutions joined the network, expanding connectivity.

### **Birth of the World Wide Web (1990s)**

- In **1990**, Tim Berners-Lee created the **World Wide Web (WWW)**, transforming how people accessed information.
- He introduced:
  - **HTML** – the language used to build webpages  
  - **URLs** – the addressing system for locating resources  
  - **HTTP** – the protocol used to access web pages  
- By **1993**, the release of the browser **Mosaic** made the web easily accessible to the public.
- The Internet grew rapidly as homes and businesses began going online.

### **Broadband & Social Media Era (2000s)**

- High-speed Internet (broadband and Wi-Fi) became widely available.
- Websites evolved into powerful platforms and services.
- This era saw the rise of:
  - **Google**
  - **Facebook**
  - **YouTube**
  - **Twitter**
- Online shopping, streaming platforms, and cloud services became mainstream.

### **Mobile & Smart Devices (2010s–Present)**

- Smartphones made the Internet portable and accessible anywhere.
- Smart devices (IoT) connected everyday objects such as watches, cars, and home appliances to the Internet.
- Internet speeds improved dramatically with **fiber**, **4G**, and **5G** technology.

## 1.1.1 ARPANET and the birth of packet switching  

### Why ARPANET Was Created?

During the **Cold War**, the U.S. needed a communication system that could survive potential failures or attacks. Traditional networks relied on a single continuous circuit, if one part failed, the whole system could collapse.  
ARPANET was designed to be **decentralized**, allowing data to reroute around damaged or busy areas.

### Key Figures Behind ARPANET

- **Leonard Kleinrock** — pioneered the theory of packet switching and helped shape early ARPANET design.
- **Vint Cerf & Bob Kahn** — later developed **TCP/IP**, the universal communication protocol that still powers the Internet today.

### Packet Switching vs. Circuit Switching

| **Circuit Switching (Old Telephone Systems)**  | **Packet Switching (ARPANET Innovation)**  |
|------------------------------------------------|--------------------------------------------|
| Uses a dedicated line between two points.      | Breaks data into small chunks called **packets**. |
| If the line breaks, communication stops.       | Packets can take different routes to reach the destination. |
| No reassembly needed data flows in order       | Receiving device **reassembles packets** in the correct order, checks for errors, and requests missing packets if needed. |
| Inefficient for digital data.                  | More reliable, flexible, and efficient. |


*This idea made large scale computer networking possible.*

### The First Four ARPANET Nodes (1969)

1. **UCLA** – First node and first message sent  
2. **SRI** – Received the first ARPANET message  
3. **UCSB** – Third node added  
4. **University of Utah** – Fourth node to join the network  

These four formed the backbone of the very first Internet-like system.

### ARPANET → NSFNET → Internet

- **ARPANET (1969–1980s):** Began as a military research network.
- **NSFNET (1980s):** Expanded ARPANET into a larger academic and scientific network funded by the National Science Foundation.
- **The Internet (1990s–present):** Adoption of **TCP/IP (1983)** unified all networks, creating the global Internet we use today.

## 1.1.2 Evolution from TCP/IP to the modern Internet

The modern Internet as we know it would not exist without the development and adoption of **TCP/IP**, the protocol suite that standardized how networks communicate. Understanding this evolution gives us insight into how disparate networks became a single global network.

#### Early Network Protocols: NCP, UUCP, and Predecessors
Before TCP/IP, networks used a variety of protocols that were often **incompatible**.  
- **NCP (Network Control Protocol):** The protocol used on ARPANET in the early 1970s for host-to-host communication. It allowed basic message passing but lacked a universal addressing scheme.  
- **UUCP (Unix-to-Unix Copy Program):** Enabled file transfers and email between UNIX systems over serial lines and modems. UUCP worked for specific networks but could not scale globally.  

These protocols were functional but limited; connecting multiple networks required a universal standard.

#### TCP/IP Architecture: RFC 791 & RFC 793
The breakthrough came with **TCP/IP**, designed by **Vint Cerf and Bob Kahn** in the 1970s.  
- **RFC 791 (IP - Internet Protocol):** Defined how data is addressed and routed across networks. It introduced the concept of **packets**, each carrying source and destination addresses.  
- **RFC 793 (TCP - Transmission Control Protocol):** Added reliability by ensuring that packets arrive **in order** and without errors. TCP also handles retransmissions, flow control, and connection management.

TCP/IP’s **layered architecture** allowed networks of different types to interoperate, forming the backbone of the global Internet.

#### Flag Day: Transition on January 1, 1983
On **January 1, 1983**, ARPANET officially switched from NCP to TCP/IP a milestone called the **“flag day.”**  
- All hosts on the network had to adopt TCP/IP simultaneously.  
- This transition unified multiple experimental networks into a **single standardized protocol suite**, laying the foundation for the Internet.

#### TCP/IP Becomes Universal
After 1983, TCP/IP spread rapidly:  
- Academic networks, government research networks, and commercial networks adopted it.  
- Its flexibility allowed it to support new applications like email, file transfer, and eventually the **World Wide Web**.  
- TCP/IP’s **end-to-end model** simplified network design, allowing networks of any type (wired, wireless, satellite) to interconnect.

#### Evolution of Protocols: HTTP, IPv6, and Beyond
TCP/IP is still at the core of the Internet, but the protocols built on top of it have evolved:  
- **HTTP (Hypertext Transfer Protocol):** Introduced in 1990, enabled the Web. Later versions, **HTTP/2** and **HTTP/3**, improved speed and reliability.  
- **IPv6:** Developed to address the exhaustion of IPv4 addresses, providing virtually unlimited unique addresses.  
- **Other protocols:** DNS, SMTP, FTP, and emerging protocols like **QUIC** and **WebRTC** continue to expand Internet capabilities.  


## 1.1.3 ISPs, IXPs, and the global Internet structure

The Internet is not just a cloud in the sky it is a **complex, hierarchical network of networks**. Understanding how ISPs, IXPs, and global infrastructure connect billions of devices is key to appreciating how the Internet actually works.

#### Internet Service Providers (ISPs): Connecting Users
**ISPs** are companies or organizations that provide Internet access to homes, businesses, and other networks.  
- **Consumer ISPs**: Provide broadband or mobile Internet to households. Examples: Comcast, AT&T, Vodafone.  
- **Business/Enterprise ISPs**: Provide dedicated high-speed connectivity for organizations and data centers.  

ISPs assign IP addresses, manage routing, and ensure users can reach websites and services anywhere in the world. They are the **first step in Internet access**.

#### Internet Exchange Points (IXPs): The Hubs of Traffic
**IXPs** are physical infrastructure where multiple networks **interconnect and exchange traffic** without going through third-party networks.  
- This reduces latency, improves speed, and lowers transit costs.  
- Large IXPs exist in major cities worldwide, such as **DE-CIX (Frankfurt), LINX (London), and AMS-IX (Amsterdam)**.  
- IXPs allow local traffic to stay local, reducing the load on long-distance connections.

#### Tiered ISP Structure: Tier-1, Tier-2, Tier-3
The Internet is structured hierarchically:  
- **Tier-1 ISPs**: Global networks that can reach every part of the Internet **without paying for transit**. They peer with each other to exchange traffic freely. Examples: AT&T, NTT, CenturyLink.  
- **Tier-2 ISPs**: Regional providers that buy transit from Tier-1 ISPs but may peer with other Tier-2 ISPs. They connect local networks and provide access to Tier-1 for long-distance traffic.  
- **Tier-3 ISPs**: Local ISPs that provide Internet directly to homes and small businesses, typically purchasing transit from Tier-2 providers.

This hierarchy ensures efficient routing and connectivity across regions and continents.

#### Peering and Transit Agreements
- **Peering**: Two ISPs agree to exchange traffic **directly** at no cost, usually at an IXP.  
- **Transit**: An ISP pays a higher tier provider to carry traffic to parts of the Internet it cannot reach via peering.  

These agreements form the economic and technical backbone of global Internet traffic.

#### How Traffic Flows Between Continents
- Internet traffic often travels through **undersea fiber-optic cables** connecting continents.  
- Large data centers and IXPs act as **interconnection hubs**, ensuring traffic is routed efficiently.  
- Content Delivery Networks (CDNs) like **Cloudflare and Akamai** cache content near users to reduce latency and congestion.  

This combination of hierarchical ISPs, IXPs, and submarine networks makes the Internet resilient, scalable, and global.


## 1.1.4 Internet governance: IETF, ICANN, W3C, etc.

The Internet might feel like a “free-for-all,” but behind the scenes, a variety of organizations **coordinate standards, policies, and technical infrastructure** to ensure it works reliably and fairly. This coordination is known as **Internet governance**.

#### Key Organizations and Their Roles

- **IETF (Internet Engineering Task Force)**  
  - Develops the **technical standards** that make the Internet interoperable.  
  - Publishes **RFCs (Request for Comments)**, which define protocols like **TCP/IP, HTTP, SMTP**, and many others.  
  - Operates openly and collaboratively, allowing anyone to contribute ideas or feedback.  

- **ICANN (Internet Corporation for Assigned Names and Numbers)**  
  - Oversees the **Domain Name System (DNS)** and IP address allocation.  
  - Ensures that **domain names are unique** and coordinates the distribution of IP blocks through Regional Internet Registries (RIRs).  
  - Maintains global DNS root servers, which are critical for resolving domain names to IP addresses.  

- **W3C (World Wide Web Consortium)**  
  - Develops **web standards** such as **HTML, CSS, and accessibility guidelines**.  
  - Ensures that web technologies are interoperable across browsers and platforms.  
  - Promotes **open, accessible, and international** web development.  

- **ISOC (Internet Society)**  
  - Advocates for **open development and governance** of the Internet.  
  - Supports initiatives that promote connectivity, security, and sustainability worldwide.  

- **IANA (Internet Assigned Numbers Authority)**  
  - Manages **global IP address pools, DNS root zones, and protocol parameters**.  
  - Operates under ICANN’s oversight.  

- **RIRs (Regional Internet Registries)**  
  - Distribute IP addresses regionally (e.g., **ARIN** in North America, **RIPE NCC** in Europe, **APNIC** in Asia-Pacific).  
  - Ensure fair allocation and manage local Internet number resources.  

#### How Decisions Are Made

Unlike a traditional organization, **the Internet is not centrally controlled**. Governance relies on:  
- **Open, consensus-based decision-making**: Anyone can participate in IETF working groups or W3C committees.  
- **Multistakeholder model**: Governments, private sector, academia, and civil society all contribute.  
- **Transparency**: Meetings, proposals, and drafts are publicly documented.  

This collaborative approach balances technical efficiency, global coordination, and the openness that has made the Internet a universal platform.


## 1.1.5 Domain names, DNS hierarchy, and IP address allocation (RIRs)

The Internet’s ability to connect billions of devices relies on a **structured addressing system** and a way to map human-readable names to numeric addresses. This is where **domain names, the DNS hierarchy, and IP address allocation** come into play.

#### Hierarchical DNS Structure

The **Domain Name System (DNS)** is like the Internet’s phonebook. It translates human-readable domain names (like `example.com`) into IP addresses (like `93.184.216.34`). DNS is hierarchical, meaning it’s structured in levels.

![DNS Hierarchy](https://github.com/milan-mohapatra-yt/internet/blob/main/assets/dns-hierarchy.png)

### **a) Root Level**

* **What it is:** The top of the DNS hierarchy.
* **Function:** Points to **Top-Level Domain (TLD) servers**.
* **Example:** The `.` in `www.example.com`.

### **b) Top-Level Domains (TLDs)**

* **What it is:** The next level down in the hierarchy. Examples include:

  * **gTLDs (generic TLDs):** `.com`, `.org`, `.net`
  * **ccTLDs (country code TLDs):** `.us`, `.uk`, `.jp`
* **Function:** Direct queries to the authoritative servers for second-level domains.

### **c) Second-Level Domains**

* **What it is:** Directly under TLDs, usually the main name you register.

  * Example: In `example.com`, `example` is the second-level domain.
* **Function:** Managed by individuals or organizations who register the domain via registrars.

### **d) Subdomains**

* **What it is:** Domains under the second-level domain.

  * Example: `blog.example.com` or `mail.example.com`
* **Function:** Can point to different servers/services (web, email, etc.).

### **e) Hostnames**

* **What it is:** The actual machine or service on the subdomain.

  * Example: `www` in `www.example.com`
* **Function:** Maps to a specific IP address.

#### Who Manages Each Layer

| Level               | Example           | Function                        | Controlled By                                |
| ------------------- | ----------------- | ------------------------------- | -------------------------------------------- |
| Root                | `.`               | Directs to TLD servers          | ICANN / IANA                                 |
| Top-Level Domain    | `.com`, `.uk`     | Directs to second-level domains | ICANN (gTLDs), national authorities (ccTLDs) |
| Second-Level Domain | `example.com`     | Managed by registrant           | Domain owner via registrar                   |
| Subdomain           | `blog.example.com` | Points to service/server        | Domain owner                                 |
| Hostname            | `www`             | Maps to IP address              | Domain owner / network administrator         |

#### Regional Internet Registries (RIRs)

IP addresses are allocated through **Regional Internet Registries (RIRs)**, which manage resources within specific regions:

- **ARIN** — North America  
- **RIPE NCC** — Europe, Middle East, Central Asia  
- **APNIC** — Asia-Pacific  
- **AFRINIC** — Africa  
- **LACNIC** — Latin America and the Caribbean  

RIRs ensure **fair and efficient distribution of IP addresses** and maintain public records of allocations.

#### IPv4 Exhaustion and IPv6 Allocation

- **IPv4 addresses** are 32-bit, allowing ~4.3 billion unique addresses, which have largely been exhausted due to global growth.  
- **IPv6** uses 128-bit addresses, providing a virtually unlimited number of IP addresses.  
- RIRs are now responsible for **allocating IPv6 addresses** and managing transition strategies for IPv4 depletion, ensuring the Internet can scale for billions more devices.  

## 1.2 **Computer Networking Basics**

### Difference between Network and Internet

| **Network**                        | **Internet**                                        |
| ---------------------------------- | --------------------------------------------------- |
| A small group of connected devices | A worldwide network connecting millions of networks |
| Can exist without the Internet     | Cannot exist without networks                       |
| Example: home LAN                  | Example: the global Internet                        |

### **1.2.1 Data Transmission (bits, bytes, latency, bandwidth)**

Data transmission is the process of sending digital data (bits) from one device to another through a communication medium such as copper cables, fiber optics, or wireless radio waves.

> ### **What Happens During Data Transmission?**
>
> When you send a message, open a website, or stream a video, your device:
>
> 1. Converts data into bits (0s and 1s)
> 2. Encodes those bits into a physical signal
>
>    * electrical pulses in copper cables
>    * light pulses in fiber
>    * radio waves in Wi-Fi / cellular
> 3. Transmits the signal across the medium
> 4. The receiving device decodes the signal back into bits

### Bits, Bytes & Data Units

In the context of **data transmission**, **“Bits, Bytes, & Data Units”** refer to the fundamental building blocks used to measure, send, and interpret digital information. Here’s a clear breakdown:


### Bit (b) — The Smallest Unit

* A **bit** is the smallest unit of digital data.
* It can have only **two values:** 0 or 1.
* In data transmission, **speed is often measured in bits per second (bps)** because data is sent one bit at a time over a channel.

**Examples:**

* 1 kbps = 1,000 bits per second
* 1 Gbps = 1,000,000,000 bits per second

### Byte (B) — 8 Bits

* A **byte** consists of **8 bits**.
* It's the standard unit for measuring stored data (files, memory, etc.).

**Examples:**

* 1 KB = 1,024 bytes (for storage; sometimes 1,000 bytes in networking contexts)
* A character like “A” typically occupies **1 byte**.

> Why Use Bits for Transmission but Bytes for Storage?
>
> * **Transmission** deals with the electrical/optical signals, which transfer **bits** one by one.
> * **Storage** deals with data in usable chunks, so **bytes** make more sense.

### Larger Data Units (Common in Transmission & Storage)

### Bit-based (for transmission speeds):

* **kb** – kilobit (1,000 bits)
* **Mb** – megabit (1,000,000 bits)
* **Gb** – gigabit
* **Tb** – terabit

Used for: Internet speeds, network bandwidth, Ethernet, Wi-Fi.

### Byte-based (for stored data):

* **kB** – kilobyte (1,000 or 1,024 bytes)
* **MB** – megabyte
* **GB** – gigabyte
* **TB** – terabyte

Used for: File sizes, disk capacity, memory.

### Important Distinction

* **1 Byte (B) = 8 bits (b)**
  So:

  * **100 Mbps ≠ 100 MB/s**
  * 100 Mbps ≈ 12.5 MB/s (divide by 8)

This is why your download speeds often look lower than your ISP's advertised speeds—because they use **megabits**, but browsers show **megabytes per second**.

### Data Units in Data Transmission

In networking, additional units describe how data moves:

* **Bandwidth:** maximum bits per second a channel can carry.
* **Throughput:** actual successful data rate.
* **Latency:** time delay (ms).
* **Packet:** a structured chunk of data (hundreds or thousands of bytes).

These units relate to bits and bytes but describe *data flow behavior* rather than size alone.

### How Data Is Physically Carried Across Media

Digital data (0s and 1s) doesn’t travel as text—it travels as **physical signals**:

### a. Electrical Signals (Ethernet Copper Cables)

* Voltage changes represent bits.
* Uses encoding schemes such as NRZ, PAM-3, PAM-4, etc.
* Susceptible to electromagnetic interference and distance limitations.

### b. Light Pulses (Fiber Optic Cables)

* Light ON = 1, Light OFF = 0 (in its simplest conceptual form).
* Extremely low signal loss → supports long distances.
* Immune to electrical interference.
* Can use multiplexing (DWDM) to send multiple wavelengths simultaneously.

### c. Radio Waves (Wi-Fi, Cellular, Bluetooth, Satellite)

* Data encoded using modulation (QPSK, QAM, OFDM, etc.).
* Travels through the air → subject to noise, fading, multipath reflections.
* Requires error correction and retransmission protocols.

Across all mediums, the core idea remains:
**We encode digital bits into a physical signal, transmit it, then decode it back into bits.**

### Propagation Delay & Physical Limits

Even at the speed of light, information takes time to move across distance.

### Propagation Delay

The time it takes for a signal to physically travel across the medium.

* Fiber: ~200,000 km/s
* Copper: ~66% the speed of light
* Radio (space): ~300,000 km/s

Example:
A signal from New York to London (approx. 5,600 km):
Propagation delay ≈ 28 ms *one-way*, 56 ms *round-trip*.
This is the baseline latency—*you can’t beat physics*.

### Jitter and Why It Matters

Jitter is **Variation in latency over time.**

* If one packet arrives in 20 ms and the next arrives in 60 ms, jitter = high.
* Critical for:

  * Real-time voice (VoIP)
  * Video streaming
  * Online gaming
* Networks use **jitter buffers** to smooth out variation.

High jitter makes real-time communication feel choppy or delayed even if bandwidth is high.

### Packet Loss

Packet Loss **When packets never reach their destination.**

usually caused by:

* Congestion (router buffers overflow)
* Wireless interference
* Faulty cables or hardware
* Long-distance radio links
* Misconfiguration or overloaded devices

Effects of packet loss:

* TCP retransmits lost packets → reduces throughput
* Video calls freeze
* Games experience lag or “rubberbanding”
* Web pages load slowly

Even **1% packet loss** can dramatically harm real throughput on a fast link.

---

### 1.2.2 **OSI Model & TCP/IP Model**

When data travels across a network—whether you're loading a webpage, sending a message, or streaming video—your device follows a structured communication framework. Two foundational models define how this happens: the **OSI Model** and the **TCP/IP Model**.

### Why Communication Models Matter
Networks are complex. Different devices, vendors, and applications need common rules to communicate effectively.  
Communication models provide:

- A **layered structure**  
- **Standard terminology**  
- Clear **responsibilities per layer**  
- Vendor/device **interoperability**  

The OSI model is conceptual, while the TCP/IP model is practical and used on the Internet. The OSI model was developed before many modern protocols were invented, and after TCP/IP became widely adopted, the OSI model gradually faded from practical use.

### **The OSI Model (7 Layers)**

The OSI model (Open Systems Interconnection model) is a 7-layer conceptual framework used to understand, design, and troubleshoot how data moves across a network.
It does not define real protocols rather, it explains how networking should work in an organized way.

![OSI 7 Layar diagram](https://github.com/milan-mohapatra-yt/internet/assets/osi-7layera-diagram.png)


### **Layer 7: Application**
- The Application Layer provides network services directly to user applications such as browsers, email clients, file transfer tools, and messaging apps.
- It does not refer to the application itself, but to the services and protocols that enable applications to communicate over a network. 
- Protocols: **HTTP, HTTPS, SMTP, POP3, IMAP, FTP / SFTP, DNS, SSH, Telnet**

### **Layer 6: Presentation**
- It translates, formats, encrypts / decryption, and compresses / decompression data so that different systems can understand each other.
- Data serialization (JSON, XML)

### **Layer 5: Session**
- The Session Layer is responsible for managing, controlling, and maintaining communication sessions between two devices or applications.
- A session is simply a connection that stays open while two devices exchange data.
- Handles setup, maintenance, and termination  
- Uses sockets and dialogues

### **Layer 4: Transport**
- The Transport layer is responsible for end-to-end communication between devices.
- It manages how much data is sent, how fast it's sent, and ensures that data arrives without errors. 
- Protocols: **TCP**, **UDP**

### **Layer 3: Network**
Networking layer responsible for:
- **Logical addressing using IP**: It assigns and uses IP addresses to identify devices on different networks. 
- **Routing between networks**: It determines the best path for data to travel from the source to the destination across multiple networks.
- **Packet forwarding**: It determines the best path for data to travel from the source to the destination across multiple networks.
- Purpose of networking layer is to move data between networks, not just within a single local network.
- Protocols: **IPv4, IPv6, ICMP**

### **Layer 2: Data Link**
Divided into:
- **LLC (Logical Link Control)**: Handles error checking, flow control, and communication with Layer 3 (Network Layer).
- **MAC (Media Access Control)**: Handles MAC addressing and control of how devices share access to the network.

Handles:
- MAC addressing: Uses MAC addresses to identify devices on the same network.
  - Permanent physical address (burned into the network card)
  - Example MAC: 44:A1:23:BC:9F:10
- Frame creation: It breaks data into frames (Layer 2 data units).
  - Frames include:
    - source MAC address
    - destination MAC address

- Error-checking information: Layer 2 frames include fields like the Frame Check Sequence (FCS), which stores a checksum used to detect corruption. This helps ensure that only valid, uncorrupted frames are processed.
- Switch operations: Switches operate at Layer 2, learning MAC addresses, building a MAC table, and forwarding frames to the correct port. If the destination is unknown, they flood the frame; if known, they forward it; if unnecessary, they filter it.
- Error detection (CRC): Layer 2 uses CRC (Cyclic Redundancy Check) to detect transmission errors. The sender calculates a CRC value and places it in the frame; the receiver recalculates it and compares. If it doesn't match, the frame is discarded.

### **Layer 1: Physical**

The Physical Layer is the first layer of the OSI model. It is responsible for the actual transmission of raw bits (0s and 1s) over a physical medium. It deals with hardware components, such as cables, connectors, switches, and electrical/optical/radio signals. This layer defines voltage levels, data rates, pin layouts, and physical specifications needed to send data between devices.


# ## **3. The TCP/IP Model (4 Layers)**
TCP/IP is the **actual** model used on today's networks and the Internet.

---

## ### **Layer 4 — Application**
Combines OSI Layers 5, 6, 7  
Examples: **HTTP, DNS, DHCP, SMTP**

---

## ### **Layer 3 — Transport**
Same function as OSI Layer 4  
Protocols: **TCP (reliable)**, **UDP (fast, lightweight)**

---

## ### **Layer 2 — Internet**
Maps to OSI Layer 3  
Handles IP addressing and routing  
Protocols: **IP, ICMP, ARP**

---

## ### **Layer 1 — Network Access**
Combines OSI Layers 1 & 2  
Covers:
- MAC addresses  
- Frames  
- Physical transmission  

---

# ## **4. OSI vs TCP/IP Mapping**
| **OSI Model (7)** | **TCP/IP Model (4)** |
|-------------------|-----------------------|
| Application (7)   | Application           |
| Presentation (6)  | Application           |
| Session (5)       | Application           |
| Transport (4)     | Transport             |
| Network (3)       | Internet              |
| Data Link (2)     | Network Access        |
| Physical (1)      | Network Access        |

---

# ## **5. Data Encapsulation: How Data Moves Through Layers**
When a device sends data, each layer **adds its own header**, creating a wrapped bundle. This process is called **encapsulation**.

### **Sender Side (Encapsulation Flow)**  
**Application Layer:** Creates data  
↓  
**Transport Layer:** Wraps data → *Segment* (TCP) / *Datagram* (UDP)  
↓  
**Internet Layer:** Adds IP header → *Packet*  
↓  
**Network Access Layer:** Adds MAC header & trailer → *Frame*  
↓  
**Physical Layer:** Converts to bits → *Bits on wire*

---

### **Receiver Side (De-encapsulation Flow)**  
Bits → Frame → Packet → Segment → Data  
Each layer removes its header and passes the data upward.

---

# ## **6. Why This Matters in Real Networking**
Understanding these models helps you troubleshoot and design networks:

- **Ping issues?** Layer 3 (IP/ICMP)  
- **Website not loading?** Layer 7 (HTTP/DNS)  
- **Slow transfer?** Layer 4 (TCP windows)  
- **Wi-Fi issues?** Layers 1–2  
- **Routing problems?** Layer 3  

The models give a precise language to pinpoint failure points.

---

# ## **Conclusion**
The OSI and TCP/IP models are foundational frameworks for understanding computer networking.  
Together, they explain:

- **How applications communicate**
- **How data flows across networks**
- **How devices on different networks interoperate**
- **Where networking problems occur**

Mastering these models is essential for anyone studying networking, cybersecurity, cloud, or IT engineering.

---

If you want, I can also write:  
📌 A cheat sheet version  
📌 A visual diagram-based version  
📌 A practice Q&A set  
📌 A downloadable PDF version  
Just tell me!
