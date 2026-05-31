# Local Network Port Scanning Lab

**Author:** Harsh Yadav

## Objective
Discover open ports on devices within a local network and understand network exposure.

## Tools Used
- Nmap
- Wireshark (optional)

## Commands
nmap -sS 192.168.1.0/24
nmap -sS -sV 192.168.1.0/24
nmap -sS 192.168.1.0/24 -oN scan.txt

## Methodology
1. Identified the local IP range.
2. Performed a TCP SYN scan.
3. Recorded discovered hosts and open ports.
4. Identified services running on those ports.
5. Evaluated potential security risks.

## Key Concepts
- Port Scanning
- TCP SYN Scan
- Network Reconnaissance
- Service Enumeration
- Firewall Security

## Interview Questions
- What is an open port?
- How does a TCP SYN scan work?
- What risks are associated with open ports?
- Difference between TCP and UDP scanning?
- How can open ports be secured?
- What is the role of a firewall?
- Why do attackers perform port scans?
- How does Wireshark help?

## Conclusion
Port scanning helps identify exposed services and improve network security.
