---
layout: post
title: "Networking Fundamentals: TCP/IP Model"
date: 2025-02-01
categories: networking
tags: tcp-ip networking fundamentals
---

# Networking Fundamentals: TCP/IP Model

Understanding the TCP/IP model is fundamental for anyone working with networks. This model forms the backbone of modern internet communication and is essential knowledge for DevOps engineers.

## What is TCP/IP?

TCP/IP (Transmission Control Protocol/Internet Protocol) is a set of communication protocols used to interconnect network devices on the internet and private networks.

## The Four Layers

### 1. Application Layer
- Protocols: HTTP, FTP, SMTP, DNS, SSH
- Provides user interfaces and network services
- Examples: Web browsing, email transfer

### 2. Transport Layer
- Protocols: TCP, UDP
- Manages end-to-end communication
- TCP: Reliable, connection-oriented
- UDP: Fast, connectionless

### 3. Internet Layer
- Protocols: IP, ICMP, ARP
- Handles logical addressing and routing
- IP addresses identify devices on networks

### 4. Network Access Layer
- Protocols: Ethernet, Wi-Fi
- Handles physical transmission of data
- Manages hardware addressing (MAC addresses)

## Key Concepts

### IP Addressing
- IPv4: 192.168.1.1 (32-bit)
- IPv6: 2001:db8::1 (128-bit)
- Subnet masks define network boundaries

### Ports
- 0-1023: Well-known ports (HTTP: 80, SSH: 22)
- 1024-49151: Registered ports
- 49152-65535: Dynamic ports

### DNS
- Translates domain names to IP addresses
- Hierarchical distributed database
- Essential for internet navigation

## Practical Commands

```bash
# Check IP configuration
ipconfig (Windows)
ifconfig (Linux/Mac)

# Test connectivity
ping google.com

# Trace route
tracert google.com (Windows)
traceroute google.com (Linux)

# Check DNS resolution
nslookup google.com
```

## Conclusion

The TCP/IP model is the foundation of modern networking. Understanding these layers and protocols is crucial for troubleshooting network issues and building reliable distributed systems.
