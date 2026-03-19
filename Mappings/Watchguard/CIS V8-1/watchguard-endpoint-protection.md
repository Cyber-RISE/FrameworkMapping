# WatchGuard Endpoint Protection

CIS Controls v8 safeguard mappings for **WatchGuard Endpoint Protection**.

| CIS Safeguard | Safeguard Title | Alignment | Evidence |
|---|---|---|---|
| 1.1 | Establish and Maintain a Detailed Enterprise Asset Inventory | Facilitates |  |
| 1.3 | Utilize an Active Discovery Tool | Full |  |
| 2.1 | Establish and Maintain a Software Inventory | Validates; Facilitates |  |
| 2.4 | Utilize Automated Software Inventory Tools | Validates; Full | WatchGuard Endpoint Security updates its Software Inventory automatically every hour. |
| 4.1 | Establish and Maintain a Secure Configuration Process | Facilitates |  |
| 4.4 | Implement and Manage a Firewall on Servers | Partial |  |
| 4.5 | Implement and Manage a Firewall on End-User Devices | Validates; Full | WatchGuard EPDR includes a host-based firewall for Windows comprised of: System rules: Communication characteristics (ports, IP addresses, protocols, etc.), allowing or denying (default action configurable) the data flows that match the configured rules. Program rules : Allow or prevent the programs installed on users’ devices from communicating with other devices. Intrusion detection system: Detects and rejects malformed traffic patterns that can affect the security or performance of protected devices. |
| 4.11 | Enforce Remote Wipe Capability on Portable End-User Devices | Partial | WatchGuard Endpoint Security provides Mobile Device Management capabilities for Android and iOS, including the ability to wipe and lock mobile devices. |
| 10.1 | Deploy and Maintain Anti-Malware Software | Full | WatchGuard Endpoint Security includes a full endpoint anti-malware stack for Windows, macOS, Linux, Android and iOS. |
| 10.2 | Configure Automatic Anti-Malware Signature Updates | Full | WatchGuard Endpoint Security implements signature file updates automatically in Windows, macOS, Linux, Android and iOS devices. |
| 10.4 | Configure Automatic Anti-Malware Scanning of Removable Media | Full | WatchGuard Endpoint Security can perform full removable media on-demand scans and will otherwise scan removable media content on-access on Windows devices. |
| 10.6 | Centrally Manage Anti-Malware Software | Full | Endpoint Security and other WatchGuard Products and Services are centrally managed from anywhere via the WatchGuard Cloud platform. |
| 10.7 | Use Behavior-Based Anti-Malware Software | Full | WatchGuard EPDR provides both behavioral and context-based malware/attack detections on Windows and Linux. |
| 13.2 | Deploy a Host-Based Intrusion Detection Solution | Full | WatchGuard EPP includes a host-based firewall with HIPS for Windows to detect and reject malformed traffic crafted to impact the security or performance of protected devices, including IP Explicit Path, Land Attack, SYN Flood, TCP Port Scan, TCP Flags Check, Header Lengths, UDP Flood, UDP Port Scan, Smart WINS, Smart DNS, Smart DHCP, ICMP Attack, IMCP Filter Echo Request, Smart ARP and OS Detection. |
| 13.7 | Deploy a Host-Based Intrusion Prevention Solution | Full | WatchGuard EPP includes a host-based firewall with HIPS for Windows to detect and reject malformed traffic crafted to impact the security or performance of protected devices, including IP Explicit Path, Land Attack, SYN Flood, TCP Port Scan, TCP Flags Check, Header Lengths, UDP Flood, UDP Port Scan, Smart WINS, Smart DNS, Smart DHCP, ICMP Attack, IMCP Filter Echo Request, Smart ARP and OS Detection. |
