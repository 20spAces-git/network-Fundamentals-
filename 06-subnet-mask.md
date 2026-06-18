## What is a Subnet Mask?

A subnet mask is a number used to divide an IP address into a network portion and a host portion.

It helps devices determine whether another device is on the same network or a different network.

Example:

255.255.255.0

## Why Subnet Masks Matter

Subnet masks help devices identify which part of an IP address represents the network and which part represents the host.

Without subnet masks, devices would not know how to communicate efficiently on a network.

## Common Subnet Masks

/8  = 255.0.0.0

/16 = 255.255.0.0

/24 = 255.255.255.0

/32 = 255.255.255.255

## Beginner Tip
/24 is the most common subnet mask in home networks.

## How Subnet Masks Work

Example:

IP Address:
192.168.1.25

Subnet Mask:
255.255.255.0

Network Address:
192.168.1.0

Host Address:
25

The subnet mask tells us that the first three sections belong to the network and the last section identifies the device.

## CIDR Notation

CIDR (Classless Inter-Domain Routing) is a shorter way to write subnet masks.

Examples:

/8

/16

/24

Example:

192.168.1.25/24

This means the subnet mask is:

255.255.255.0

## Real-World Example

Laptop:
192.168.1.25/24

Printer:
192.168.1.50/24

Because both devices are on the same network, they can communicate directly.

If a device had a different network address, traffic would need to be sent through a router.

## Cybersecurity Connection

Subnet masks help security analysts:

- Identify network boundaries
- Understand network architecture
- Investigate suspicious activity
- Configure firewalls
- Analyze logs and alerts

Subnetting knowledge is commonly used in SOC, DFIR, and network security roles.

## Key Terms

- Subnet Mask
- CIDR
- Network Address
- Host Address
- IPv4
- Network Portion
- Host Portion
- Router

## Commands to Practice

```bash
# Check your local IP and subnet mask configuration
ipconfig
ipconfig /all

# Test connectivity to your default gateway
ping 192.168.1.1

# Trace the path packets take across the internet
tracert google.com

## Key Takeaways

- Subnet masks divide networks into network and host portions.
- CIDR notation is a shortened way to write subnet masks.
- /24 is one of the most common subnet masks.
- Subnet masks help devices determine where traffic should be sent.
- Subnet masks are important for cybersecurity and network administration.

### What is a subnet mask?

A number used to divide an IP address into network and host portions.

### What does a subnet mask help determine?

Whether devices are on the same network.

### What is the subnet mask for /24?

255.255.255.0

### What does CIDR stand for?

Classless Inter-Domain Routing.

### What is the most common home network subnet?

/24 or 255.255.255.0

### Why are subnet masks important?

They help devices communicate correctly and define network boundaries.

## Personal Notes

What I learned:

- Subnet masks divide networks into network and host portions.
- CIDR notation is a shortcut for subnet masks.
- /24 is very common in home networks.
- Subnet masks help determine where traffic should go.
- Understanding subnet masks is important for cybersecurity.
