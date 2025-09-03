# Windows Active Directory

## 📌 Overview
Built and Configured a Windows Active Directory domain on Windows Server 2022 to improve centralized management and DNS configuration in my homelab. This project sharpened my skills in setting up core services like AD DS and DNS, and prepared me for real-world IT support tasks involving user and network administration.

---

## 🛠️ Lab Setup
- Tools/Software Used: Windows Server 2022, Powershell, Proxmox, DNS Manager, and Server Manager
- Environment: 1 VM acting as the Domain Controller on Windows Server 2022

---

## 🔎 Objectives
- To configure a AD Domain so I can connect my other Windows VM's for improved management.
- To practice working in a Windows Server environment
- To simulate an business environment to practice troubleshooting user support tickets.

---

## ⚙️ Steps & Implementation
**Step 1:** Install AD DS and DNS Roles 
![Install AD DS and DNS Roles](./screenshots/1-Install-AD-DS-DNS-Roles.png)

**Step 2:** Configure DNS for for AD DS

**Step 2.1:** Create a Foward Lookup Zone
![Create Foward Lookup Zone](./screenshots/2.1-Create-Forward-Lookup-Zone.png)

**Step 2.2:** Create a Reverse Lookup Zone
![Create Reverse Lookup Zone](./screenshots/2.2-Create-Reverse-Lookup-Zone.png)

**Step 2.3:** Configure Fowarder
![Configure Forwarder](./screenshots/2.3-Configure-Fowarders.png)

**Step 2.4:** Configure DNS Interfaces
![Configure DNS Interfaces](./screenshots/2.4-Configure-DNS-Interfaces.png)

**Step 2.5:** Create the Server's Host A Record
![Create Server's Host A Record](./screenshots/2.5-Create-the-Server's-Host-A-Record.png)

**Step 2.6:** Configure Name Servers
![Configure Name Servers](./screenshots/2.6-Configure-the-Server's-DNS-Address.png)

**Step 2.7.1:** Configure Name Server Forward Lookup Zone
![Configure Name Server Forward Lookup Zone](./screenshots/2.7.1-Configure-Name-Server-Forward-Lookup-Zone.png)

**Step 2.7.2:** Configure Name Server Reverse Lookup Zone
![Configure Name Server Reverse Lookup Zone](./screenshots/2.7.2-Configure-Name-Server-Reverse-Lookup-Zone.png)

**Step 3:** Create Active Directory Domain
![Create Active Directory Domain](./screenshots/3-Create-Active-Directory-Domain.png)

**Step 4:** Reconfigure the DNS Forward Zone
![Reconfigure the DNS Forward Zone](./screenshots/4.1-Reconfigure-the-Forward-DNS-Zone.png)

**Step 4.1:** Reconfigure the DNS Reverse Zone
![Reconfigure the DNS Reverse Zone](./screenshots/4.2-Reconfigure-the-Reverse-DNS-Zone.png)

**Step 5:** Disable IPv6 on the net adapter
![Disable IPv6 on the net adapter](./screenshots/5-Disable-IPv6-on-the-Net-Adapter.png)

**Step 6:** Add the Domain to the DNS Zone
![Add the Domain to the DNS Zone](./screenshots/6-Add-the-Domain-to-the-DNS-Zone.png)


---

## 🐞 Troubleshooting & Issues
- **Issue:** The command to install the Active Directory Domain Service and DNS Roles was not recognized and would not execute. "Install-WindowsFeature -Name AD-Domain-Services, DNS -IncludeManagementTools"
- **Diagnosis:** I researched and confirmed that the command is correct and should work to install these services.
- **Solution:** I executed the command to install AD DS with management tools first, then installed the DNS with management tools.



---

## ✅ Key Takeaways
- Gained hands-on experience setting up a Windows Server as a Domain Controller
- Strengthened skills in documentation by recording setup steps, screenshots, and solutions.
- Built a realistic IT Lab environment that mirrors enterprise support tasks, preparing me for an entry level IT role.

---
