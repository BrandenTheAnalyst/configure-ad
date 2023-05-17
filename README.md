<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Create Resourse Group on Azure 
- Create Azure virtual machine with Domain Controller with Active Directory installed
- Create another Azure virtual running Windows 10 Pro
- Connect Windows 10 VM to Domain Controller w/ Active Directory

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/imiMJWg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here in this picture a lot is going on clearly, this is a virtual machine that is running windows 10 as a user admin. The user admin in this lab, can add security groups, add/remove users to certain groups if needed and so on and so on. 
  
The Command Prompt is used to ping to the domain controller, which is used to host the Active Directory.
</p>
<br />

<p>
<img src="https://i.imgur.com/wc0pOxv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here in this above picture, I am in the Domain Controller which has Active Directory installed, and currently enabling ICMPv4 to allow ping one VM to another VM.
<br />


