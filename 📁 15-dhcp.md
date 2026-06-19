# DHCP (Dynamic Host Configuration Protocol)

## What is DHCP?

DHCP (Dynamic Host Configuration Protocol) is a network protocol that automatically assigns network settings to devices.

Instead of manually configuring every device, DHCP automatically provides:

* IP Address
* Subnet Mask
* Default Gateway
* DNS Server

---

## Why DHCP Matters

Without DHCP, every device would need to be manually configured before joining a network.

DHCP simplifies network management and allows devices to connect quickly.

---

## How DHCP Works

When a device joins a network, it requests network settings from a DHCP server.

The DHCP server responds with the necessary configuration information.

This process allows the device to communicate on the network and access the internet.

---

## The DHCP Process (DORA)

DHCP uses a four-step process commonly called DORA.

### Discover

The device broadcasts a request looking for a DHCP server.

### Offer

The DHCP server offers an available IP address.

### Request

The device requests the offered IP address.

### Acknowledge

The DHCP server confirms the assignment.

---

## Information Provided by DHCP

DHCP commonly assigns:

* IP Address
* Subnet Mask
* Default Gateway
* DNS Server

Example:

IP Address:
192.168.1.25

Subnet Mask:
255.255.255.0

Default Gateway:
192.168.1.1

DNS Server:
8.8.8.8

---

## Real-World Example

When you connect your laptop to Wi-Fi:

1. The laptop joins the network.
2. A DHCP server assigns an IP address.
3. The laptop receives network settings.
4. Internet access becomes available.

This process usually happens in seconds.

---

## DHCP Ports

DHCP uses:

Port 67 (Server)

Port 68 (Client)

Protocol:

UDP

---

## Cybersecurity Connection

Security teams frequently investigate DHCP information when troubleshooting devices and analyzing network activity.

DHCP logs can help identify:

* New devices joining a network
* Device IP assignments
* Network configuration issues
* Unauthorized devices

Understanding DHCP is important for network monitoring and incident response.

---

## Key Terms

* DHCP
* DORA
* IP Address
* Subnet Mask
* Default Gateway
* DNS Server
* UDP
* Port 67
* Port 68

---

## Commands to Practice

```bash
# View your current DHCP-assigned configuration and lease info
ipconfig /all

# Release your current DHCP IP address lease
ipconfig /release

# Request a brand new IP address lease from the DHCP server
ipconfig /renew

---

## Key Takeaways

* DHCP stands for Dynamic Host Configuration Protocol.
* DHCP automatically assigns network settings.
* DHCP uses the DORA process.
* DHCP commonly uses UDP ports 67 and 68.
* DHCP simplifies network management.
* Most home and business networks use DHCP.

---

## Practice Questions & Answers

### What does DHCP stand for?

Answer:
Dynamic Host Configuration Protocol.

### What is DHCP used for?

Answer:
Automatically assigning network settings to devices.

### What does DORA stand for?

Answer:
Discover, Offer, Request, Acknowledge.

### What port does a DHCP server use?

Answer:
UDP Port 67.

### What port does a DHCP client use?

Answer:
UDP Port 68.

### What information does DHCP provide?

Answer:
IP Address, Subnet Mask, Default Gateway, and DNS Server.

### Why is DHCP important?

Answer:
It allows devices to join networks without manual configuration.

---

## Personal Notes

What I learned:

* DHCP automatically configures devices on a network.
* DORA describes the DHCP assignment process.
* DHCP provides IP addresses and other network settings.
* DHCP uses UDP ports 67 and 68.
* Most networks rely on DHCP to simplify administration.
