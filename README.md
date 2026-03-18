# 🖥️ Active Directory Home Lab

A hands-on home lab simulating an enterprise IT environment using **Oracle VirtualBox**, **Windows Server 2022**, and **Windows 11**. This project documents the step-by-step process of building a domain environment from scratch.

This lab will consist of a **Windows Server 2022 Domain Controller** and a **Windows 11 client machine** joined to the domain.

---

## 🎯 Objective

Build and document an enterprise-style Active Directory environment to develop practical skills in:

- Domain administration  
- User provisioning  
- Virtualization  
- PowerShell automation  

These skills are directly applicable to **SOC Analyst** and **IT Administrator** roles.

---

## 🧰 Tools & Technologies

| Tool | Purpose |
|------|--------|
| Oracle VirtualBox 7.2.6 | Hypervisor / virtualization platform |
| Windows Server 2022 | Domain Controller OS (in progress) |
| Windows 11 (x64) | Client machine |
| Active Directory Domain Services (AD DS) | Directory and identity management |
| PowerShell | Automation (planned) |

---

## 📊 Lab Progress

- [x] VirtualBox installed and configured  
- [x] Windows 11 client VM created  
- [x] Windows 11 installation completed  
- [ ] Windows Server 2022 VM setup (in progress)  
- [ ] Active Directory Domain Services installed  
- [ ] Domain created and configured  
- [ ] Client joined to domain  
- [ ] Users created via PowerShell  

---

## 💻 Client Machine Setup (Windows 11)

### Step 1 — Download Oracle VirtualBox
Downloaded **VirtualBox 7.2.6** from the official VirtualBox website.

![Step 1](https://github.com/HusseinCyberSec/Active-Directory-Home-Lab/blob/35fdfb2e38cc74c5980233d338934c62c00f2987/Lab_Pictures/lab%201.PNG)

---

### Step 2 — Download Windows 11 ISO
Downloaded the **Windows 11 (x64) ISO** from Microsoft’s official website.

![Step 2](https://github.com/HusseinCyberSec/Active-Directory-Home-Lab/blob/35fdfb2e38cc74c5980233d338934c62c00f2987/Lab_Pictures/lab%202.PNG)

---

### Step 3 — Create Windows 11 Client Virtual Machine
Created a new virtual machine named **admin**, attached the Windows 11 ISO, and selected the appropriate OS version.

![Step 3](https://github.com/HusseinCyberSec/Active-Directory-Home-Lab/blob/35fdfb2e38cc74c5980233d338934c62c00f2987/Lab_Pictures/lab%203.PNG)

---

### Step 4 — Configure User Credentials
During installation, created a local user account by defining a username and secure password.

![Step 4](https://github.com/HusseinCyberSec/Active-Directory-Home-Lab/blob/35fdfb2e38cc74c5980233d338934c62c00f2987/Lab_Pictures/lab%204.PNG)

---

### Step 5 — Windows 11 Installation Complete ✅
Windows 11 installation completed successfully and the virtual machine is fully operational.

![Step 5](https://github.com/HusseinCyberSec/Active-Directory-Home-Lab/blob/35fdfb2e38cc74c5980233d338934c62c00f2987/Lab_Pictures/lab%205.PNG)

---

## 🖥️ Domain Controller Setup (Windows Server 2022)

*(Currently in progress — setup steps will be documented next)*

Planned steps:

- Create Windows Server 2022 VM  
- Install Windows Server 2022  
- Configure Administrator account  
- Install Active Directory Domain Services (AD DS)  
- Promote to Domain Controller  

---

## 🔜 Coming Next

- Complete Windows Server 2022 installation  
- Install **Active Directory Domain Services (AD DS)**  
- Promote server to **Domain Controller**  
- Configure **DNS and DHCP**  
- Join Windows 11 client to the domain  
- Automate bulk user creation with **PowerShell**  

---

## 🚀 Key Skills Demonstrated

- Virtualization using Oracle VirtualBox  
- Windows 11 system deployment  
- System configuration and setup  
- Understanding of client/server architecture  
- Enterprise lab environment design  

---
