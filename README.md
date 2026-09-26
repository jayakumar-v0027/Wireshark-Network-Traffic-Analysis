# Wireshark Network Traffic Analysis

## Project Overview

A hands-on networking and cybersecurity project using Wireshark on Kali Linux.

The objective of this project was to capture, filter, and analyze network packets to understand how common protocols communicate at the packet level.

## Tools Used

- Kali Linux
- Wireshark
- Ping
- Linux networking commands
## Protocols Analyzed

### 1. ICMP

ICMP traffic was generated using the `ping` command and analyzed in Wireshark.

#### Observations

- ICMP Echo Request
- ICMP Echo Reply
- Source and destination IP addresses
- Packet length
- TTL (Time To Live)
- IPv4 header information

Wireshark filter:

`icmp`

### 2. DNS

DNS traffic was captured and analyzed to understand domain-name resolution.

#### Observations

- DNS Standard Query
- DNS Standard Query Response
- A records
- AAAA records
- Source and destination IP addresses
- DNS packet information

Wireshark filter:

`dns`

## Packet Analysis

The captured packets were inspected using Wireshark's packet list, packet details, and packet bytes sections.

The analysis helped me understand how network communication can be examined at different protocol layers.

## Screenshots

The `screenshots` directory contains:

- ICMP packet analysis
- ICMP response analysis
- DNS filtered traffic
- DNS packet analysis

## Capture Files

The `captures` directory contains the original Wireshark packet captures:

- `ICMP_Capture.pcapng`
- `DNS_Capture.pcapng`

These files can be opened using Wireshark for further analysis.

## Learning Outcomes

Through this project, I learned how to:

- Capture network traffic using Wireshark
- Apply Wireshark display filters
- Identify network protocols
- Analyze ICMP Echo Request and Reply packets
- Understand basic DNS queries and responses
- Inspect IPv4 packet headers
- Read source and destination addresses
- Examine packet-level network communication

## Environment

**Operating System:** Kali Linux  
**Tool:** Wireshark  
**Project Area:** Networking & Cybersecurity  
**Level:** Beginner / Hands-on Lab
