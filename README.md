<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Microsoft Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> 

<h2>Configure the Following:</h2>

- Roles
- Departments
- Users
- SLA
- Help Topics

<h2>Configuration Guideline</h2>

<p align="center">
<img src="https://i.imgur.com/OVVVtdx.png" height="50%" width="50%" alt="LogIn"/>
</p>
<p align="center"> Log into http://localhost/osTicket/scp/login.php with credentials established in the Pre-Configuration phase. 
</p>
<br />

<p align="center">
<img src="https://i.imgur.com/xlq2lO0.png" height="50%" width="50%" alt="Roles"/>
</p>
<p> In the Agent Panel, select Roles. Click Add New Role. In the Definition section, type "Supreme Admin". In the Permissions, select all options, then click Add Role. 
</p>
<br />

<p align="center">
<img src="https://i.imgur.com/OFIRJ57.png" height="50%" width="50%" alt="Departments"/>
</p>
<p align="center"> In the Agent Panel, select Departments. Click Add New Department. Name it "System Administrators" and click Create. 
</p>
<br />

<p align="center">
<img src="https://i.imgur.com/VlCGbFA.png" height="50%" width="50%" alt="Teams"/>
</p>
<p align="center"> In the Agent Panel, select Teams. Click Add Team. Add "Level II Support." Click Create. 
</p>
<br />

<p align="center">
<img src="https://i.imgur.com/XklQWRU.png" height="50%" width="50%" alt="User Access"/>
</p>
<p align="center"> In the Agent Panel, select Settings, then Users. Check the box for Require registration and login to create tickets. Save.
</p>
<br />

<p align="center">
<img src="https://i.imgur.com/SZoYNFe.png" height="50%" width="50%" alt=""/>
</p>
<p> In the Agent Panel, select the Agent tab. Click on Add New Agent. In the Account tab, add Agent's name, e-mail, and user name. (Jane Doe, jane_admin@helper.com, jane_admin.) Unselect the Send the agent a password reset email, and Unselect Require password change at next login. Add password. In the Status and Settings section, check Administrator. 
</p>
<br />

<p align="center">
<img src="https://i.imgur.com/FyuVTK9.png" height="50%" width="50%" alt="Access Tab"/>
</p>
<p align="center"> In the Access tab, select Primary Department as System Administrators. Select role as Supreme Admin. 
</p>
<br />

<p align="center">
<img src="https://i.imgur.com/FUu6qCV.png" height="50%" width="50%" alt="Permissions Tab"/>
</p>
<p> In the Permission tab, go through each of the multiple tabs and select all options. (Jane Doe is an administrator.) For other agent's select options accordingly.  
</p>
<br />

<p align="center">
<img src="https://i.imgur.com/AWyWwMi.png" height="50%" width="50%" alt="Teams Tab"/>
</p>
<p align="center"> In the Teams Tab, select a team such as Level I or add teams. Add Level II Support. Click create. 
</p>
<br />

<p align="center">
<img src="https://i.imgur.com/Dk9c1Zt.png" height="50%" width="50%" alt="John Doe"/>
</p>
<p align="center"> Following the previous methods, create an administrator named John Doe. 
</p>
<br />

<p align="center">
<img src="https://i.imgur.com/b3CmDL6.png" height="50%" width="50%" alt="User Karen"/>
</p>
<p align="center"> Log into the osTicket as jane_admin. In the Admin Panel, select Users and Add New User (Karen Hart; karen@clueless.com). Click Add.  
</p>
<br />

<p align="center">
<img src="https://i.imgur.com/lujmJO3.png" height="50%" width="50%" alt="Register"/>
</p>
<p align="center"> While in the newly created user for Karen Hart, select Register. Select the option to add a password. 
</p>
<br />

<p align="center">
<img src="https://i.imgur.com/MpEhmiQ.png" height="50%" width="50%" alt="Ken Jeong"/>
</p>
<p align="center"> Repeating the previous steps, create a new user. (Ken Jeong; kenjeong@lovemyself.com)
</p>
<br />

<p align="center">
<img src="https://i.imgur.com/gxyucy9.png" height="50%" width="50%" alt="SLA"/>
</p>
<p> In the Agent Panel, select Manage, then Service Level Agreements (SLA). Click Add New SLA Plan. Add the following SLA Plans: SEV-A with a 1 hour grace period with a 24/7 schedule. SEV-B with a 4 hour grace period with a 24/7 schedule. SEV-C with a 8 hour grace period with a Monday-Friday 8 am - 5 pm with US Holidays. 
</p>
<br />

<p align="center">
<img src="https://i.imgur.com/4mZxej0.png" height="50%" width="50%" alt="Help Topics"/>
</p>
<p> In the Agent Panel, go to Manage, then to Help Topics. Add the following Help Topics: Business Critical Outage, Personal Computer Issues, Equipment Request, and Password Reset. It is optional to set the Department, SLA, and Priority. These options will be left in the default for this tutorial.  
</p>
<br />

<p align="center">
<img src="https://i.imgur.com/ubUCd3K.png" height="50%" width="50%" alt="Conclude"/>
</p>
<p> This concludes this tutorial. The next one will be on this with the ticket lifecycle. 
</p>
<br />
