# 🖥️ Active Directory Home Lab

A hands-on home lab simulating an enterprise IT environment using **Oracle VirtualBox**, **Windows Server 2019**, and **Windows 11**. This project documents the full setup process—from virtual machine creation to building a domain environment with a server and client system.

This lab consists of a **Windows Server 2019 Domain Controller** and a **Windows 11 client machine** designed to be joined to the domain.

---

## 🎯 Objective

Build and document an enterprise-style Active Directory environment to develop practical skills in:

- Domain administration  
- User provisioning  
- Virtualization  
- PowerShell automation (upcoming)  

These skills are directly applicable to **SOC Analyst** and **IT Administrator** roles.

---

## 🧰 Tools & Technologies

| Tool | Purpose |
|------|--------|
| Oracle VirtualBox 7.2.6 | Hypervisor / virtualization platform |
| Windows 11 (x64) | Domain Controller OS |
| Active Directory Domain Services (AD DS) | Directory and identity management |
| PowerShell | Automation (in progress) |

---

## 📊 Lab Progress

- [x] VirtualBox installed and configured  
- [x] Windows Server 2019 VM created  
- [x] Windows 11 client VM created  
- [x] Windows 11 installation completed  
- [ ] Active Directory Domain Services installed  
- [ ] Domain created and configured  
- [ ] Client joined to domain  
- [ ] Users created via PowerShell  

---

## 🖥️ Domain Controller Setup (Windows Server 2019)

*(Initial setup completed — AD DS configuration coming next)*

- Created Domain Controller VM  
- Installed Windows Server 2019  
- Configured Administrator account  
- Verified system functionality  

---

## 💻 Client Machine Setup (Windows 11)

### Step 1 — Download Oracle VirtualBox
Downloaded **VirtualBox 7.2.6** from the official VirtualBox website.

![Step 1](lab%201.PNG)

---

### Step 2 — Download Windows 11 ISO
Downloaded the **Windows 11 (x64) ISO** from Microsoft’s official website.

![Step 2](lab%202.PNG)

---

### Step 3 — Create Windows 11 Client Virtual Machine
Created a new virtual machine named **admin**, attached the Windows 11 ISO, and selected the appropriate OS version.

![Step 3](lab%203.PNG)

---

### Step 4 — Configure User Credentials
During installation, created a local user account by defining a username and secure password.

![Step 4](lab%204.PNG)

---

### Step 5 — Windows 11 Installation Complete ✅
Windows 11 installation completed successfully and the virtual machine is fully operational.

![Step 5](lab%205.PNG)

---

## 🔜 Coming Next

- Install **Active Directory Domain Services (AD DS)**  
- Promote server to **Domain Controller**  
- Configure **DNS and DHCP**  
- Create **Organizational Units (OUs)**  
- Join Windows 11 client to the domain  
- Automate bulk user creation with **PowerShell**  

---

## 🚀 Key Skills Demonstrated

- Virtualization using Oracle VirtualBox  
- Windows Server & Windows 11 deployment  
- System configuration and setup  
- Client/server architecture understanding  
- Enterprise environment simulation  

---
