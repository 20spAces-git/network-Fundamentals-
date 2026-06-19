# TCP vs UDP

## What are TCP and UDP?

TCP (Transmission Control Protocol) and UDP (User Datagram Protocol) are communication protocols that operate at Layer 4 of the OSI Model, also known as the Transport Layer.

They determine how data is sent between devices across a network.

---

## Why TCP and UDP Matter

TCP and UDP are responsible for transporting data between systems.

Many applications and services rely on one of these protocols to communicate efficiently.

Understanding the difference is important for networking, cybersecurity, and troubleshooting.

---

## What is TCP?

TCP is a connection-oriented protocol that provides reliable communication.

Before data is sent, TCP establishes a connection between devices.

### TCP Features

* Reliable
* Connection-oriented
* Error checking
* Data arrives in order
* Retransmits lost packets

---

## What is UDP?

UDP is a connectionless protocol that focuses on speed.

Data is sent without establishing a connection first.

### UDP Features

* Fast
* Connectionless
* Minimal overhead
* No guarantee of delivery
* No retransmission of lost packets

---

## TCP vs UDP Comparison

| Feature         | TCP        | UDP            |
| --------------- | ---------- | -------------- |
| Connection      | Yes        | No             |
| Reliable        | Yes        | No             |
| Speed           | Slower     | Faster         |
| Error Checking  | Extensive  | Minimal        |
| Packet Ordering | Guaranteed | Not Guaranteed |

---

## Common TCP Applications

* HTTP
* HTTPS
* FTP
* SSH
* Email

These applications require reliable communication.

---

## Common UDP Applications

* Online Gaming
* Video Streaming
* Voice Calls (VoIP)
* DNS
* Live Broadcasts

These applications prioritize speed.

---

## Real-World Example

Imagine sending an important document.

TCP is like certified mail.

You receive confirmation that the package arrived.

UDP is like dropping a flyer from an airplane.

It is fast, but there is no guarantee everyone receives it.

---

## Cybersecurity Connection

Security analysts frequently investigate TCP and UDP traffic.

Understanding these protocols helps with:

* Packet analysis
* Wireshark investigations
* Firewall configuration
* Threat detection
* Network troubleshooting

Many attacks target specific TCP or UDP services.

---

## Key Terms

* TCP
* UDP
* Transport Layer
* Connection-Oriented
* Connectionless
* Packet
* Reliability
* Latency
* Throughput

---

## Commands to Practice

```bash
# View active TCP connections and listening ports on your device
netstat -an

# Test connectivity to a specific port (if your system has telnet or nc)
telnet google.com 80

---

## Key Takeaways

* TCP provides reliable communication.
* UDP prioritizes speed.
* TCP establishes a connection before transmitting data.
* UDP sends data without creating a connection.
* TCP and UDP operate at Layer 4 of the OSI Model.

---

## Practice Questions & Answers

### What does TCP stand for?

Answer:
Transmission Control Protocol.

### What does UDP stand for?

Answer:
User Datagram Protocol.

### Which protocol is connection-oriented?

Answer:
TCP.

### Which protocol is faster?

Answer:
UDP.

### Which protocol guarantees delivery?

Answer:
TCP.

### Which protocol is commonly used for gaming?

Answer:
UDP.

### Which OSI layer uses TCP and UDP?

Answer:
Layer 4 (Transport Layer).

### Which protocol retransmits lost packets?

Answer:
TCP.

---

## Personal Notes

What I learned:

* TCP focuses on reliability.
* UDP focuses on speed.
* TCP is used when accurate delivery is important.
* UDP is used when low latency is important.
* Both protocols operate at the Transport Layer.
