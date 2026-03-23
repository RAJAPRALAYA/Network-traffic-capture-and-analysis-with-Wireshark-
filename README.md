# Network-traffic-capture-and-analysis-with-Wireshark
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

<img width="1147" height="636" alt="image" src="https://github.com/user-attachments/assets/7b821d5e-9471-4ff7-b492-5d98a93c2b3b" />

<img width="1156" height="640" alt="image" src="https://github.com/user-attachments/assets/ea05bf8b-0f68-43bd-a6dd-4c55ceb0c743" />

<img width="1152" height="614" alt="image" src="https://github.com/user-attachments/assets/da3e70b4-ec69-480b-9580-368de7523f38" />

<img width="1159" height="638" alt="image" src="https://github.com/user-attachments/assets/8a834bee-96f0-434d-9386-7619f8b6a600" />

<img width="1159" height="635" alt="image" src="https://github.com/user-attachments/assets/3ffd5517-41c8-4687-98cb-c56f6d4ea863" />


<img width="1158" height="636" alt="image" src="https://github.com/user-attachments/assets/2bc59dad-41d5-40c2-ad6c-9c22ff49f1e1" />


## RESULT:
Network traffic was successfully captured and analyzed using Wireshark.
