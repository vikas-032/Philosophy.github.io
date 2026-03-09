---
layout: default
title:  "Networking"
date:   2026-03-09 4:29:03 +0530
categories: k8s
---


Computer Networking is the process of connecting multiple computers or devices so they can communicate and share resources like files, printers, and internet access.

Example:
Your laptop accessing a website through the Internet.

2. Types of Networks
LAN (Local Area Network)

A network within a small geographic area.

Examples:

Home Wi-Fi network

Office network

WAN (Wide Area Network)

A network that connects devices over large distances.

Example:

The global Internet

MAN (Metropolitan Area Network)

A network covering a city or metropolitan area.

PAN (Personal Area Network)

Network connecting personal devices.

Example:

Bluetooth between phone and headphones.

3. IP Address

An IP Address (Internet Protocol Address) is a unique identifier assigned to each device in a network.

Example:

192.168.1.1

Types:

IPv4

32-bit address

Example:

192.168.0.1
IPv6

128-bit address

Created to solve IPv4 address exhaustion.

4. DNS (Domain Name System)

DNS converts domain names into IP addresses.

Example:

google.com → 142.250.x.x

Without DNS, users would have to remember numeric IP addresses.

DNS infrastructure is coordinated by organizations such as
Internet Corporation for Assigned Names and Numbers.

5. OSI Model

The OSI Model explains how network communication happens in 7 layers.

Layer	Name	Function
7	Application	User interface
6	Presentation	Data format, encryption
5	Session	Session management
4	Transport	Reliable data delivery
3	Network	Routing
2	Data Link	MAC addressing
1	Physical	Cables, hardware

Interview tip:
Most interviewers ask which layer TCP/IP protocols work on.

6. TCP vs UDP
TCP (Transmission Control Protocol)

Features:

Reliable

Ordered data delivery

Error checking

Used in:

Web browsing

Emails

File transfer

UDP (User Datagram Protocol)

Features:

Faster

No error checking

No guaranteed delivery

Used in:

Video streaming

Online games

Live calls

7. Networking Devices
Router

Connects different networks and directs traffic.

Example:
Home router connecting LAN to the internet.

Switch

Connects devices within a LAN.

Works using MAC addresses.

Modem

Connects your network to the ISP (Internet Service Provider).

Firewall

Security device that filters network traffic.

Example vendors include companies like
Cisco.

8. Ports

Ports allow multiple services on a single IP address.

Common ports:

Port	Protocol
80	HTTP
443	HTTPS
22	SSH
21	FTP

Example:
When you open HTTPS, your browser uses port 443.

9. Subnetting

Subnetting divides a large network into smaller networks.

Example:

192.168.1.0/24

Benefits:

Better network management

Improved security

Efficient IP allocation

This concept is very important when working with cloud platforms like
Amazon Web Services.

10. HTTP vs HTTPS
HTTP

HyperText Transfer Protocol used for web communication.

HTTPS

Secure version of HTTP that uses SSL/TLS encryption.

Example websites:

GitHub

Google Chrome

11. MAC Address

A MAC Address (Media Access Control Address) is a unique hardware identifier assigned to network interfaces.

Example:

00:1A:2B:3C:4D:5E

Used at Layer 2 (Data Link Layer).

12. Packet and Latency
Packet

A small unit of data sent across a network.

Latency

The time taken for data to travel from source to destination.

Lower latency = faster communication.

13. Basic Networking Commands (Often Asked)
Ping

Tests connectivity between devices.

Example:

ping google.com
Traceroute

Shows the path packets take to reach the destination.

IPConfig

Displays IP configuration of your system.

Quick Interview Summary

You must know these 10 topics clearly:

What is networking

LAN / WAN

IP address

DNS

OSI model

TCP vs UDP

Router / Switch

Ports

Subnetting

HTTP vs HTTPS