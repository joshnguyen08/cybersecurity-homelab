# cybersecurity-homelab

## Project Overview

- **pfSense**: Acts as the main router and firewall, controlling network traffic.
- **Security Onion**: Provides network security monitoring, intrusion detection, and traffic analysis.
- **Kali Linux**: Used for penetration testing and vulnerability assessments.
- **Windows Server 2022 and Windows 10 Enterprise**: Serve as target machines for various security tests.
- **Splunk**: Collects and visualizes log data for analysis. (Receives Windows Event Logs, Wazuh Logs)
- **ELK Server**: Collects and visualizes log data for analysis. (Receives Windows Event Logs, Wazuh Logs, Network Traffic from Zeek packet capture via SPAN port)
- **Wazuh**: HIDS/HIPS with EDR functionalities and SIEM. 

- **Virtualization software**: VirtualBox

**Objective:** Simulate real-world security scenarios using virtual machines and networking tools. 


**TODO:**
1. Familiarization with Tools
2. Traffic and Network Monitoring
3. Security Automation
4. Malware Analysis
5. Reverse Engineering


## My current homelab:

PSU - MSI MAG A550 BN Gaming Power Supply - 80 Plus Bronze Certified 550W - Compact Size - ATX PSU 

CPU Cooler - Noctua NH-U12S chromax.Black, 120mm Single-Tower CPU Cooler (Black) 

RAM - 2xCORSAIR VENGEANCE RGB DDR5 RAM 32GB (2x16GB) 6400MHz CL36 Intel XMP iCUE Compatible Computer Memory - Black (CMH32GX5M2B6400C36) 

PC Case- GAMDIAS ATX Mid Tower Gaming Computer PC Case with Tempered Glass Swing Door, 1x 120mm ARGB Fan & Front Panel Sync with Motherboards, Vertical PCIE Slots for Your Graphic Cards (VGA/GPU) 

Motherboard- MSI MAG B650 Tomahawk WiFi Gaming Motherboard (AMD Ryzen 8000/7000, AM5, DDR5, PCIe 4.0, M.2, SATA 6Gb/s, USB 3.2 Gen 2, HDMI/DP, Wi-Fi 6E, Bluetooth 5.3, 2.5Gbps LAN, ATX) 

CPU - AMD Ryzen 5 7600X 6-Core, 12-Thread Unlocked Desktop Processor

GRAPHICS CARD: NVIDIA GeForce GTX 1050 Ti

CPU cooler -  Noctua NH-U12S chromax.Black, 120mm Single-Tower CPU Cooler (Black)

SSD - SAMSUNG 970 EVO Plus SSD 2TB - M.2 NVMe Interface Internal Solid State Drive with V-NAND Technology (MZ-V7S2T0B/AM)

## Tools Used:

Zeek - network traffic capture and monitoring tool

Suricata - network traffic analysis tool for threat detection

Nessus - vulnerability scanner 

Technitium DNS Server - DNS server for blocking malicious domains

Filebeats / Splunk Forwarder / Logstash - forwarding services to ELK/Splunk SIEMs


## Setup and Download: 

Virtualization: 

https://www.virtualbox.org/wiki/Downloads 

Pfsense: 

https://www.pfsense.org/download/  

Security Onion: 

https://github.com/Security-Onion-Solutions/securityonion/blob/master/VERIFY_ISO.md  

https://ubuntu.com/download/desktop  

Kali Linux: 

https://www.kali.org/get-kali/#kali-virtual-machines  

Window Machine: 

https://www.microsoft.com/en-us/evalcenter/evaluate-windows-server-2019  

https://www.microsoft.com/en-us/evalcenter/evaluate-windows-10-enterprise  

Splunk: 

https://ubuntu.com/download/server  

https://www.splunk.com/  

ELK Server:

https://www.elastic.co/downloads  
https://www.elastic.co/guide/en/elasticsearch/reference/current/deb.html  
https://www.elastic.co/guide/en/kibana/8.15/deb.html#deb-repo
