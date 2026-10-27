# Wireshark Network Traffic Analysis

## Overview
Analyzed network traffic using Wireshark on Windows 11 to understand DNS queries, TCP connections, IP addresses, ports, and TCP flags.

## Tools Used
- Wireshark
- Windows 11

## Analysis
- Used the `dns` filter to inspect DNS queries.
- Used the `tcp` filter to examine TCP traffic.
- Used `tcp.flags.syn == 1` to identify TCP SYN and SYN-ACK packets.
- Observed TCP retransmissions, which may occur due to delayed or lost packets.

## Key Learning
Gained practical experience with Wireshark filters, DNS traffic, TCP connections, and basic network traffic investigation.

## Evidence
- `Wireshark-Network-Analysis.pcapng` — Packet capture
- `tcp-syn-analysis.png` — Analysis screenshot

## Conclusion
This project strengthened my foundational network traffic analysis skills relevant to cybersecurity and SOC operations.
