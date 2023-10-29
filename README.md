<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to Deploy on-premises Active Directory within Azure Compute](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1: Set up the domain controller(DC-1) and Client-1(Virtual Machine) in Azure.
- Step 2: Set up Active Directory on DC-1
- Step 3: Join Client-1 to DC-1 by changing DNS server.
- Step 4: How to use a powershell script in order to create other employee user names that are connected to client-1 and DC-1

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Use your Azure account and make a resource group. Next create a virtual machine with windows servers 2022 datacenter: Azure Edition, make sure it has 2vcpus. Name the virtual machine DC-1(Domain Controller 1). After it has been created change the NIC private IP Address to static by going to the network,click the NIC name, Click IP-Configurations,lastly click IP Address and change to static.Lastly create another virtual machine as a regular operating system and call it client 1. When creating client 1 put it in the same resource group as DC-1 and use Windows 10 as the operating system, the size of the operating system should be 2 vcpus. Next, put Client-1 in the same virtual network as DC-1. Login to Client-1 and DC-1 on separate Remote Desktop Connection programs using their unique public IP Addresses. Now you're logged in to both DC-1 and Client-1.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
dsfdggh
