# Collision Domain

## What is a Collision Domain?

A collision domain is a section of a network where devices share the same communication medium and data collisions can occur.

A collision happens when two devices attempt to send data at the same time.

---

## Why Collision Domains Matter

Collisions can slow down network performance because devices must resend their data.

Modern networks use switches to reduce collisions and improve efficiency.

---

## How Collision Domains Work

Imagine two computers trying to send data across the same connection at the same time.

The data can collide, causing both transmissions to fail.

The devices must then wait and retransmit the information.

---

## Collision Example

Example:

PC1 sends data.

PC2 sends data at the same time.

The data collides.

Both devices must retransmit their information.

This creates delays and reduces network performance.

---

## Devices and Collision Domains

### Hub

A hub creates one large collision domain.

All connected devices share the same communication channel.

Because of this, collisions are more likely.

### Switch

A switch creates a separate collision domain for each port.

This greatly reduces collisions and improves performance.

---

## Real-World Example

A network with 20 computers connected to a hub shares one collision domain.

A network with 20 computers connected to a switch creates 20 separate collision domains.

The switched network performs much better.

---

## Hub vs Switch Comparison

| Device | Collision Domains             |
| ------ | ----------------------------- |
| Hub    | One Large Collision Domain    |
| Switch | One Collision Domain Per Port |

---

## Cybersecurity Connection

Understanding collision domains helps analysts understand how network traffic flows.

While collisions are less common in modern switched networks, collision domains remain an important networking concept and are often discussed in networking and cybersecurity certifications.

---

## Key Terms

* Collision Domain
* Collision
* Hub
* Switch
* Ethernet
* Network Traffic
* Packet
* Retransmission

---

## Commands to Practice

```bash
# Check your local network configuration
ipconfig

# Test connectivity to an external server
ping google.com

# Trace the route packets take to leave your network segment
tracert google.com

---

## Key Takeaways

* A collision occurs when two devices send data simultaneously.
* Hubs create one large collision domain.
* Switches create separate collision domains for each port.
* Switches reduce collisions and improve performance.
* Modern networks primarily use switches.

---

## Practice Questions & Answers

### What is a collision domain?


A network segment where data collisions can occur.

### What is a collision?


When two devices attempt to send data at the same time.

### Which device creates one large collision domain?


A hub.

### Which device creates separate collision domains?


A switch.

### Why are switches more efficient?


They reduce collisions and improve network performance.

### Are collisions common in modern networks?


No, because most modern networks use switches.

---

## Personal Notes

What I learned:

* Collisions happen when devices transmit at the same time.
* Hubs create one large collision domain.
* Switches create separate collision domains.
* Switches improve network performance by reducing collisions.
* Modern networks rarely experience collisions because switches are widely used.
