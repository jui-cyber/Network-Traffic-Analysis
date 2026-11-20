# Network Traffic Analysis Using Wireshark

## Project Overview
This project focuses on analyzing network traffic using Wireshark. It is a beginner-level cybersecurity project designed to understand how network communication works and how packets can be monitored and analyzed.

## Objectives
- Understand live network packet capture.
- Analyze DNS queries and responses.
- Understand TCP Three-Way Handshake.
- Examine HTTP and HTTPS/TLS traffic.
- Identify source and destination IP addresses.
- Understand common network protocols.

## Tools Used
- Wireshark
- Windows Command Prompt (CMD)
- Windows Operating System

## Practical Tasks

### 1. Live Packet Capture
Captured live network packets and observed communication between devices.

### 2. DNS Analysis
Used the `dns` display filter to examine DNS queries and responses.

### 3. TCP Three-Way Handshake
Analyzed TCP connection establishment using SYN, SYN-ACK, and ACK flags.

### 4. HTTP Analysis
Observed HTTP requests and examined packet details such as GET requests and Host information.

### 5. HTTPS/TLS Analysis
Observed TLS handshake packets, including Client Hello and Server Hello.

### 6. IP Address Analysis
Used Wireshark filters to identify source and destination IP addresses.

## Wireshark Display Filters

```text
dns
tcp
http
tls
ip.addr == YOUR_IP_ADDRESS
tcp.flags.syn == 1
tcp.flags.syn == 1 && tcp.flags.ack == 0
tcp.port == 443
```

## Project Screenshots

The `screenshots` folder contains practical evidence of:

- Live Packet Capture
- DNS Analysis
- TCP Handshake
- HTTP Analysis
- TLS Analysis
- IP Address Analysis

## Learning Outcomes
- Learned basic network traffic monitoring.
- Understood TCP/IP communication.
- Identified common network protocols.
- Practiced packet analysis using Wireshark.
- Improved foundational cybersecurity and SOC analysis skills.

## Conclusion
This project helped me build practical knowledge of network traffic analysis and understand how Wireshark can be used as a network monitoring and troubleshooting tool.

**Author:** Jui Sarker  
**Field:** Cybersecurity | SOC Analyst Learning Journey
