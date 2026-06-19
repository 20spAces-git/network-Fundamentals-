# DNS (Domain Name System)

## What is DNS?

DNS (Domain Name System) is a service that translates human-readable domain names into IP addresses.

Without DNS, users would need to remember IP addresses instead of website names.

Example:

google.com → 142.250.x.x

---

## Why DNS Matters

Computers communicate using IP addresses, but humans prefer easy-to-remember names.

DNS acts like the internet's phone book by matching names to IP addresses.

---

## How DNS Works

When you type a website into your browser:

1. You enter a domain name.
2. Your computer sends a DNS request.
3. A DNS server looks up the IP address.
4. The IP address is returned.
5. Your browser connects to the website.

Example:

youtube.com
↓
DNS Lookup
↓
IP Address
↓
Website Loads

---

## DNS Components

### Domain Name

A human-readable website name.

Examples:

* google.com
* youtube.com
* tryhackme.com

---

### DNS Server

A server that responds to DNS requests and provides IP addresses.

Common DNS Providers:

* Google DNS (8.8.8.8)
* Cloudflare DNS (1.1.1.1)

---

### DNS Query

A request sent by a device asking for the IP address associated with a domain name.

---

### DNS Response

The answer returned by a DNS server containing the requested IP address.

---

## Real-World Example

You type:

github.com

Your computer asks a DNS server:

"What IP address belongs to github.com?"

The DNS server responds with the IP address.

Your browser then connects to GitHub.

---

## DNS and Ports

DNS commonly uses:

Port 53

Protocols:

* UDP (most requests)
* TCP (larger responses)

---

## Cybersecurity Connection

DNS plays a major role in cybersecurity.

Security teams use DNS data to:

* Investigate suspicious domains
* Detect malware communication
* Analyze phishing attempts
* Monitor network activity

Many cyber attacks involve DNS in some way.

---

## Key Terms

* DNS
* Domain Name
* DNS Server
* DNS Query
* DNS Response
* IP Address
* Port 53
* UDP
* TCP

---

## Commands to Practice

```bash
# Query a DNS server to find the IP address of a domain
nslookup github.com

# View your local DNS cache and network configuration
ipconfig /displaydns

---

## Key Takeaways

* DNS stands for Domain Name System.
* DNS translates names into IP addresses.
* DNS commonly uses Port 53.
* DNS allows users to access websites without memorizing IP addresses.
* DNS is important in networking and cybersecurity.

---

## Practice Questions & Answers

### What does DNS stand for?

Answer:
Domain Name System.

### What does DNS do?

Answer:
It translates domain names into IP addresses.

### What port does DNS use?

Answer:
Port 53.

### Why is DNS important?

Answer:
It allows users to access websites using names instead of IP addresses.

### What command can be used to test DNS lookups?

Answer:

nslookup

### What is a DNS query?

Answer:
A request asking for the IP address of a domain name.

---

## Personal Notes

What I learned:

* DNS translates website names into IP addresses.
* DNS acts like the internet's phone book.
* DNS commonly uses Port 53.
* DNS is used every time I visit a website.
* DNS data is frequently analyzed during cybersecurity investigations.
