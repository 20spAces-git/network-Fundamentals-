## What is IPv4?

IPv4 (Internet Protocol Version 4) is the most widely used protocol for identifying devices on a network.

Every device connected to a network is assigned an IP address so it can send and receive data.

Example IPv4 Address:

192.168.1.10
## IPv4 Address Format
An IPv4 address contains four numbers separated by periods.

* **Example:** `192.168.1.10`
* Each section is called an **octet**. Each octet can contain a value from 0 to 255.
IPv4 allows devices to communicate across local networks and the internet.

Without IP addresses, devices would not know where to send or receive data.

## IPv4 Address Format

An IPv4 address contains four numbers separated by periods.

## Example:

192.168.1.10

Each section is called an octet.

Each octet can contain a value from 0 to 255.

## Public vs Private IP Addresses

Public IP Addresses:
- Accessible from the internet
- Assigned by Internet Service Providers (ISPs)

Private IP Addresses:
- Used inside local networks
- Not directly accessible from the internet

Examples:

Private:
192.168.1.10

Public:
8.8.8.8

## Common Private IP Ranges

Class A:
10.0.0.0 - 10.255.255.255

Class B:
172.16.0.0 - 172.31.255.255

Class C:
192.168.0.0 - 192.168.255.255

## Network and Host Portions

An IP address consists of:

- Network Portion
- Host Portion

Example:

192.168.1.25/24

Network:
192.168.1.0

Host:
25

The network identifies the network itself, while the host identifies a specific device.

## Real-World Example

A laptop receives the IP address:

192.168.1.25

A printer receives:

192.168.1.50

Because both devices are on the same network, they can communicate directly.

## Cybersecurity Connection

IP addresses are essential for:

- Log analysis
- Network monitoring
- Threat detection
- Incident response
- Firewall configuration

Security analysts constantly work with IP addresses when investigating network activity.

## Key Terms

- IPv4
- IP Address
- Public IP
- Private IP
- Octet
- Network Portion
- Host Portion
- Internet Protocol

## Commands to Practice

```bash
# Check your local IP and network configuration
ipconfig
ipconfig /all

# Test connectivity to an external server
ping google.com

# Trace the path packets take across the internet
tracert google.com
