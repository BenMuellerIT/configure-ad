<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to Deploy on-premises Active Directory within Azure Compute](https://youtu.be/uxMm9jbKn4o)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1 - Create 2 virtual machines in Microsoft Azure
- Step 2 - set up a few firewall rules
- Step 3 - set permissions and create organizational units for employees and admins on the server
- Step 4 - allow the employee's PC to be able to connect to the network
- Step 5 - run a script to create employees
- Step 6 - Create scenarios

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/9rJzkNU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I created 2 virtual machines in Microsoft Azure. One acts as a Server for users to connect to, and the other simulates an employee terminal. I then set up a few firewall rules. Then, set permissions and create organizational units for employees and admins on the server.
</p>
<br />

<p>
<img src="https://i.imgur.com/OGrmPsr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, we need to allow the employee's PC to be able to connect to the network that has been established.
</p>
<br />

<p>
<img src="https://i.imgur.com/oNwDupa.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 After all of the setup is done, I run a script to create employees. Using one of the created employees, I create scenarios like an expired password, being locked out from too many attempts, and a new employee set up.
</p>
<br />
