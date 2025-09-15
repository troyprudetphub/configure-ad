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
- Windows 10

<h2>Configuration Steps</h2>

- Create A Domain Controller virtual machine using Windows Server 2022
- Change private ip address from dynamic to a static ip address
- Create a Client virtual machine using Windows
- Use the private ip address from the Windows server as the dns server for the Client virtual machine

  <h2>Deployment and Configuration Steps</h2>

<p>
<img width="584" height="631" alt="Screenshot 2025-09-04 230546" src="https://github.com/user-attachments/assets/abef31d7-9b5e-49ec-9dc7-a412c7f4509b" />
</p>
<br />

<p>
<img width="1031" height="293" alt="Screenshot 2025-09-04 231740" src="https://github.com/user-attachments/assets/e3038348-5e49-461d-b3e8-c28106e26b36" />
</p>
<br />

<p>
<img width="576" height="376" alt="Screenshot 2025-09-04 232522" src="https://github.com/user-attachments/assets/2cbe94a4-a686-462f-818b-7b43c8c9780e" />
</p>
<p>
Using powershell I ran the command "ipconfig /all" to confirm if the ip address for the DNS server was the same as the Windows server.



