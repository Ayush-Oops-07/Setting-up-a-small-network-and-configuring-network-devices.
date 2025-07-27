===========================================================
Project Title : Setting Up a Small Network and Configuring Devices
Submitted By  : Ayush Kumar Sharma
Tool Used     : Cisco Packet Tracer
===========================================================

📌 DESCRIPTION:
This project simulates a small wired and wireless network setup including a router, switch, PCs, a printer, and a wireless-enabled laptop using Cisco Packet Tracer. Each device is assigned a static IP and connectivity is verified using ping tests.

-----------------------------------------------------------
🛠️ REQUIREMENTS:
- Cisco Packet Tracer (v7.2 or above recommended)
- Basic networking knowledge (IP addressing, router config)
- Project Files:
   └── network_project.pkt
   └── Screenshots folder (for documentation)

-----------------------------------------------------------
📦 FILE STRUCTURE:
Project_Folder/
├── Final_Report.docx
├── README.txt
├── Packet_Tracer_File/
    └── network_project.pkt

-----------------------------------------------------------
📶 NETWORK DEVICES USED:
- Cisco Router (1941)
- Cisco Switch (2960)
- PC0 and PC1
- Printer
- Access Point-PT (used for wireless SSID only)
- Wireless Laptop

-----------------------------------------------------------
🔧 STEP-BY-STEP INSTRUCTIONS:

1. Open `network_project.pkt` in Cisco Packet Tracer.

2. Verify all devices are placed as per the star topology.

3. Configure the Router:
   - CLI commands to set IP: 192.168.1.1/24 on GigabitEthernet0/0
   - `no shutdown` to bring up the interface.

4. Assign IP Addresses:
   - PC0: 192.168.1.2
   - PC1: 192.168.1.3
   - Printer: 192.168.1.4
   - Laptop: 192.168.1.5 (manual IP via WiFi)
   - Subnet Mask: 255.255.255.0
   - Default Gateway: 192.168.1.1

5. Configure Wireless:
   - Use Access Point or Wireless Router to set SSID: "Home_WiFi"
   - Use WPA2-PSK with Passphrase: "StrongPass123"
   - Laptop connects wirelessly via Desktop > PC Wireless

6. Perform Ping Tests:
   - From PC0 to PC1, Printer, Laptop, Router
   - From Laptop to Router

7. Save screenshots at each step for documentation.

-----------------------------------------------------------
✅ TROUBLESHOOTING:
- If ping fails, check:
   - Interface status (`no shutdown` on router)
   - IP addresses and gateway configs
   - WiFi settings (SSID & password)

-----------------------------------------------------------
📧 AUTHOR:
Ayush Kumar Sharma  
C.V. Raman Global University, Bhubaneswar  
Course: BCA (2023–2026)

-----------------------------------------------------------
📘 NOTE:
This project is part of the Smart ED LMS learning program and demonstrates practical implementation of a small office/home network with documentation and simulation.
