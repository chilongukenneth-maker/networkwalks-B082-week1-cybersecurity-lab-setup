# networkwalks-B082-week1-cybersecurity-lab-setup
cybersecurity lab setup

## 💻 Cybersecurity Lab Environment Setup

## Cybersecurity | Kali Linux | VirtualBox | Linux Networking | Penetration Testing | Ethical Hacking | Network Virtualization|
               networkwalks-B082-week1-Cybersecurity-lab-setup
              VirtualBox • Kali Linux • Virtual Networking • Linux Networking

## 🎯 Lab Purpose
The purpose of this lab is to build a controlled and isolated cybersecurity environment using Oracle VirtualBox and Kali Linux.
A dedicated virtual lab provides a safer environment for practicing cybersecurity concepts without directly experimenting on production systems or unauthorized networks.
The lab will be used as a foundation for practical learning in:
   - Networking
   - Linux
   - Cisco
   - Ethical Hacking
   - Security Labs
    - Python
    - Security Automation

## 🖥️ Lab Environment

| Components              |       Details         | 
|-------------------------|-----------------------|
| Host OS                 | windows 11 home       |
|-------------------------|-----------------------|
|   RAM                   |  12 GB                |
|-------------------------|-----------------------|
|   processor             |   intel core i5       |
|-------------------------|-----------------------|
| Host storage            |     1 TB              |
|-------------------------|-----------------------|
|virtualization platform  | oracle VB    7.2.14   |
|-------------------------|-----------------------|
|Guest OS                 | kali linux 2026.2     |
|-------------------------|-----------------------|
|  Network type           |  NAT Network          |
|-------------------------|-----------------------|
|  Network CIDR           |  10.0.0.0/24          |
|-------------------------|-----------------------|
| kali linux ip           |   10.0.0.2            |
|-------------------------|-----------------------|
|  Gateway                |   10.0.0.1            |
|-------------------------|-----------------------|
|  DNS                    |    8.8.8.8            |
|-------------------------|-----------------------|

## 🔗 Tools & Resources
             🔗7-Zip: https://7-zip.org/download.html
               🔗VirtualBox: https://virtualbox.org/wiki/Downloads
                 🔗Kali Linux: https://kali.org/get-kali


## 📝 Steps 1/6
   - 7-Zip
   - Oracle VirtualBox
   - Kali Linux
   - NAT Network
    - Linux Networking
   - IPv4
   - VirtualBox Snapshots

The Networkwalks Phase 1 workflow consists of six setup steps:
   1.Install 7-Zip
   2.Install Oracle VirtualBox
   3.Configure the VirtualBox NAT Network
   4.Download and import Kali Linux
   5.Configure Kali Linux IP settings
   6.Create a VM snapshot

## 🚀 Phase 01 — Lab Setup
         1️⃣ 7-Zip Installation
           What I Did
          Installed 7-Zip to extract and manage the virtual machine files required for the cybersecurity lab.
          Why
          The Kali Linux VM files need to be extracted and prepared before importing them into the virtualization environment.
          Result
          Status: ✅ Completed


<img width="485" height="369" alt="Screenshot 2026-08-13 165023" src="https://github.com/user-attachments/assets/37c3a6e9-9661-4ddc-b9fa-e1c0e8ad4186" />

## 2️⃣ Oracle VirtualBox Installation
        What I Did
        Installed and configured Oracle VirtualBox as the virtualization platform for the cybersecurity laboratory.
        Why
        VirtualBox provides the virtualized environment required to run Kali Linux as a separate virtual machine.
        Result
        Status: ✅ Completed
        
<img width="569" height="898" alt="Screenshot 2026-08-13 165136" src="https://github.com/user-attachments/assets/5b339421-8228-4ada-bfed-c7ca51b708be" />
<img width="1920" height="1080" alt="Screenshot 2026-08-14 075847" src="https://github.com/user-attachments/assets/b6cee68a-c6d6-41bd-b343-4a124df643f1" />

## 3️⃣ NAT Network Configuration
    What I Did
    Created a dedicated NAT Network in Oracle VirtualBox for the cybersecurity lab.
    Why
    The NAT Network provides a controlled virtual networking environment for the laboratory machines.

     Network Type : NAT Network
     Network CIDR : 10.0.0.0/24
    DHCP         : Enabled
    Status: ✅ Completed
