<h1>Active Directory Home Lab </h1>

 ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)

<h2>Description</h2>
In this project, I am going to create an Active Directory homelab Environment using Oracle Virtual Box. Configuring and running this lab 
will help my understanding og how active directory and windows networking works. 

This lab project involves building a fully functional Windows Active Directory environment using Oracle VirtualBox. The goal is to simulate a small corporate network, complete with a domain controller, internal network, DHCP, DNS, NAT routing, and a Windows 10 domain‑joined client. By completing this lab, you gain hands‑on experience with Windows Server administration, networking fundamentals, and automation using PowerShell.

The project begins by installing VirtualBox and creating two virtual machines: a Windows Server 2019 domain controller and a Windows 10 client. The domain controller is configured with dual network adapters—one for external internet access and one for an isolated internal network. Server 2019 is then configured with a static IP, Active Directory Domain Services, DNS, DHCP, and Routing/NAT to allow internal clients to reach the internet.

A PowerShell automation script is used to generate over 1,000 Active Directory user accounts, demonstrating how scripting can streamline administrative tasks. Finally, a Windows 10 VM is installed, connected to the internal network, receives its IP configuration from DHCP, and is joined to the new domain. Logging in with one of the generated domain accounts validates the full environment.

This lab provides practical experience with:

Virtualization and VM networking

Active Directory setup and domain creation

DNS, DHCP, and NAT configuration

PowerShell automation for user provisioning

Domain‑joining and client management

It mirrors the foundational structure of real enterprise Windows networks and builds the core skills needed for system administration, IT support, and cybersecurity roles.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Diskpart</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Launch the utility: <br/>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select the disk:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
