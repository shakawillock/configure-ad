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

- Create Domain Controller VM and Client VM in Azure
- Use the same resource group for both VMs
- Ensure both VMs are in the same VNet
- Ensure connectivity between Client VM and Domain Controller VM
- Install Active Directory
- Create an Admin and Normal User account in Active Directory
- Join Client VM to your domain
- Setup Remote Desktop for non-admin users on Client VM
- Create additional users and attempt to login to Client VM with one of the users

<h2>Deployment and Configuration Steps</h2>

<p>1. Create Domain Controller VM and Client VM in Azure </p>
<p>
<img src="https://i.imgur.com/Wdi9GyY.png" height="80%" width="80%" alt="Creating VMs"/>
</p>
<br />

<p>2. Use the same resource group for both VMs</p>

<p>3. Ensure both VMs are in the same VNet</p>

<p>4. Install Active Directory</p>
<p>
<img src="https://i.imgur.com/LRulSdz.png" height="80%" width="80%" alt="Installing Active Directory"/>
</p>
<br />

<p>5. Create an Admin and Normal User Account in Active Directory</p>
<p>
<img src="https://i.imgur.com/gAzJq0V.png" height="80%" width="80%" alt="Creating Admin and User Account"/>
</p>
<br />

<p>6. Join Client VM to your domain</p>
<p>
<img src="https://i.imgur.com/D0VLurh.png" height="80%" width=80%" alt="Joining Client VM"/>
</p>
<br />

<p>7. Setup Remote Desktop for non-admin users on Client VM</p>

<p>8. Create additional users and attempt to login to Client VM with one of the users</p>
<p>
<img src="https://i.imgur.com/WMuGCFp.png" height="80%" width=80%" alt="User Joining Client VM"/>
</p>