<img width="520" height="332" alt="Screenshot 2026-08-13 165317" src="https://github.com/user-attachments/assets/27145016-c841-46c0-b2c2-2b2d2262b99e" />
<img width="1920" height="1080" alt="Screenshot 2026-08-14 080424" src="https://github.com/user-attachments/assets/e9ef6dd6-1fe0-497b-92a7-0d10c9882874" />

## 4️⃣ Kali Linux VM Setup
     What I Did
    Downloaded and imported the Kali Linux virtual machine into Oracle VirtualBox and connected the VM to the configured NatNetwork.
    Why
    Kali Linux is used as the primary cybersecurity operating environment for practical security learning, laboratory exercises, and authorized security testing.
    VM Configuration
    Operating System : Kali Linux Version : 2026.2 Virtualization : Oracle VirtualBox Network : NatNetwork
    Status: ✅ Completed
<img width="1920" height="1080" alt="Screenshot 2026-08-14 080829" src="https://github.com/user-attachments/assets/527b5915-51bd-4b72-b65b-f5d9f73c8abe" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/0c480042-7d93-428e-ba74-e28da0ebff6b" />
<img width="1280" height="800" alt="Screenshot_2026-08-14_08_11_33" src="https://github.com/user-attachments/assets/960691d3-b2d1-4e60-bacc-bb78eca6e611" />

## 5️⃣ Kali Linux Network Configuration
     What I Did
     Configured the Kali Linux network interface with the required IP address, subnet, gateway, and DNS settings.
     Why
     Proper IP configuration is required for Kali Linux to communicate with the configured NAT Network and access network resources.
     IP Address : 10.0.0.2/24
     Gateway    : 10.0.0.1
    DNS        : 8.8.8.8
    status: ✅ completed
## Commands Used
ifconfig
sudo ifconfig eth0 down
sudo ifconfig eth0 up
ping google.com
ping -c 4 8.8.8.8
<img width="1280" height="800" alt="Screenshot_2026-08-13_22_06_47" src="https://github.com/user-attachments/assets/0e82e89b-3a68-45f2-a3bc-eccb5c475bf2" /> 
<img width="1280" height="800" alt="Screenshot_2026-08-13_22_09_30" src="https://github.com/user-attachments/assets/22b86153-df8b-4b11-8787-69b2fc472d1e" />
<img width="1280" height="800" alt="Screenshot_2026-08-13_22_06_28" src="https://github.com/user-attachments/assets/f9aa8a16-d07a-4400-8078-1359718e6561" />

## 6️⃣ VirtualBox Snapshot
   What I Did
   Created a VirtualBox snapshot after completing the initial Kali Linux lab configuration.
   Why
   The snapshot provides a safe restore point before continuing with future cybersecurity labs and experiments.
  Snapshot Purpose : Lab Backup & Recovery
  Status: ✅ Completed
  <img width="1920" height="1080" alt="Screenshot 2026-08-14 091723" src="https://github.com/user-attachments/assets/da1f387c-3225-4d5c-9d68-f00ffc67d487" />

##  🏗️ Lab Architecture
##   Host Machine
 ##      │
  ##     ▼
##   Oracle VirtualBox
   ##    │
  ##     ▼
##   NAT Network
##   10.0.0.0/24
  ##     │
   ##    ▼
##  Kali Linux VM
##  10.0.0.2/24
  ##     │
  ##     ▼
#  Cybersecurity Labs

## 🧠 Key Learning
   During this phase, I gained practical experience with:
     - Virtual machine deployment
    - VirtualBox configuration
    - Kali Linux setup
    - IPv4 and subnet configuration
    - NAT networking
    - Linux network configuration
     - Routing and connectivity verification
     - VM snapshot and recovery

🔗 Tools & Resources
7-Zip: https://7-zip.org/download.html
VirtualBox: https://virtualbox.org/wiki/Downloads
Kali Linux: https://kali.org/get-kali
📝 Steps 1/6
7-Zip
Oracle VirtualBox
Kali Linux
NAT Network
Linux Networking
IPv4
VirtualBox Snapshots
🛡️Lab Setup
The Networkwalks Phase 1 workflow consists of six setup steps:

