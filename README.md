# Cyber-Secuity-
CyberSecuirty internship work
I added Nmap from their webpage, and then I knew a local IP range, for example, 192.168.31.1/24 for me to scan. After adding Nmap I completed a TCP SYN scan
nmap -sS 192.168.31.1/24
With this information, I made observations of live hosts and the open ports. If I wanted an even further look, I could have also captured packets in Wireshark and conducted further analysis of the packets. I then created a list of services running on the open ports, for example, HTTP, SSH, SMB, etc, and considered the risk, such as: was there an admin panel exposed, services that were out of date or ports that were of interest, such as port 49152. Finally, I saved the information as .txt and .html so I could document and report.

