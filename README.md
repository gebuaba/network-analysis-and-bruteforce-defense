# Network Traffic Analysis & Brute Force Defense

## Project Overview
This project demonstrates hands-on cybersecurity fundamentals covering
network traffic analysis and password security defense.

The work combines offensive testing (brute-force simulation) with defensive
controls (password hardening and account lockout), reflecting a Purple Team approach.

---

## Tools & Technologies
- Kali Linux
- Wireshark
- Hydra
- Burp Suite
- SSH
- PAM (pwquality, faillock)
- FTP, TCP/IP

---

## Project Sections

### 1️⃣ Network Traffic Analysis (Wireshark)
- Captured and analyzed live network traffic
- Identified TCP handshakes, FTP authentication, and ephemeral ports
- Examined protocol behavior (TCP, DNS, ARP, DHCP, FTP)

### 2️⃣ Password Security & Brute Force Defense
- Performed controlled brute-force attacks using Hydra
- Implemented strong password policies using PAM
- Configured account lockout mechanisms
- Verified effectiveness against repeated attack attempts

---

## Key Security Lessons
- Cleartext protocols like FTP expose credentials
- Weak passwords are easily compromised
- Account lockout and strong password policies significantly reduce risk
- Defensive controls must be tested, not assumed

---

## Disclaimer
All testing was conducted in controlled lab environments or intentionally
vulnerable systems for educational purposes only.