Install 7-Zip
Install Oracle VirtualBox
Configure the VirtualBox NAT Network
Download and import Kali Linux
Configure Kali Linux IP settings
Create a VM snapshot
🚀 Phase 01 — Lab Setup
1️⃣ 7-Zip Installation
What I Did
Installed 7-Zip to extract and manage the virtual machine files required for the cybersecurity lab.

Why
The Kali Linux VM files need to be extracted and prepared before importing them into the virtualization environment.

Result
Status: ✅ Completed

Screenshot 2026-08-10 183524 7zip-extract-archive
2️⃣ Oracle VirtualBox Installation
What I Did
Installed and configured Oracle VirtualBox as the virtualization platform for the cybersecurity laboratory.

Why
VirtualBox provides the virtualized environment required to run Kali Linux as a separate virtual machine.

Result
Status: ✅ Completed

Screenshot 2026-08-10 183701 Screenshot 2026-08-10 204554
3️⃣ NAT Network Configuration
What I Did
Created a dedicated NAT Network in Oracle VirtualBox for the cybersecurity lab.

Why
The NAT Network provides a controlled virtual networking environment for the laboratory machines.

Network Type : NAT Network
Network CIDR : 10.0.0.0/24
DHCP         : Enabled
Status: ✅ Completed

Screenshot 2026-08-10 145039
4️⃣ Kali Linux VM Setup
What I Did
Downloaded and imported the Kali Linux virtual machine into Oracle VirtualBox and connected the VM to the configured NatNetwork.

Why
Kali Linux is used as the primary cybersecurity operating environment for practical security learning, laboratory exercises, and authorized security testing.

VM Configuration
Operating System : Kali Linux Version : 2026.2 Virtualization : Oracle VirtualBox Network : NatNetwork

Status: ✅ Completed

Screenshot 2026-08-10 114321 notebook-kali-2024 1
5️⃣ Kali Linux Network Configuration
What I Did
Configured the Kali Linux network interface with the required IP address, subnet, gateway, and DNS settings.

Why
Proper IP configuration is required for Kali Linux to communicate with the configured NAT Network and access network resources.

IP Address : 10.0.0.2/24
Gateway    : 10.0.0.1
DNS        : 8.8.8.8
Screenshot_2026-08-10_02_34_59
Commands Used
ifconfig
sudo ifconfig eth0 down
sudo ifconfig eth0 up
ping google.com
Screenshot_2026-08-10_09_29_30 Screenshot_2026-08-10_05_32_37
Status: ✅ Completed

          6️⃣ VirtualBox Snapshot
        What I Did
          Created a VirtualBox snapshot after completing the initial Kali Linux lab configuration.
          Why
         The snapshot provides a safe restore point before continuing with future cybersecurity labs and experiments.
          Snapshot Purpose : Lab Backup & Recovery
          Status: ✅ Completed
         Screenshot 2026-08-10 152932 Screenshot 2026-08-10 153013


  ## 🏗️ Lab Architecture
    Host Machine
     │
     ▼
   Oracle VirtualBox
     │
     ▼
  NAT Network
  10.0.0.0/24
     │
     ▼
  Kali Linux VM
  10.0.0.2/24
     │
     ▼
  Cybersecurity Labs

  
## 🧠 Key Learning
During this phase, I gained practical experience with:
 - Virtual machine deployment
 - VirtualBox configuration
 - Kali Linux setup
 - IPv4 and subnet configuration
 - NAT networking
 - Linux network configuration
 - Routing and connectivity verification
 - VM snapshot and recovery


## 🔐 Security & Ethics
This laboratory is intended for educational and authorized cybersecurity practice only.
Security testing should only be performed on systems, networks, applications, or devices that you own or have explicit permission to test.

## 👨‍🏫 Mentor
Waqas Karim (CCIE)
Thank you for  your  technical guidance and practical learning opportunity throughout this week1 project.

## 📊 Phase 01 Progress
6 / 6 Steps Completed ✅
🔐 Learn • Practice • Build • Secure
Networkwalks Cybersecurity Internship — Week1_cybersecurity_lab_setup

    
















   
















