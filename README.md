<h1>Active Directory Home Lab</h1>

<h2>Description</h2>
This project demonstrates my ability to set up and manage an Active Directory (AD) environment using virtual machines. The lab consists of:<br/>

<br>-Domain Controller (DC): Configured a VM to act as the primary DC, including installing and managing Active Directory Domain Services (AD DS).<br/>
-Employee Computer: Created a second VM to simulate a client workstation within the domain.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell:For managing and scripting tasks within the Active Directory environment.</b> 
- <b>Windows Server: For configuring and managing the Domain Controller (DC).</b>
- <b>Active Directory Domain Services (AD DS): Core service used to manage users, computers, and policies in the domain.</b>
- <b>VirtualBox: For creating and running virtual machines (VMs).</b>
- <b>Windows 10: Used as the client operating system for the employee computer.</b>

<h2>Environments Used </h2>

- <b>Windows 10</b>
- <b>Windows Server 2019: Installed on the Domain Controller VM.</b>
- <b>Local Network: Simulated network connection between the VMs for domain communication.</b>
- <b>Active Directory Lab: Configured as a controlled environment to test domain functionalities.</b>

<h2>Program walk-through:</h2>

<p align="center">
Create DC VM: <br/>
<img src="https://i.imgur.com/dZBwp14.png" height="80%" width="80%" alt="Create DC VM"/>
<br />
<br />
Install Active Directory Domain Services:  <br/>
<img src="https://i.imgur.com/9SIIf4U.png" height="80%" width="80%" alt="Active Directory"/>
<br />
<br />
Create Admin OU and User: <br/>
<img src="https://i.imgur.com/u08AzMt.png" height="80%" width="80%" alt="Active Directory"/>
<br />
<br />
Configure NAT:  <br/>
<img src="https://i.imgur.com/rXPoboq.png" height="80%" width="80%" alt="Active Directory"/>
<br />
<br />
Configure DHCP scope:  <br/>
<img src="https://i.imgur.com/pE6TpLM.png" height="80%" width="80%" alt="Active Directory"/>
<br />
<br />
Creating and Managing Domain Resources (I utilized a script to create a majority of users):  <br/>
<img src="https://i.imgur.com/OnrnYnI.png" height="80%" width="80%" alt="Active Directory"/>
<br />
<br />
Verify Funcionality from User VM:  <br/>
<img src="https://i.imgur.com/qvubmUN.png" height="80%" width="80%" alt="Active Directory"/>
<br />
<br />
Verify DHCP lease from User PC on DC:  <br/>
<img src="https://i.imgur.com/zkbJWyz.png" height="80%" width="80%" alt="Active Directory"/>
</p>


