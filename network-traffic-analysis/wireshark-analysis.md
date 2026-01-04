# Network Traffic Analysis Using Wireshark

## Objective
Analyze TCP, FTP, and HTTP traffic to understand how data flows across a network
and how credentials can be exposed.

## Environment
- OS: Kali Linux
- Tool: Wireshark
- Interface: eth0

## Steps Performed
1. Identified local IP address using `ifconfig`
2. Captured live traffic on eth0
3. Connected to an FTP server and downloaded a file
4. Stopped capture and analyzed packets

## Protocols Observed
- TCP – reliable data transmission
- DNS – name resolution
- ARP – MAC address resolution
- DHCP – IP address assignment
- FTP – file transfer

## Findings
- FTP transmits credentials in cleartext
- Ephemeral source ports are automatically assigned
- TCP connections follow a three-way handshake (SYN, SYN-ACK, ACK)

## Security Impact
Unencrypted protocols expose sensitive data and should be replaced with secure
alternatives such as SFTP or FTPS.
