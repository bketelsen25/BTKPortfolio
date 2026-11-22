---
layout: default
title: Reflections
---

# Reflections

**Assignment 1 – Network Models, Cabling, and Basic Command-Line Tools**

This assignment introduced me to the OSI and TCP/IP models and how data is encapsulated as it moves from an application down to bits on the wire. I also learned how physical components like wall jacks, patch panels, and the MDF/IDF connect a device to the internet, and I used tools like ping, tracert, and ipconfig to examine my own network.

One challenge was keeping straight which layer each protocol and address belongs to, such as MAC versus IP. Mapping my home network and tracing the route to Amazon and UCF made these concepts much more concrete.

**Assignment 2 – Protocols, Addressing, and Wireshark Traces**

This assignment taught me how common protocols, port numbers, MAC addresses, and IP address classes work together. I used Wireshark to compare how HTTP, TCP, UDP, and DNS behave, including the TCP three-way handshake and DNS queries and responses.

One challenge was understanding how the sequence and acknowledgment numbers change during the handshake. Looking at the real packets helped me see why TCP is reliable while UDP is faster and connectionless, and how DNS TTL values affect network traffic.

**Assignment 3 – Physical Media, Wireless Networking, and Throughput**

This assignment covered cabling types, signal problems like attenuation and crosstalk, and how Wi-Fi works through SSIDs, frames, and security standards. In Wireshark, I measured the throughput of a real download and compared it to my link speed. I also counted 802.11 management, control, and data frames.

One challenge was calculating throughput and network utilization correctly. Finding that most of the captured wireless frames were overhead helped me understand why real-world speeds fall short of theoretical bandwidth.

**Assignment 4 – Virtualization, Subnetting, and HTTP Behavior**

This assignment introduced me to virtualization, cloud service models, and VirtualBox, where I set up an Ubuntu VM. I also practiced IP address classes, subnetting, and VLAN design, and used Wireshark to study how HTTP handles conditional requests, embedded objects, and authentication.

Subnetting was the biggest challenge, especially working out block sizes and network and broadcast addresses. Working through the calculations step by step made it far more manageable, and seeing a 304 Not Modified response showed how caching saves bandwidth.

**Assignment 5 and 6 – Network Security, WAN Technologies, and TCP Performance**

These assignments covered security certifications, GRC tools, firewalls, DMZs, switch security, STP, and WAN options like MPLS and site-to-site VPNs. I also used Wireshark to compare TCP retransmissions and duplicate ACKs on a normal download and a lossy network.

One challenge was comparing the whole capture to a single TCP stream and calculating retransmission rates. Seeing a 1.26% retransmission rate on the lossy network, versus 0.126% on the normal download, showed me how packet loss affects performance and how TCP recovers from it.

**Quizzes and Discussions**

The quiz and discussion assignments were also very helpful for filling in the gaps between the major assignments. The discussions were fun for looking into various emerging areas of IT and seeing how they could affect networking now or in the future. I especially appreciated the quizzes, because the multiple-choice practice was extremely helpful for reviewing content before the midterm exam, and I believe my high score on the midterm can largely be credited to the review material in the quizzes.

**Overall Reflection**

I am very interested in the networking field, and I will likely pursue a career in networking post-graduation. My internship last summer solidified this interest, and this course has given me a great foundation I can build on to continue my growth as a student and intern, and eventually enter the professional world as an experienced technician. I am grateful for all of the opportunities this course has provided, and I look forward to continuing my networking coursework next semester.
