# secbyte-packet-analysis-wireshark-ics-scada-ot-security-ctf-labs
A practical collection of cybersecurity CTF labs covering network packet capture &amp; analysis (Wireshark fundamentals, display filters, DNS tunneling/leaks, TCP handshake/options data carving, raw wire protocol inspection) and Industrial Control Systems (ICS/SCADA) OT security .
# Wireshark Packet Analysis, Network Protocol Forensics & ICS/SCADA OT Security CTF Labs

Welcome to the **Wireshark Packet Analysis, Network Protocol Forensics & ICS/SCADA OT Security CTF Lab Collection**. This repository serves as an organized, searchable catalog of practical cybersecurity labs hosted on Learn SecByte.

This collection focuses on low-level wire-level packet forensics, network stream reconstruction, Operational Technology (OT) security, and industrial control network defense—spanning **Wireshark Fundamentals, Packet Capture & Display Filtering (Wireshark interface navigation, capture acquisition, advanced display filters)**, **Protocol-Level Network Forensics (DNS exfiltration/tunneling, TCP handshake flags/options data carving, protocol wire inspection)**, **ICS/SCADA Architecture, Safety Impact & Asset Security (HMI security, Purdue model zone trust, safety instrumentation systems)**, and **Industrial Protocol Forensics & OT Incident Response (Substation outage IR, SCADA telemetry monitoring, water plant intrusion analysis)**.

---

## Lab Collection Index

### 1. Wireshark Fundamentals, Packet Capture & Display Filtering
* **Wireshark Fundamentals: Packet Detective**  
  *Lab Link:* [https://learn.secbyte.org/ctf/wireshark-fundamentals-packet-detective](https://learn.secbyte.org/ctf/wireshark-fundamentals-packet-detective)  
  *Focus:* Core principles of Wireshark, capturing raw network traffic (`dumpcap`), navigating packet details/bytes panes, and reconstructing TCP/UDP stream conversations.

* **Packet Capture Pursuit**  
  *Lab Link:* [https://learn.secbyte.org/ctf/packet-capture-pursuit](https://learn.secbyte.org/ctf/packet-capture-pursuit)  
  *Focus:* Analyzing multi-gigabyte PCAP files, extracting embedded binary files from HTTP/FTP streams, and identifying network anomalies across enterprise traffic traces.

<Image src="image_agent_tag_13779428388547677932" alt="Wireshark software internal architecture showing capture engine, packet dissecting, and GUI modules" caption="Wireshark Packet Dissecting & Capture Architecture" />

---

* **Display Filters: Log Sleuthing & Hidden Indicators**  
  *Lab Link:* [https://learn.secbyte.org/ctf/display-filters-log-sleuthing-hidden-indicators](https://learn.secbyte.org/ctf/display-filters-log-sleuthing-hidden-indicators)  
  *Focus:* Writing complex Wireshark display filters (`contains`, `matches`, boolean operators), isolating suspicious port traffic, and locating subtle Indicators of Compromise (IoCs).

### 2. Protocol-Level Network Forensics & Deep Packet Inspection
* **Protocol Analysis: Reading the Wire**  
  *Lab Link:* [https://learn.secbyte.org/ctf/protocol-analysis-reading-the-wire](https://learn.secbyte.org/ctf/protocol-analysis-reading-the-wire)  
  *Focus:* Deep dissection of Ethernet frames, IP packet headers, ARP cache poisoning vectors, ICMP error codes, and low-level protocol encapsulation structures.

* **TCP Analysis: From Handshake to Hidden Data**  
  *Lab Link:* [https://learn.secbyte.org/ctf/tcp-analysis-from-handshake-to-hidden-data](https://learn.secbyte.org/ctf/tcp-analysis-from-handshake-to-hidden-data)  
  *Focus:* Analyzing TCP 3-way handshakes (`SYN`, `SYN-ACK`, `ACK`), identifying out-of-order/retransmission events, and extracting covert data embedded in TCP window size or option fields.

* **DNS Traffic Analysis: Hidden Names & Leaky Queries**  
  *Lab Link:* [https://learn.secbyte.org/ctf/dns-traffic-analysis-hidden-names-leaky-queries](https://learn.secbyte.org/ctf/dns-traffic-analysis-hidden-names-leaky-queries)  
  *Focus:* Detecting DNS tunneling/exfiltration (`DNScat2`, `iodine`), analyzing high-entropy subdomain queries, identifying internal hostname resolution leaks, and parsing TXT record payloads.

### 3. ICS/SCADA Architecture, Safety Impact & Asset Security
