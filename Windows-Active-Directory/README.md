# Windows Active Directory

## 📌 Overview
[Write a 2–3 sentence summary of what the project is about, why you did it, and what skills it demonstrates.]

---

## 🛠️ Lab Setup
- Tools/Software Used: Windows Server 2022, Proxmox, and Server Manager
- Environment: 1 VM acting as the Domain Controller

---

## 🔎 Objectives
- To configure a AD Domain so I can connect my other Windows VM's for easier management.
- To practive working in a Windows Server environment
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
- **Issue:** [Describe a problem you ran into, e.g., client could not join domain]  
- **Diagnosis:** [How you investigated, e.g., checked DNS settings, reviewed event logs]  
- **Solution:** [What you did to fix it, e.g., corrected DNS forwarder]  



---

## ✅ Key Takeaways
- [What did you learn from this project?]
- [How does this skill connect to IT support tasks?]
- [Anything you’d do differently next time?]

---
