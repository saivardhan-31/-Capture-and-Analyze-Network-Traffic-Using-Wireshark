# -Capture-and-Analyze-Network-Traffic-Using-Wireshark

This repository contains my Wireshark Network Traffic Analysis. The objective was to capture live network packets, identify basic protocols, and analyze different types of network traffic.

🛠️ Tools Used
Wireshark (packet capture and analysis)
Ping & Web Browsing (to generate traffic)

📂 Repository Contents
Wireshark_Traffic_Analysis_Report.pdf → Detailed report of the capture and findings
full_capture.pcap → Complete packet capture file
dns.pcap → Filtered DNS packets
tcp.pcap → Filtered TCP packets

🔎 Protocols Identified
DNS → Domain name resolution
ICMP → Ping requests and replies
TCP → Standard web traffic (HTTP/HTTPS)
QUIC (HTTP/3) → UDP-based secure web protocol used by modern browsers

📜 Summary

The analysis shows how different protocols (DNS, ICMP, TCP, QUIC) work together to enable real-time communication on the internet. The presence of QUIC highlights the shift towards HTTP/3 over UDP, improving speed, security, and reliability.
