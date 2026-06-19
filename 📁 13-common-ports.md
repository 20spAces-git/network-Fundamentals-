# Common Ports

## What is a Port?

A port is a logical communication endpoint used by applications and services to send and receive network traffic.

Ports help devices determine which application should receive incoming data.

Think of an IP address as an apartment building and a port as a specific apartment number.

---

## Why Ports Matter

Ports allow multiple services to operate on the same device at the same time.

Without ports, computers would not know which application should receive network traffic.

Understanding ports is essential for networking, cybersecurity, and troubleshooting.

---

## Common Port Numbers

| Port  | Protocol | Service              |
| ----- | -------- | -------------------- |
| 20/21 | TCP      | FTP                  |
| 22    | TCP      | SSH                  |
| 23    | TCP      | Telnet               |
| 25    | TCP      | SMTP                 |
| 53    | TCP/UDP  | DNS                  |
| 67/68 | UDP      | DHCP                 |
| 80    | TCP      | HTTP                 |
| 110   | TCP      | POP3                 |
| 143   | TCP      | IMAP                 |
| 443   | TCP      | HTTPS                |
| 3389  | TCP      | Remote Desktop (RDP) |

---

## Port 20/21 - FTP

FTP (File Transfer Protocol) is used to transfer files between systems.

FTP is considered insecure because data is transmitted without encryption.

---

## Port 22 - SSH

SSH (Secure Shell) provides encrypted remote access to systems.

SSH is commonly used by system administrators and security professionals.

---

## Port 23 - Telnet

Telnet provides remote access but does not encrypt traffic.

Because of security concerns, SSH has largely replaced Telnet.

---

## Port 25 - SMTP

SMTP (Simple Mail Transfer Protocol) is used to send email.

---

## Port 53 - DNS

DNS translates domain names into IP addresses.

Example:

google.com → IP Address

---

## Port 67/68 - DHCP

DHCP automatically assigns network settings such as:

* IP Address
* Subnet Mask
* Default Gateway
* DNS Server

---

## Port 80 - HTTP

HTTP is used for unencrypted web traffic.

Websites using HTTP do not encrypt data.

---

## Port 443 - HTTPS

HTTPS is the secure version of HTTP.

HTTPS encrypts communication using SSL/TLS.

Most modern websites use HTTPS.

---

## Port 3389 - RDP

Remote Desktop Protocol allows users to remotely access Windows systems.

RDP is commonly used by administrators and support personnel.

---

## Real-World Example

When you visit:

https://google.com

Your browser typically communicates using:

Port 443

When a computer requests a DNS lookup:

Port 53 is used.

When a system receives an IP address automatically:

Ports 67 and 68 are used.

---

## Cybersecurity Connection

Ports are frequently used during:

* Network scanning
* Vulnerability assessments
* Incident response
* Firewall configuration
* Penetration testing

Security analysts often investigate open ports to identify services running on systems.

---

## Key Terms

* Port
* TCP
* UDP
* Service
* FTP
* SSH
* DNS
* DHCP
* HTTP
* HTTPS
* RDP

---

## Commands to Practice

netstat -an

ipconfig /all

ping google.com

---

## Key Takeaways

* Ports identify specific services and applications.
* Different services use different port numbers.
* Port 22 is SSH.
* Port 53 is DNS.
* Port 80 is HTTP.
* Port 443 is HTTPS.
* Port 3389 is RDP.
* Ports are important in cybersecurity and networking.

---

## Practice Questions & Answers

* **Q: What is a port?**
  * **A:** A logical communication endpoint used by applications and services to manage network traffic.
* **Q: What port does SSH use?**
  * **A:** Port 22.
* **Q: What port does DNS use?**
  * **A:** Port 53.
* **Q: What port does HTTP use?**
  * **A:** Port 80.
* **Q: What port does HTTPS use?**
  * **A:** Port 443.
* **Q: What port does Remote Desktop (RDP) use?**
  * **A:** Port 3389.
* **Q: Which protocol is more secure, HTTP or HTTPS?**
  * **A:** HTTPS, because it encrypts the traffic using SSL/TLS.
* **Q: What service uses ports 67 and 68?**
  * **A:** DHCP (Dynamic Host Configuration Protocol).

---

## Personal Notes

* Ports help identify specific network services running on a host.
* Common ports appear constantly in networking troubleshooting and cybersecurity packet analysis.
* Memorizing these key ports (like 22, 53, 80, 443) makes it much faster to read firewall logs and identify traffic types.
