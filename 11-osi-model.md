Layer 7 - Application
Layer 6 - Presentation
Layer 5 - Session
Layer 4 - Transport
Layer 3 - Network
Layer 2 - Data Link
Layer 1 - Physical

## What is the OSI Model?

The Open Systems Interconnection (OSI) Model is a framework used to understand how data moves across a network.

It divides network communication into seven layers, each with a specific function.

## Why the OSI Model Matters

The OSI Model helps networking and cybersecurity professionals understand how devices communicate and where problems may occur.

It provides a structured way to troubleshoot network issues and analyze traffic.

## The Seven Layers

Layer 7 - Application

Layer 6 - Presentation

Layer 5 - Session

Layer 4 - Transport

Layer 3 - Network

Layer 2 - Data Link

Layer 1 - Physical

## Layer 7 - Application

Provides network services directly to users and applications.

Examples:

- Web Browsers
- Email Clients
- DNS
- HTTP

  ## Layer 6 - Presentation

Responsible for data formatting, encryption, and compression.

Examples:

- SSL/TLS Encryption
- Data Formatting

  ## Layer 5 - Session

Establishes, maintains, and terminates communication sessions between devices.

## Layer 4 - Transport

Responsible for reliable data delivery.

Protocols:

- TCP
- UDP

  ## Layer 3 - Network

Responsible for routing and logical addressing.

Examples:

- IPv4
- Routers
- IP Addresses

  ## Layer 2 - Data Link

Responsible for MAC addressing and local network communication.

Examples:

- Switches
- MAC Addresses
- Ethernet

  ## Layer 1 - Physical
Responsible for transmitting raw bits across physical media. 

* **Examples:** Cables, Hubs, Connectors, Bits

---

## Real-World Example
When you visit a website, data travels down and up the OSI layers:

* **Application Layer:** Your web browser requests a webpage (HTTP/HTTPS).
* **Transport Layer:** TCP establishes a reliable connection.
* **Network Layer:** IP addresses determine where the traffic routes across networks.
* **Data Link Layer:** MAC addresses deliver the traffic locally from the router to your device.
* **Physical Layer:** The data is converted into electrical, light, or radio signals to travel through cables and hardware.

---

## Cybersecurity Connection
Security professionals use the OSI Model constantly to isolate problems:
* **Troubleshooting:** Figuring out if a connectivity issue is a bad cable (Layer 1) or a misconfigured IP (Layer 3).
* **Packet Analysis:** Inspecting headers in tools like Wiresharks to investigate incidents.
* **Defensive Controls:** Configuring Firewalls (Layer 3/4) or Web Application Firewalls (Layer 7) to block malicious traffic.

---

## Commands to Practice

```bash
# Check your local IP (Layer 3) and MAC Address (Layer 2)
ipconfig /all

# Test network layer connectivity to a remote host (Layer 3)
ping google.com

# Trace the Layer 3 hops packets take across routers to a destination
tracert 8.8.8.8

## Cybersecurity Connection

Security professionals use the OSI Model when:

- Troubleshooting networks
- Analyzing packets
- Investigating incidents
- Configuring firewalls
- Monitoring network traffic

Understanding the OSI Model helps analysts determine where a problem exists within the communication process.

## Memory Trick

Please Do Not Throw Sausage Pizza Away

Physical
Data Link
Network
Transport
Session
Presentation
Application

## Key Terms

- OSI Model
- Application Layer
- Presentation Layer
- Session Layer
- Transport Layer
- Network Layer
- Data Link Layer
- Physical Layer
- TCP
- UDP
- IP Address
- MAC Address

### How many layers are in the OSI Model?

Answer:
Seven.

### Which layer uses IP addresses?

Answer:
Layer 3 (Network).

### Which layer uses MAC addresses?

Answer:
Layer 2 (Data Link).

### Which layer uses TCP and UDP?

Answer:
Layer 4 (Transport).

### Which layer includes switches?

Answer:
Layer 2 (Data Link).

### Which layer includes routers?

Answer:
Layer 3 (Network).

Hub → Layer 1
Switch → Layer 2
MAC Address → Layer 2
ARP → Layer 2/3
IPv4 → Layer 3
Router → Layer 3
TCP/UDP → Layer 4
