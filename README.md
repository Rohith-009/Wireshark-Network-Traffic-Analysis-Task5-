
# Wireshark-Network-Traffic-Analysis-Task5-

## Objective
To capture real-time network packets using Wireshark and analyze different protocols such as TCP, DNS, HTTP, and ICMP.

##  Tools Used
- Wireshark (Packet Sniffer)
- Windows OS (or Linux/Mac)

---

##  Steps Performed
1. Installed and launched Wireshark.
2. Selected the active network interface (Wi-Fi).
3. Started live capture.
4. Browsed websites and pinged a server to generate traffic.
5. Stopped the capture after 2 minutes.
6. Applied filters for protocol analysis:
   - HTTP: `http`
   - DNS: `dns`
   - TCP: `tcp`
   - ICMP: `icmp`
7. Exported the capture as `.pcap`.

---

##  Protocols Identified and Findings

###  1. TCP (Transmission Control Protocol)
- Used for reliable communication
- Observed 3-way handshake: SYN, SYN-ACK, ACK
- Source and destination ports visible
- Found in most website traffic

###  2. DNS (Domain Name System)
- Used to resolve domain names into IP addresses
- Example: Query for `google.com`
- UDP transport protocol observed

###  3. ICMP (Internet Control Message Protocol)
- Used for network diagnostics (ping)
- Echo request and echo reply packets captured
- Helps detect network reachability

###  4. HTTP/HTTPS
- Client requesting webpage content
- HTTPS payload encrypted for security
- Visible host and server handshake details

-
##  Conclusion
This task improved packet-level visibility and enhanced understanding of TCP/IP communication. Wireshark is extremely useful for network troubleshooting, cybersecurity investigation, and protocol inspection.

---

##  Author
Aluri Rohith
Cyber Security Internship Task 5 Submission
