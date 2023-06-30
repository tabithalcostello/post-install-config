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

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Confiure Departments
- Configure Users
- Configure SLA

<h2>Configuration Steps</h2>

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
<p> In the Agent Panel, select Departments. Click Add New Department. Name it "System Administrators" and click create. 
</p>
<br />

<p align="center">
<img src="" height="50%" width="50%" alt=""/>
</p>
<p>
Description
</p>
<br />

<p align="center">
<img src="" height="50%" width="50%" alt=""/>
</p>
<p>
Description
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
<p> In the Access tab, select Primary Department and type of Access the agent is permitted. 
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
<p> In the Teams Tab, select a team such as Level I or add teams. Add Level II Support. Click create. 
</p>
<br />

<p align="center">
<img src="" height="50%" width="50%" alt=""/>
</p>
<p>
Description
</p>
<br />

<p align="center">
<img src="" height="50%" width="50%" alt=""/>
</p>
<p>
Description
</p>
<br />

<p align="center">
<img src="" height="50%" width="50%" alt=""/>
</p>
<p>
Description
</p>
<br />

<p align="center">
<img src="" height="50%" width="50%" alt=""/>
</p>
<p>
Description
</p>
<br />

<p align="center">
<img src="" height="50%" width="50%" alt=""/>
</p>
<p>
Description
</p>
<br />

<p align="center">
<img src="" height="50%" width="50%" alt=""/>
</p>
<p>
Description
</p>
<br />

<p align="center">
<img src="" height="50%" width="50%" alt=""/>
</p>
<p>
Description
</p>
<br />
