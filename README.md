# 🖥️ Active Directory Home Lab

A hands-on home lab simulating an enterprise IT environment using **Oracle VirtualBox**, **Windows Server 2022**, and **Windows 11**. This project documents the full process of building an Active Directory domain from scratch, including server configuration, domain controller promotion, and client setup.

This lab consists of a **Windows Server 2022 Domain Controller** and a **Windows 11 client machine** joined to the domain.

---

## 🎯 Objective

Build and document an enterprise-style Active Directory environment to develop practical skills in:

- Domain administration  
- User provisioning  
- Network configuration  
- PowerShell automation  

These skills are directly applicable to **SOC Analyst** and **IT Administrator** roles.

---

## 🧰 Tools & Technologies

| Tool | Purpose |
|------|--------|
| Oracle VirtualBox 7.2.6 | Hypervisor / virtualization platform |
| Windows Server 2022 | Domain Controller OS |
| Windows 11 (x64) | Client machine |
| Active Directory Domain Services (AD DS) | Directory and identity management |
| PowerShell | Automation |

---

## 📊 Lab Progress

- [x] VirtualBox installed and configured  
- [x] Windows 11 client VM created  
- [x] Windows Server 2022 VM created  
- [x] Static IP configured on server  
- [x] Active Directory Domain Services installed  
- [x] Server promoted to Domain Controller  
- [x] Domain successfully configured  
- [x] Client joined to domain  
 

---

## 💻 Client Machine Setup (Windows 11)

### Step 1 — Download Oracle VirtualBox
![Step 1](https://github.com/HusseinCyberSec/Active-Directory-Home-Lab/blob/35fdfb2e38cc74c5980233d338934c62c00f2987/Lab_Pictures/lab%201.PNG)

---

### Step 2 — Download Windows 11 ISO
![Step 2](https://github.com/HusseinCyberSec/Active-Directory-Home-Lab/blob/35fdfb2e38cc74c5980233d338934c62c00f2987/Lab_Pictures/lab%202.PNG)

---

### Step 3 — Create Windows 11 Client Virtual Machine
![Step 3](https://github.com/HusseinCyberSec/Active-Directory-Home-Lab/blob/35fdfb2e38cc74c5980233d338934c62c00f2987/Lab_Pictures/lab%203.PNG)

---

### Step 4 — Configure User Credentials
![Step 4](https://github.com/HusseinCyberSec/Active-Directory-Home-Lab/blob/35fdfb2e38cc74c5980233d338934c62c00f2987/Lab_Pictures/lab%204.PNG)

---

### Step 5 — Windows 11 Installation Complete ✅
![Step 5](https://github.com/HusseinCyberSec/Active-Directory-Home-Lab/blob/35fdfb2e38cc74c5980233d338934c62c00f2987/Lab_Pictures/lab%205.PNG)

---

## 🖥️ Domain Controller Setup (Windows Server 2022)

### Step 6 — Download Windows Server 2022
![Step 6](https://github.com/HusseinCyberSec/Active-Directory-Home-Lab/blob/main/Lab_Pictures/lab%206.PNG)

---

### Step 7 — Create Server VM & Attach ISO
![Step 7](https://github.com/HusseinCyberSec/Active-Directory-Home-Lab/blob/main/Lab_Pictures/lab%207.PNG)

---

### Step 8 — Windows Server Installation Complete
![Step 8](https://github.com/HusseinCyberSec/Active-Directory-Home-Lab/blob/main/Lab_Pictures/lab%208.PNG)

---

### Step 9 — Configure Static IP Address
Configured a static IP address for the server using Command Prompt to ensure stable domain services.

![Step 9](https://github.com/HusseinCyberSec/Active-Directory-Home-Lab/blob/main/Lab_Pictures/lab%209.PNG)

---

### Step 10 — Install Active Directory Domain Services
Installed the **AD DS role** via Server Manager.

![Step 10](https://github.com/HusseinCyberSec/Active-Directory-Home-Lab/blob/main/Lab_Pictures/lab%2010.PNG)

---

### Step 11 — Promote Server to Domain Controller
Promoted the server to a Domain Controller and created a new domain.

![Step 11](https://github.com/HusseinCyberSec/Active-Directory-Home-Lab/blob/main/Lab_Pictures/lab%2011.PNG)

---

### Step 12 — Domain Controller Setup Complete 
Successfully logged into the domain controller after full configuration.

![Step 12](https://github.com/HusseinCyberSec/Active-Directory-Home-Lab/blob/1ddec2ace37bda602f18d20d418546080908f8b8/Lab_Pictures/lab%2012.PNG)

### Step 13 — Domain Controller Setup Complete 
Join client to domain. Configured DNS to point to domain controller, join windows 11 machine to LAB.local. Verified successful domain login 
![Step 13](https://github.com/HusseinCyberSec/Active-Directory-Home-Lab/blob/main/Lab_Pictures/lab%2015.PNG)

### Step 14 — Domain Controller Setup Complete 
Create domain users and Groups 
![Step 13](https://github.com/HusseinCyberSec/Active-Directory-Home-Lab/blob/main/Lab_Pictures/lab%2013.PNG)
![Step 13](https://github.com/HusseinCyberSec/Active-Directory-Home-Lab/blob/main/Lab_Pictures/lab%2014.PNG)
## 🚀 Key Skills Demonstrated

- Active Directory Domain Services (AD DS) deployment  
- Domain Controller configuration (Windows Server 2022)  
- Static IP and network configuration  
- Virtualization using Oracle VirtualBox  
- Windows 11 & Server environment setup  
- Enterprise infrastructure simulation  

📌 Project Outcome

This lab simulates a real-world enterprise environment where a domain controller centrally manages users, groups, and client machines. It demonstrates foundational IT and security skills used in help desk, system administration, and SOC roles.
