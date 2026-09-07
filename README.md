# Network-traffic-capture-and-analysis-with-Wireshark

### NAME: Sathyaa R
### REG NO: 212223100052

## AIM:
To capture and analyze network traffic using Wireshark in order to observe protocols, packets, and potential anomalies.
## Requirements:
- **Hardware:**
    - Computer with internet access
    - Network adapter (Ethernet/Wi-Fi)
- **Software:**
    - Wireshark (latest stable version)
    - Sample PCAP files (optional for offline analysis)
## Architecture:
```mermaid
flowchart TD
    A[Network Interface Card] --> B[Wireshark Packet Capture Engine]
    B --> C[Packet Decoder & Protocol Analyzer]
    C --> D[Packet Display & Filtering Interface]
    D --> E[Investigator Analyzes Network Data]
    E --> F[Findings: IPs, Ports, Protocols, Anomalies]
```
## DESIGN STEPS:
### Step 1:
Install Wireshark on the system.

### Step 2:
Launch Wireshark and select the network interface (Ethernet/Wi-Fi).

### Step 3:
Start the capture, apply filters (like http, tcp, ip.addr == x.x.x.x) to analyze specific traffic, and stop the capture after observing relevant data.
### Step 4:
**Analyze traffic to identify:**
  - Source & Destination IP addresses
  - Protocols (HTTP, DNS, TCP, UDP, etc.)
  - Suspicious activities (e.g., unusual ports, repeated requests).
## PROGRAM:
Wireshark Packet Capture and Filter Usage

## OUTPUT:
Captured Packets with Protocol Analysis and Detailed Packet Info

<img width="1920" height="1080" alt="1" src="https://github.com/user-attachments/assets/5f038aff-f0c4-44f0-bbec-75df5169232b" />

<img width="1920" height="1080" alt="2" src="https://github.com/user-attachments/assets/51725965-1d11-45e1-839d-0206ad285e96" />

<img width="1920" height="1080" alt="3" src="https://github.com/user-attachments/assets/5272b801-2459-4a3c-b0ab-1375f8b0a8bd" />

<img width="1920" height="1080" alt="4" src="https://github.com/user-attachments/assets/edb16aeb-a260-410d-b32d-efd826e33eb4" />

<img width="1920" height="1080" alt="5" src="https://github.com/user-attachments/assets/121fbcd5-01c0-4d1d-83ae-94de5c782971" />

<img width="1920" height="1080" alt="6" src="https://github.com/user-attachments/assets/d59ce248-ac62-4df5-8f76-825325ef083b" />


## RESULT:
Network traffic was successfully captured and analyzed using Wireshark.
