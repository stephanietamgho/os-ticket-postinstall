<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (22H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure new Roles
- Configure new Departments
- Configure new Teams
- Allow new tickets creation
- Configure new Agents
- Configure new Users
- Configure new SLAs
- Configure new Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/UoBOnJv.png" height="80%" width="80%" alt="osticket-loginpage"/>
</p>
<p>
Log in to your Help Desk portal with the credentials you created during the installation phase.
</p>
<br />

<p>
<img src="https://i.imgur.com/racELsD.png" height="80%" width="80%" alt="osticket main page"/>
</p>
<p>
On your portal ensure you run as the Administrator. If "Agent Panel" is displayed, you are, in fact, running as the Admin. Otherwise, click on Admin Panel to see the Admin portal from which we are going to set up new configurations.
</p>
<br />

<p>1. CONFIGURE NEW ROLES</p>
<p>
<img src="https://i.imgur.com/yGafQOf.png" height="80%" width="80%" alt="New roles configuration"/>
</p>
<p>
On the Admin Panel, go to Agents > Roles > Add New Role.
</p>
<br />


<p>
<img src="https://i.imgur.com/gCBupbm.png" height="80%" width="80%" alt="New roles configuration"/>
</p>
<p>
Name it "System Administrator". 
</p>
<br />


<p>
<img src="https://i.imgur.com/uDq4oqM.png" height="80%" width="80%" alt="New roles configuration"/>
<img src="https://i.imgur.com/dxo957R.png" height="80%" width="80%" alt="New roles configuration"/>
</p>
<p>
You may edit its permission tickets settings: Permissions > Tickets and,  permission tasks settings: Permissions > Tasks.
</p>
<br />



<p>2. CONFIGURE NEW DEPARTMENTS</p>
<p>
<img src="https://i.imgur.com/lyYvdzn.png" height="80%" width="80%" alt="New Department configuration"/>
</p>
<p>
On the Admin Panel, go to Agents > Departments > Add New Role.  
</p>
<br />


<p>
<img src="https://i.imgur.com/oCHbCAW.png" height="80%" width="80%" alt="New department configuration"/>
</p>
<p>
Name it :System Administrators" and keep its default settings.
</p>
<br />


<p>2. CONFIGURE NEW TEAMS</p>
<p>
<img src="https://i.imgur.com/uJcVeIm.png" height="80%" width="80%" alt="New Teams configuration"/>
</p>
<p>
Still on the Admin Panel, go to Agents > Teams > Add New Teams. Name it "System Administrator". 
</p>
<br />


<p>
<img src="https://i.imgur.com/eCYNKoV.png" height="80%" width="80%" alt="New Teams configuration"/>
</p>
<p>
Name it however you like. I named mine "Level II Support", that'll handle more important matters.
</p>
<br />


<p>
<img src="https://i.imgur.com/wfALegn.png" height="80%" width="80%" alt="New Team configuration"/>
</p>
<p>
I also set myself as a memeber of the Level II support department. Go to the neighboring tab " Member", clicked on my name and "Add".
</p>
<br />


<p>4. ALLOW ANYONE TO CREATE TICKETS</p>
<p>
<img src="https://i.imgur.com/asOFNcN.png" height="80%" width="80%" alt="New tickets creation"/>
</p>
<p>
On the Admin Panel, go to Agents > Settings > User, and allow anyone to create tickets. Make sure you also check that registration is required. 
</p>
<br />

<p>5. CONFIGURE NEW AGENTS (WORKERS)</p>
<p>
<img src="https://i.imgur.com/IbjdNJz.png" height="80%" width="80%" alt="New agents configuration"/>
</p>
<p>
On the Admin Panel, go to Agents > Add New Agent. We will create two agents: John Clear and Jane Doe.
</p>
<br />


<p>
<img src="https://i.imgur.com/1g8ucDv.png" height="80%" width="80%" alt="New agents configuration"/>
</p>
<p>
Register John's full name and email address where users may reach him. Then set his login credentials by setting a new password. Click "password".
</p>
<br />


<p>
<img src="https://i.imgur.com/QeWFnwi.png" height="80%" width="80%" alt="New agents configuration"/>
</p>
<p>
When setting John's or an agent's password, uncheck the email confirmation prompt.
</p>
<br />


<p>
<img src="https://i.imgur.com/O5f5Isb.png" height="80%" width="80%" alt="New agents configuration"/>
<img src="https://i.imgur.com/d3PWb4.png" height="80%" width="80%" alt="New agents configuration"/>
<img src="https://i.imgur.com/HUQa0fJ.png" height="80%" width="80%" alt="New agents configuration"/>
</p>
<p>
You may configure your agent's permissions, assign your agent a department, a role as well, using the neighborings tabs.
</p>
<br />


<p>
<img src="https://i.imgur.com/gpYZczx.png" height="80%" width="80%" alt="New agents configuration"/>
</p>
<p>
The new agents' list.
</p>
<br />


<p>6. CONFIGURE NEW USERS (CUSTOMERS)</p>
<p>
<img src="https://i.imgur.com/racELsD.png" height="80%" width="80%" alt="New USERS configuration"/>
</p>
<p>
Switch to Agent Panel by clicking on it. 
</p>
<br />


<p>
<img src="https://i.imgur.com/lxX7CXC.png" height="80%" width="80%" alt="New users configuration"/>
</p>
<p>
I will create two users but you can create as many as you want. 
</p>
<br />


<p>
<img src="https://i.imgur.com/5iFr2GM.png" height="80%" width="80%" alt="New users configuration"/>
</p>
<p>
On the Agent Panel, go to Users > Add New User. 
</p>
<br />


<p>
<img src="https://i.imgur.com/0xxTZom.png" height="80%" width="80%" alt="New users configuration"/>
</p>
<p>
I created Teddy's profile and followed the same procedure with Suszy's. Then I click on "Add User".
</p>
<br />

<p>7. CONFIGURE NEW SLA </p>
<p>
<img src="https://i.imgur.com/gUqOYzp.png" height="80%" width="80%" alt="New SLA configuration"/>
</p>
<p>
Back to the Admin Panel, go to Manage > SLA > Add SLA plan
</p>
<br />


<p>
<img src="https://i.imgur.com/yGafQOf.png" height="80%" width="80%" alt="New roles configuration"/>
</p>
<p>
On the Admin Panel, go to Agents > Roles > Add New Role. Name it "System Administrator". 
</p>
<br />


<p>
<img src="https://i.imgur.com/yGafQOf.png" height="80%" width="80%" alt="New roles configuration"/>
</p>
<p>
On the Admin Panel, go to Agents > Roles > Add New Role. Name it "System Administrator". 
</p>
<br />


<p>
<img src="https://i.imgur.com/yGafQOf.png" height="80%" width="80%" alt="New roles configuration"/>
</p>
<p>
On the Admin Panel, go to Agents > Roles > Add New Role. Name it "System Administrator". 
</p>
<br />


<p>
<img src="https://i.imgur.com/yGafQOf.png" height="80%" width="80%" alt="New roles configuration"/>
</p>
<p>
On the Admin Panel, go to Agents > Roles > Add New Role. Name it "System Administrator". 
</p>
<br />


<p>
<img src="https://i.imgur.com/yGafQOf.png" height="80%" width="80%" alt="New roles configuration"/>
</p>
<p>
On the Admin Panel, go to Agents > Roles > Add New Role. Name it "System Administrator". 
</p>
<br />


<p>
<img src="https://i.imgur.com/yGafQOf.png" height="80%" width="80%" alt="New roles configuration"/>
</p>
<p>
On the Admin Panel, go to Agents > Roles > Add New Role. Name it "System Administrator". 
</p>
<br />


<p>
<img src="https://i.imgur.com/yGafQOf.png" height="80%" width="80%" alt="New roles configuration"/>
</p>
<p>
On the Admin Panel, go to Agents > Roles > Add New Role. Name it "System Administrator". 
</p>
<br />


<p>
<img src="https://i.imgur.com/yGafQOf.png" height="80%" width="80%" alt="New roles configuration"/>
</p>
<p>
On the Admin Panel, go to Agents > Roles > Add New Role. Name it "System Administrator". 
</p>
<br />


<p>
<img src="https://i.imgur.com/yGafQOf.png" height="80%" width="80%" alt="New roles configuration"/>
</p>
<p>
On the Admin Panel, go to Agents > Roles > Add New Role. Name it "System Administrator". 
</p>
<br />


<p>
<img src="https://i.imgur.com/yGafQOf.png" height="80%" width="80%" alt="New roles configuration"/>
</p>
<p>
On the Admin Panel, go to Agents > Roles > Add New Role. Name it "System Administrator". 
</p>
<br />


<p>
<img src="https://i.imgur.com/yGafQOf.png" height="80%" width="80%" alt="New roles configuration"/>
</p>
<p>
On the Admin Panel, go to Agents > Roles > Add New Role. Name it "System Administrator". 
</p>
<br />


<p>
<img src="https://i.imgur.com/yGafQOf.png" height="80%" width="80%" alt="New roles configuration"/>
</p>
<p>
On the Admin Panel, go to Agents > Roles > Add New Role. Name it "System Administrator". 
</p>
<br />


<p>
<img src="https://i.imgur.com/yGafQOf.png" height="80%" width="80%" alt="New roles configuration"/>
</p>
<p>
On the Admin Panel, go to Agents > Roles > Add New Role. Name it "System Administrator". 
</p>
<br />


<p>
<img src="https://i.imgur.com/yGafQOf.png" height="80%" width="80%" alt="New roles configuration"/>
</p>
<p>
On the Admin Panel, go to Agents > Roles > Add New Role. Name it "System Administrator". 
</p>
<br />


<p>
<img src="https://i.imgur.com/yGafQOf.png" height="80%" width="80%" alt="New roles configuration"/>
</p>
<p>
On the Admin Panel, go to Agents > Roles > Add New Role. Name it "System Administrator". 
</p>
<br />
