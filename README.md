🖥️ Active Directory Home Lab
A hands-on home lab simulating an enterprise IT environment using Oracle VirtualBox and Windows Server 2019. This project documents the full setup process from VM creation to a fully configured Active Directory domain — with user management via PowerShell coming next.

🎯 Objective
Build and document an enterprise-style Active Directory environment to practice domain administration, user provisioning, and PowerShell automation — skills directly applicable to SOC Analyst and IT Administrator roles.

🧰 Tools & Technologies
ToolPurposeOracle VirtualBox 7.2.6Hypervisor / virtualization platformWindows Server 2019 (Evaluation)Domain Controller OSWindows 10 22H2Client machine (coming soon)Active Directory Domain ServicesDirectory and identity managementPowerShellUser automation (in progress)


## Lab Progress
- [x] Windows Server installed on VirtualBox
- [x] Administrator account configured
- [ ] Active Directory Domain Services installed
- [ ] Domain created and configured
- [ ] Client VM joined to domain
- [ ] Users created via PowerShell

🗂️ Setup Walkthrough
Step 1 — Download Oracle VirtualBox
Downloaded VirtualBox 7.2.6 for Windows from the official VirtualBox website.
![Active Directory Lab](Lab%201.PNG)
Step 2 — Download Windows 10 ISO
Downloaded Windows 10 Version 22H2 from Microsoft's official download page to use as the client machine OS.
![Lab 2](lab%202.PNG)

Step 3 — Download Windows Server 2019 ISO
Downloaded the Windows Server 2019 Standard Evaluation ISO (64-bit) from the Microsoft Evaluation Center.
![Lab 3](lab%203.PNG)

Step 4 — Create the Domain Controller VM
Created a new VM in VirtualBox named "DC" (Domain Controller), set OS to Microsoft Windows.
![Lab 4](lab%204.PNG)

Step 5 — Configure VM Hardware
Allocated 2048MB RAM, 1 CPU, and 20GB disk for the Domain Controller VM.
![Lab 5](lab%205.PNG)

Step 6 — Configure Internal Network Adapter
Set Adapter 2 to Internal Network (intnet) so the DC can communicate with client VMs on an isolated network.
![Lab 7](lab%207.PNG)

Step 7 — Install Windows Server 2019
Mounted the ISO and ran the Windows Server 2019 installation inside VirtualBox.
![Lab 9](lab%209.PNG)

Step 8 — Configure Administrator Account
Set up the built-in Administrator account with a secure password during the post-install setup.
![Lab 10](lab%2010.PNG)

Step 9 — Windows Server 2019 Live ✅
Windows Server 2019 Standard Evaluation is fully installed and running in VirtualBox.
![Lab 11](lab%2011.PNG)

🔜 Coming Next

Install AD DS role and promote to Domain Controller
Configure DNS and DHCP
Create Organizational Units (OUs)
Automate bulk user creation with PowerShell
Join a Windows 10 client to the domain
