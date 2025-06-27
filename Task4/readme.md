## 🔐 Task 4: Configure and Test Firewall Rules on Windows 7 VM

### 🧾 Overview
Here,I configured and tested basic firewall rules using **Windows Firewall with Advanced Security** on a **Windows 7 Virtual machine**. The goal was to allow or block traffic by creating custom inbound rules and verifying their effects using Telnet.

### 🧰 Tools Used
- Windows 7 VM (on VirtualBox)
- Windows Firewall
- Telnet Client (for traffic testing)
- VirtualBox clipboard features for screenshot sharing

### 🧪 What I Did ?

#### ✅ Step 1: Enabled Windows Firewall Rules
- Opened **Windows Firewall with Advanced Security**
- Created a **New Inbound Rule** to **block TCP traffic on port 23 (Telnet)**

#### ✅ Step 2: Tested the Block
- Enabled **Telnet Client** via “Turn Windows features on or off”
- Ran the following in Command Prompt:

  ```bash
  telnet localhost 23
  ```
## Screenshots: (For Better Understanding in a Order)

Advance Settings in the Windows Firewall
![Screenshot](Advance settings.png)

