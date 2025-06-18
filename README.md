# Wireshark Network Traffic Analysis

This project presents a detailed analysis of real-time network traffic using Wireshark. It focuses on inspecting and understanding common network protocols across multiple OSI layers. The project was conducted on both Windows 11 and Kali Linux environments using Wireshark as the primary packet capture and analysis tool.

## Objectives

- Capture and analyze real-world network traffic.
- Understand protocol behavior across TCP/IP stack layers.
- Strengthen practical skills in network troubleshooting and traffic inspection.

## Protocols Analyzed

### 1. TCP (Transmission Control Protocol)
- Captured and explained the three-way handshake process (SYN, SYN-ACK, ACK).
- Identified sequence and acknowledgment numbers, window sizes, and flags.

### 2. DNS (Domain Name System)
- Observed DNS queries and corresponding responses during name resolution.
- Analyzed UDP-based DNS requests to resolve external domains.

### 3. HTTP (Hypertext Transfer Protocol)
- Analyzed HTTP GET requests and HTTP 200 OK/404 responses.
- Reviewed the request headers and server replies.

### 4. ICMP (Internet Control Message Protocol)
- Captured ICMP Echo Requests and Echo Replies (ping).
- Verified connectivity and round-trip time between host and external server.

### 5. ARP (Address Resolution Protocol)
- Examined ARP Requests and Replies used to resolve IP addresses to MAC addresses within the LAN.

### 6. DHCP (Dynamic Host Configuration Protocol)
- Checked for presence of DHCP Discover, Offer, Request, and Acknowledgment messages.
- Observed that the host had a pre-assigned IP, and thus DHCP negotiation was not active during capture.

## Tools Used

- **Wireshark** (on both Kali Linux and Windows 11)
- **Command Line Tools**: `ping`, `ipconfig`, `ipconfig /release`, `ipconfig /renew`
- **Wireshark Filters**: `tcp`, `dns`, `http`, `icmp`, `arp`, `bootp`

## Files Included

- `Wireshark Traffic Analysis Project Report.docx` – Complete protocol analysis report with descriptions, packet numbers, and screenshots.
- `wireshark_capture.pcapng` – The original Wireshark capture file used for this project.
- `screenshots/` – Contains labeled screenshots of packets for each analyzed protocol.

> To view `wireshark_capture.pcapng`, open it using Wireshark.  
> Apply filters such as `tcp`, `dns`, `http`, `icmp`, `arp`, or `bootp` to examine specific protocol traffic.

## Skills Demonstrated

- Network protocol analysis and interpretation
- Understanding of OSI and TCP/IP layers
- Real-time packet filtering and inspection
- Foundational network forensics and traffic auditing

## Author

**Olina Kundu**  
Cybersecurity & Networking Enthusiast    
GitHub: [github.com/OlinaKundu](https://github.com/OlinaKundu)
