<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />


<h2>Video Demonstration</h2>


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (22H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1
- Step 2
- Step 3
- Step 4

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/uiNQC5A.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/LV1Keq6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
"The images above show the resource group that was created along with the virtual network (VNET). The VNet was established using Windows Server 2202 Datacenter. This VNet also host the Domain Controller."
</p>
<br />

<p>
<img src="https://i.imgur.com/xn0A7Vj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
"This image above shows the virtual machine that was created with Windows 10." 
</p>
<br />
<p>
<img src="https://i.imgur.com/CLL6oZ4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/ml2oj5F.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
"The above image shows the Domain Controller's private IP address being changed from dynamic to static. A static  IP address means it won't change over time. You can change this by navigating to the network settings on the Domain controller, then to the network interface's IP configuration. Select Ipconfig1, scroll to the private address setting, and change the configuration from  dynamic to static."
</p>
<br />

<img src="https://i.imgur.com/TZlSO4M.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>
<p>

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.

</p>
<br />


<img src="https://i.imgur.com/Fj3o9id.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

<img src="https://i.imgur.com/9xVQjAL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

"The image above shows PowerShell opened on the Windows 10 virtual machine via Remote Desktop, using the public IP address privided Mircosoft Azure. To launch PowerShell, I navigated to the start menu, selected Windows PowerShell and chose Run as Administrator".

</p>
<br />

<img src="https://i.imgur.com/58Z7YC4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/SfHYEyA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/LZZLkfp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
"The images above display Server Manager on the Domain Controller, accessed via Remote Desktop using the public IP address provided by Mircosoft Azure. Server Manager is utilized to install the neccessary features to fully configure Domain Controller."
</p>
<br />

<img src="https://i.imgur.com/8RFy2jH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>
<p>
"The above display me logging to the Domain Controller after it has been fully configured."

</p>
<br />

<img src="https://i.imgur.com/8M7qDTx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/9UFXBVU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
"The images above display the creation of an employee name Jane. To create Jane's account, I navigated to the Start menu, opened Active Directory Users and Computer, expanded mydomain.com; right-clicked the appropriate Organizational Unit(OU), and select New and  User."
</p>
<br />

<img src="https://i.imgur.com/YjDmlWW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
"The image above displays a Powershell script being executed to list users accounts."
</p>
<br />

<img src="https://i.imgur.com/ndocI8u.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
"The image above display of one of the Users logging in."
</p>
<br />
<img src="https://i.imgur.com/LV1Keq6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laborisnisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
