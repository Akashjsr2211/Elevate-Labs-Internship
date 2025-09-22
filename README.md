# Network Reconnaissance & Analysis

This project demonstrates basic network reconnaissance and packet analysis techniques using Linux command-line tools and Wireshark. It covers discovering a host’s IP address, performing a TCP SYN scan using Nmap, and analyzing the resulting packets with Wireshark.

---

## Overview

This repository documents:

- Finding the host machine’s IP address using `ifconfig`
- Performing a **TCP SYN scan** using **Nmap**
- Capturing and analyzing packets with **Wireshark**

This setup is intended purely for **educational and ethical purposes** — only run scans on systems you own or have permission to test.

---

## Tools Used

| Tool         | Purpose                                                     |
|--------------|-------------------------------------------------------------|
| **ifconfig** | Displays network interface information (IP, MAC, etc.)       |
| **Nmap**     | Network scanning and reconnaissance tool                     |
| **Wireshark**| Packet capturing and deep network analysis tool              |

---

## Steps Performed

### 1. Discovering IP Address

Use `ifconfig` to identify your machine’s IP address:

```bash
ifconfig
